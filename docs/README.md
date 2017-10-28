# Alzheimer's Disease Challenge Hackathon: Datasets

There are two data sets that have been compiled from raw ADNI data for the PyCon UK 2017 Alzheimer's Challenge Hackathon.



## LB1_LB2: Longitudinal training set
> Longitudinal measurements (i.e. over multiple visits) with associated outcomes (i.e. labelled training set) compiled from the entire ADNI history. Contains all individuals that have provided data in at least two visits (different dates) across ADNI1, ADNI GO and ADNI2 **up until May 2010**. Data from sources such as MR & PET imaging, cognitive tests, CSF biomarkers and clinical assessment have been processed using standard ADNI data pipelines.
> 
> Individuals flagged under the `LB2` column are rollover individuals who will be participating in ADNI3. This is the population for whom TADPOLE predictions should be made. For the PyCon UK hackathon, predicted outcomes will be evaluated against a held-out test set (i.e. recent visits from LB2 rollover patients). For the wider TADPOLE Challenge, predicted outcomes will be evaluated against ADNI3 rollovers once this data is collected in 2018.

For more information including a full data dictionary, please see [data_dictionary.md](data_dictionary.md) or you can download the data dictionary in CSV format [here](tadpole_data_dictionary.csv).



## LB4: Longitudinal held-out test set
> Longitudinal measurements for visits for LB2 patients **from May 2010 onwards**.

The columns for the LB4 test set are identical to those used for LB1_LB2, i.e. please see [data_dictionary.md](data_dictionary.md) for detailed information on columns or you can download the data dictionary in CSV format [here](tadpole_data_dictionary.csv).


## Dataset summary
[See here for a friendly intro](https://www.quora.com/How-does-Diffusion-Tensor-Imaging-DTI-work-and-how-is-it-used-in-neuroscience) to neuro-imaging methods (MRI and DTI) written by DARPA's former chief scientist. The TADPOLE Challenge website also has an [excellent overview of the cognitive tests, MRI measures, PET measures, CSF measures and risk factors](https://tadpole.grand-challenge.org/data/) used.


### TADPOLE specific features
- `D1`, `D2` and `LB1` columns can be ignored.
- `LB2` denotes whether this participant exists in the `LB4` hackathon test set.
- `DXCHANGE` codes clinical status 1=Stable:NL to NL, 2=Stable:MCI to MCI, 3=Stable:AD to AD, 4=Conv:NL to MCI, 5=Conv:MCI to AD, 6=Conv:NL to AD, 7=Rev:MCI to NL, 8=Rev:AD to MCI, 9=Rev:AD to NL, -1=Not available |


### ADNIMERGE
> Key ADNI tables merged into one table.

- Identifiers (`RID`, `PTID`)
- Data collection metadata such as visit code (`VISCODE`), site (`SITE`), collection protocols (`COLPROT`, `ORIGPROT`), examination date (`EXAMDATE`)
- Demographics at baseline (baseline Dx, age, gender, education, ethnicity, race, marital status)
- Medical imaging data (e.g. `FDG` is "average FDG-PET of angular, temporal, and posterior cingulate")
- Clinical & cognitive test data: Clinical Dementia Rating (`CDRSB`); ADAS (Alzheimer's Disease Assessment Scale), both `ADAS11` and `ADAS13`; Mini-Mental State Examination (`MMSE`), Rey Auditory Verbal Learning Test (`RAVLT`, `RAVLT_immediate`)
- Ecog features: for both participant and study partner (mem, lang, vis/spat, plan, organ, div atten, total)
- UCSFFSX data: `Ventricles`, `Hippocampus`, `WholeBrain`, `Entorhinal`, `Fusiform`, `MidTemp`, `ICV`
- Many of the above have equivalent baseline metrics, e.g. `CDRSB_bl`, `ADAS11_bl`, `ADAS13_bl`, `Ventricles_bl` and more; also time measured since baseline in years (`Years_bl`) and months (`Month_bl`) and months rounded (`Month`, `M`).


### UCSFFSL
> MRI biomarkers (FreeSurfer longitudinally processed ROIs from UCSFFSL tables).

- Identifiers (`RID_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16`)
- Study metadata (visit codes)
- MRI data: field strength, scan data, study UID, series UID, image UID, rundate, version, status, overall quality rating
- MRI base image includes a timepoint N image: where N in [1, 8] (e.g. `BASETP1_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16`, `BASETP2_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16`)
- Partial ratings ("QC variables") of temporal lobe, frontal lobe, parietal lobe, insula, occipital lobe, basal ganglia, cerebral WM, ventricles.
- MRI detail: formatted as `ST{X}{Y}_{Z}` where `{X}` is number between 1-130 corresponding to region (e.g. `RightParahippocampal`); `{Y}` is e.g. `SV`/`CV` for volume, `SA` for surface area, `TA`/`TS` for average/sd of cortical thickness, etc; and `{Z}` is always `_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16`. For example, `ST100SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16`.


### UCSFFSX
> Cross-sectional MRI biomarkers (processed with FreeSurfer).

This dataset is very similar in features to the UCSFFSL data.


### BAIPETNMRC
> PET ROI-based biomarkers (FDG) from the Banner Alzheimer's Institute PET NMRC Summaries.

- Identifiers (`RID_BAIPETNMRC_09_12_16`)
- Study metadata (visit codes, examination date, table version, image identifiers, date analysis performed, complete/incomplete)
- Normalised CMRgl data (CMRgl is "total or regional Cerebral Glucose Metabolism (CMRgl) as measured by positron emission tomography (PET)"): formatted as `{X}{Y}_{Z}` where `{X}` is a region identifier such as `HIPPL` ("Hippocampus_L") or `FRTSUPL` ("Frontal_sup_L"); `{Y}` is a number from 01-12 (unknown what this constitutes, possibly related to months since baseline but this is purely a guess!); and `{Z}` is always `_BAIPETNMRC_09_12_16`
- Additional PET data: formatted as `{X}_{Z}` where `{X}` may have a description (e.g. `ACI` is "amyloid convergence index for AV-45 subjects") or it may not (e.g. `FROITRN001`), and `{Z}` is always `_BAIPETNMRC_09_12_16`


### UCBERKELEYAV45
> PET ROI-based biomarkers (AV45) from the UC Berkeley AV45 analysis.

- Identifiers (`RID_UCBERKELEYAV45_10_17_16`)
- Study metadata (visit codes, date of AV45 scan)
- AV45 data - florbetapir mean (`CEREBELLUMGREYMATTER`, `WHOLECEREBELLUM`, `ERODED_SUBCORTICALWM`, `COMPOSITE_REF`, `FRONTAL`, `CINGULATE`, `PARIETAL`, `TEMPORAL`)
- AV45 data - summary florbetapir (`SUMMARYSUVR_{X}` where `{X}` might be e.g `WHOLECEREBNORM` or `COMPOSITE_REFNORM`)
- AV45 data - ventricles (e.g. `VENTRICLE_3RD`, `VENTRICLE_3RD_SIZE`)
- AV45 data - cingulate cortex (`CC_{X}` where `{X}` might be e.g. `ANTERIOR`, `ANTERIOR_SIZE`)
- AV45 data - cerebrospinal fluid (`CSF` and `CSF_SIZE`)
- AV45 data - CTX (`CTX_{X}_{Y}` where `{X}` is either left/right (`LH`/`RH`) and `{Y}` is e.g. `BANKSSTS`, `BANKSSTS_SIZE`, `MEDIALORBITOFRONTAL`, `MEDIALORBITOFRONTAL_SIZE`)
- AV45 data - other (either `LEFT_{X}`, e.g. `LEFT_ACCUMBENS_AREA` or `RIGHT_{X}`, e.g. `RIGHT_AMYGDALA_SIZE`, or neither, e.g. `NON_WM_HYPOINTENSITIES` and `OPTIC_CHIASM`)
- Notes on AV45 data: all features end in `_UCBERKELEYAV45_10_17_16`; and many of the features are represented as both the AV45 uptake in that subregion (e.g. `CC_ANTERIOR`) and the ROI size in mm^3 (e.g. `CC_ANTERIOR_SIZE`)


### UCBERKELEYAV1451
> PET ROI-based biomarkers (AV1451) from the UC Berkeley AV1451 analysis.

This dataset is very similar in features and structure to the UCBERKELEYAV45 data.


### DTIROI
> [Diffusion Tensor Imaging (DTI)](https://www.quora.com/How-does-Diffusion-Tensor-Imaging-DTI-work-and-how-is-it-used-in-neuroscience) looks at diffusion in the brain to understand where there are blood vessels in the brain, the width of vessels and their orientation. These DTI biomarkers represent ROI summary measures (e.g. mean diffusivity MD, axial diffusivity AD) taken from the ADNI spreadsheet `DTIROI_04_30_14.csv`.

- Identifiers (`RID_DTIROI_04_30_14`)
- Study metadata (visit codes, examination date, version, image IDs, date, status)
- Fractional anisotropy (FA, "a scalar value between zero and one that describes the degree of anisotropy of a diffusion process"): features like `FA_{X}_{Y}` where `{X}` is e.g. `CST` ("Corticospinal tract") and `{Y}` is `L` or `R`)
- Mean diffusivity (MD): features like `MD_{X}_{Y}` where `{X}` is region (e.g. `CST`) and `{Y}` is `L`/`R`
- Radial diffusivity (RD): features like `RD_{X}_{Y}` where `{X}` is region (e.g. `CST`) and `{Y}` is `L`/`R`
- Axial diffusivity (AD): features like `AD_{X}_{Y}` where `{X}` is region (e.g. `CST`) and `{Y}` is `L`/`R`
- Notes on DTIROI data: all features end in `_DTIROI_04_30_14`.


### UPENNBIOMK9
> Three CSF biomarkers (Amyloid-beta, Tau and P-Tau) taken from the UPENN Elecsys analysis (originally derived from ADNI's `UPENNBIOMK9_04_19_17.csv` spreadsheet).

- Identifiers (`RID_UPENNBIOMK9_04_19_17`)
- Study metadata (visit codes, examination date, study phase, analysis batch, reagents lot number, calibrator/quality control lot number, analysis run date)
- CSF biomarkers: `ABETA` (amyloid-beta), `TAU` and `PTAU` (all in pg/ml).
- `COMMENT` ("extrapolated ABETA result")
- Notes on UPENNBIOMK9 data: all features end in `__UPENNBIOMK9_04_19_17`.
