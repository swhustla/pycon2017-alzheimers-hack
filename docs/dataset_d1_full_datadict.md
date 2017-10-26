# Alzheimer's Disease Challenge Hackathon: Dataset D1 (Full Data Dictionary)

For more information on other datasets, please see [datasets.md](datasets.md). For a high level summary of the D1 data set, please see [dataset_d1.md](dataset_d1.md).

## D1: Longitudinal training set
> Longitudinal measurements (i.e. over multiple visits) with associated outcomes (i.e. labelled training set) compiled from the entire ADNI history. Contains all individuals that have provided data in at least two visits (different dates) across ADNI1, ADNI GO and ADNI2. Data from sources such as MR & PET imaging, cognitive tests, CSF biomarkers and clinical assessment have been processed using standard ADNI data pipelines.


## Full data dictionary

| Column | Description | Source table |
| -- | -- | -- |
| RID | Participant roster ID (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | ADNIMERGE |
| PTID | Participant ID (Additional notes: 3 digit site number and 4 digit roster ID (RID) separated by '_S_') | ADNIMERGE |
| VISCODE | Visit code | ADNIMERGE |
| D1 | Denotes whether participant belongs to dataset D1 |   |
| D2 | Denotes whether participant belongs to dataset D2 |   |
| DXCHANGE | 1=Stable:NL to NL, 2=Stable:MCI to MCI, 3=Stable:AD to AD, 4=Conv:NL to MCI, 5=Conv:MCI to AD, 6=Conv:NL to AD, 7=Rev:MCI to NL, 8=Rev:AD to MCI, 9=Rev:AD to NL, -1=Not available |   |
| SITE | Site | ADNIMERGE |
| COLPROT | Protocol under which data was collected | ADNIMERGE |
| ORIGPROT | Protocol from which subject originated | ADNIMERGE |
| EXAMDATE | Examination Date (Additional notes: From registry table) | ADNIMERGE |
| DX_bl | Baseline Dx (Additional notes: From studysum table) | ADNIMERGE |
| AGE | Age at baseline (Additional notes: From ptdemog table) | ADNIMERGE |
| PTGENDER | Sex (Additional notes: From ptdemog table) | ADNIMERGE |
| PTEDUCAT | Education (Additional notes: From ptdemog table) | ADNIMERGE |
| PTETHCAT | Ethnicity (Additional notes: From ptdemog table) | ADNIMERGE |
| PTRACCAT | Race (Additional notes: From ptdemog table) | ADNIMERGE |
| PTMARRY | Marital status at baseline (Additional notes: From ptdemog table) | ADNIMERGE |
| APOE4 | ApoE4 (Additional notes: From apoe table) | ADNIMERGE |
| FDG | Average FDG-PET of angular, temporal, and posterior cingulate (Additional notes: From ucberkeleyfdg table) | ADNIMERGE |
| PIB | Average PIB SUVR of frontal cortex, anterior cingulate, precuneus cortex, and parietal cortex (Additional notes: From pibpetsuvr table) | ADNIMERGE |
| AV45 | Average AV45 SUVR of frontal, anterior cingulate, precuneus, and parietal cortex relative to the cer (Additional notes: From ucberkeleyav45 table) | ADNIMERGE |
| CDRSB | CDR-SB (Additional notes: From cdr table) | ADNIMERGE |
| ADAS11 | ADAS 11 (Additional notes: From adas table) | ADNIMERGE |
| ADAS13 | ADAS 13 (Additional notes: From adas table) | ADNIMERGE |
| MMSE | MMSE (Additional notes: From mmse table) | ADNIMERGE |
| RAVLT | RAVLT (forgetting) (Additional notes: From neurobat table) | ADNIMERGE |
| RAVLT_immediate | RAVLT (5 sum) (Additional notes: From neurobat table) | ADNIMERGE |
| FAQ | FAQ (Additional notes: From neurobat table) | ADNIMERGE |
| MOCA | MOCA (Additional notes: From moca table) | ADNIMERGE |
| EcogPtMem | Participant ECog - Mem (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtLang | Participant ECog - Lang (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtVisspat | Participant ECog - Vis/Spat (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtPlan | Participant ECog - Plan (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtOrgan | Participant ECog - Organ (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtDivatt | Participant ECog - Div atten (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtTotal | Participant ECog - Total (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogSPMem | Study Partner ECog - Mem (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPLang | Study Partner ECog - Lang (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPVisspat | Study Partner ECog - Vis/Spat (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPPlan | Study Partner ECog - Plan (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPOrgan | Study Partner ECog - Organ (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPDivatt | Study Partner ECog - Div atten (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPTotal | Study Partner ECog - Total (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| Ventricles | UCSF Ventricles (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Hippocampus | UCSF Hippocampus (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| WholeBrain | UCSF WholeBrain (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Entorhinal | UCSF Entorhinal (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Fusiform | UCSF Fusiform (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| MidTemp | UCSF Med Temp (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| ICV | UCSF ICV (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| DX | Dx status (Additional notes: From studysum table) | ADNIMERGE |
| EXAMDATE_bl | Examination Date at baseline (Additional notes: From registry table) | ADNIMERGE |
| CDRSB_bl | CDR-SB at baseline (Additional notes: From cdr table) | ADNIMERGE |
| ADAS11_bl | ADAS 11 at baseline (Additional notes: From adas table) | ADNIMERGE |
| ADAS13_bl | ADAS 13 at baseline (Additional notes: From adas table) | ADNIMERGE |
| MMSE_bl | MMSE at baseline (Additional notes: From mmse table) | ADNIMERGE |
| RAVLT_bl | RAVLT (forgetting) at baseline (Additional notes: From neurobat table) | ADNIMERGE |
| RAVLT_immediate_bl | RAVLT (5 sum) at baseline (Additional notes: From neurobat table) | ADNIMERGE |
| FAQ_bl | FAQ at baseline (Additional notes: From neurobat table) | ADNIMERGE |
| Ventricles_bl | UCSF Ventricles at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Hippocampus_bl | UCSF Hippocampus at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| WholeBrain_bl | UCSF WholeBrain at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Entorhinal_bl | UCSF Entorhinal at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| Fusiform_bl | UCSF Fusiform at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| MidTemp_bl | UCSF Med Temp at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| ICV_bl | UCSF ICV at baseline (Additional notes: From ucsffsx and ucsffsx51 tables) | ADNIMERGE |
| MOCA_bl | MOCA at baseline (Additional notes: From moca table) | ADNIMERGE |
| EcogPtMem_bl | Pt ECog - Mem at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtLang_bl | Pt ECog - Lang at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtVisspat_bl | Pt ECog - Vis/Spat at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtPlan_bl | Pt ECog - Plan at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtOrgan_bl | Pt ECog - Organ at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtDivatt_bl | Pt ECog - Div atten at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogPtTotal_bl | Pt ECog - Total at baseline (Additional notes: Mean of non-missing responses from ecogpt table) | ADNIMERGE |
| EcogSPMem_bl | SP ECog - Mem at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPLang_bl | SP ECog - Lang at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPVisspat_bl | SP ECog - Vis/Spat at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPPlan_bl | SP ECog - Plan at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPOrgan_bl | SP ECog - Organ at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPDivatt_bl | SP ECog - Div atten at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| EcogSPTotal_bl | SP ECog - Total at baseline (Additional notes: Mean of non-missing responses from ecogsp table) | ADNIMERGE |
| FDG_bl | Average FDG-PET of angular, temporal, and posterior cingulate at baseline (Additional notes: From ucberkeleyfdg table) | ADNIMERGE |
| PIB_bl | Average PIB SUVR of frontal cortex, anterior cingulate, precuneus cortex, and parietal cortex at bas (Additional notes: From pibpetsuvr table) | ADNIMERGE |
| AV45_bl | Average AV45 SUVR of frontal, anterior cingulate, precuneus, and parietal cortex relative to the cer (Additional notes: From ucberkeleyav45 table) | ADNIMERGE |
| Years_bl | Years from baseline (Additional notes: From registry EXAMDATEs) | ADNIMERGE |
| Month_bl | Months from baseline (Additional notes: From registry EXAMDATEs) | ADNIMERGE |
| Month | Months from baseline (to nearest 6 months, as a factor) (Additional notes: From registry EXAMDATEs) | ADNIMERGE |
| M | Months from baseline (to nearest 6 months, as continuous) (Additional notes: From registry EXAMDATEs) | ADNIMERGE |
| RID_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Participant roster ID (Type: T) (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | UCSFFSL |
| VISCODE_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Visit code (Type: T) | UCSFFSL |
| VISCODE2_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Translated visit code (Additional notes: Months from baseline rounded to nearest 6 months) | UCSFFSL |
| FLDSTRENG_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | The field strength. 1.5 or 3 (Type: D) | UCSFFSL |
| EXAMDATE_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | The scan date for the image processed (Type: D) | UCSFFSL |
| LONISID_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | The LONI study UID for the image processed (Type: T) | UCSFFSL |
| LONIUID_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | The LONI series UID for the image processed. (Type: T) | UCSFFSL |
| IMAGEUID_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | The ImageUID for the image processed. (Type: T) | UCSFFSL |
| RUNDATE_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 |  (Type: D) | UCSFFSL |
| VERSION_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 |  (Type: D) | UCSFFSL |
| STATUS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 |  (Type: T) (Rangeval: complete/partial) | UCSFFSL |
| BASETP1_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 1 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP2_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 2 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP3_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 3 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP4_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 4 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP5_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 5 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP6_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 6 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP7_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 7 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| BASETP8_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Whether or not the base image includes a timepoint 8 image. (Type: N) (Code: 0 = No, 1 = Yes) | UCSFFSL |
| OVERALLQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | An overall quality rating. Refer to additional QC variables for Partial rating. (Type: T) (Code: Pass/Fail/Partial) | UCSFFSL |
| TEMPQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of temporal lobe. Fail affects the following regions: LeftTemporalPole (ST60); RightTempor (Type: T) (Code: Pass/Fail) | UCSFFSL |
| FRONTQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the frontal lobe. Fail affects the following regions: LeftFrontalPole (ST25); RightFron (Type: T) (Code: Pass/Fail) | UCSFFSL |
| PARQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the parietal lobe. Fail affects the following regions: LeftPostcentral (ST49); RightPos (Type: T) (Code: Pass/Fail) | UCSFFSL |
| INSULAQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the insula. Fail affects the following regions: LeftInsula (ST129); RightInsula (ST130) (Type: T) (Code: Pass/Fail) | UCSFFSL |
| OCCQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the occipital lobe. Fail affects the following regions: LeftLingual (ST38); RightLingua (Type: T) (Code: Pass/Fail) | UCSFFSL |
| BGQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the basal ganglia. Fail affects the following regions: LeftPutamen (ST53); RightPutamen (Type: T) (Code: Pass/Fail) | UCSFFSL |
| CWMQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the cerebral WM. Fail affects the following regions: LeftCerebralWM (ST20); RightCerebr (Type: T) (Code: Pass/Fail) | UCSFFSL |
| VENTQC_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | QC rating of the ventricles. Fail affects the following regions: LeftLateralVentricle (ST37); RightL (Type: T) (Rangeval: Pass/Fail) | UCSFFSL |
| ST100SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightNonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST101SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightPallidum (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST102CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST102SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST102TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST102TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST103CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST103SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST103TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST103TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST104CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST104SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST104TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST104TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST105CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST105SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST105TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST105TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST106CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST106SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST106TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST106TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST107CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST107SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST107TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST107TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST108CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST108SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST108TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST108TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST109CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST109SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST109TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST109TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST10CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of Icv (Type: N) (Length: 15) (Decimal: 8) (Units: mm3) | UCSFFSL |
| ST110CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST110SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST110TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST110TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST111CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST111SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST111TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST111TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST112SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightPutamen (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST113CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST113SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST113TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST113TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST114CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST114SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST114TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST114TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST115CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST115SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST115TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST115TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST116CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST116SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST116TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST116TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST117CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST117SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST117TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST117TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST118CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST118SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST118TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST118TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST119CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST119SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST119TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST119TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST11SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftAccumbensArea (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST120SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightThalamus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST121CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST121SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST121TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST121TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST122SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightUndetermined (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST123CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST123SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST123TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST123TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST124SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightVentralDC (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST125SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightVessel (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST126SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST127SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of ThirdVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST128SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of WMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST129CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST129SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST129TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST129TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST12SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftAmygdala (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST130CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST130SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST130TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST130TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST13CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST13SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST13TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST13TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST14CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST14SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST14TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST14TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST15CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST15SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST15TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST15TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST16SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftCaudate (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST17SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftCerebellumCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST18SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftCerebellumWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST19SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftCerebralCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST1SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of Brainstem (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST20SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftCerebralWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST21SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftChoroidPlexus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST22CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST22SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST22TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST22TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST23CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST23SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST23TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST23TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST24CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST24SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST24TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST24TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST25CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST25SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST25TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST25TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST26CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST26SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST26TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST26TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST27SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftHemisphere (Type: N) (Length: 16) (Decimal: 2) (Units: mm2) | UCSFFSL |
| ST28CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftHemisphereWM (Type: N) (Length: 10) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST29SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftHippocampus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST2SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of CorpusCallosumAnterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST30SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftInferiorLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST31CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST31SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST31TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST31TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST32CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST32SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST32TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST32TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST33SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftInterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST34CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST34SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST34TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST34TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST35CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST35SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST35TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST35TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST36CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST36SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST36TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST36TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST37SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST38CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST38SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST38TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST38TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST39CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST39SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST39TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST39TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST3SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of CorpusCallosumCentral (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST40CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST40SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST40TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST40TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST41SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftNonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST42SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftPallidum (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST43CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST43SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST43TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST43TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST44CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST44SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST44TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST44TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST45CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST45SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST45TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST45TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST46CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST46SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST46TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST46TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST47CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST47SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST47TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST47TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST48CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST48SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST48TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST48TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST49CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST49SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST49TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST49TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST4SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of CorpusCallosumMidAnterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST50CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST50SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST50TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST50TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST51CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST51SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST51TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST51TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST52CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST52SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST52TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST52TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST53SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftPutamen (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST54CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST54SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST54TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST54TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST55CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST55SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST55TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST55TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST56CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST56SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST56TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST56TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST57CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST57SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST57TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST57TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST58CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST58SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST58TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST58TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST59CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST59SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST59TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST59TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST5SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of CorpusCallosumMidPosterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST60CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST60SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST60TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST60TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST61SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftThalamus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST62CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST62SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST62TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST62TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST63SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftUndetermined (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST64CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of LeftUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST64SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of LeftUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST64TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of LeftUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST64TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of LeftUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST65SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftVentralDC (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST66SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftVessel (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST67SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of LeftWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST68SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of NonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST69SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of OpticChiasm (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST6SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of CorpusCallosumPosterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST70SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightAccumbensArea (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST71SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightAmygdala (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST72CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST72SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST72TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST72TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST73CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST73SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST73TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST73TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST74CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST74SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST74TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST74TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST75SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightCaudate (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST76SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightCerebellumCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST77SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightCerebellumWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST78SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightCerebralCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST79SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightCerebralWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST7SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of Csf (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST80SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightChoroidPlexus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST81CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST81SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST81TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST81TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST82CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST82SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST82TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST82TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST83CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST83SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST83TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST83TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST84CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST84SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST84TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST84TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST85CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST85SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST85TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST85TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST86SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightHemisphere (Type: N) (Length: 16) (Decimal: 2) (Units: mm2) | UCSFFSL |
| ST87CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightHemisphereWM (Type: N) (Length: 10) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST88SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightHippocampus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST89SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightInferiorLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST8SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of FifthVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST90CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST90SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST90TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST90TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST91CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST91SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST91TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST91TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST92SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightInterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST93CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST93SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST93TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST93TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST94CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST94SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST94TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST94TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST95CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST95SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST95TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST95TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST96SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of RightLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| ST97CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST97SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST97TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST97TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST98CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST98SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST98TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST98TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST99CV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (Cortical Parcellation) of RightMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSL |
| ST99SA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Surface Area of RightMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSL |
| ST99TA_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Average of RightMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST99TS_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Cortical Thickness Standard Deviation of RightMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSL |
| ST9SV_UCSFFSL_02_01_16_UCSFFSL51ALL_08_01_16 | Volume (WM Parcellation) of FourthVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSL |
| RID_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Participant roster ID (Type: T) (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | UCSFFSX |
| VISCODE_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Visit code (Type: T) | UCSFFSX |
| EXAMDATE_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | The scan date for the image processed (Type: D) | UCSFFSX |
| VERSION_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 |  (Type: D) | UCSFFSX |
| FLDSTRENG_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | The field strength. 1.5 or 3 (Type: D) | UCSFFSX |
| LONISID_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | The LONI study UID for the image processed (Type: T) | UCSFFSX |
| LONIUID_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | The LONI series UID for the image processed. (Type: T) | UCSFFSX |
| IMAGEUID_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | The ImageUID for the image processed. (Type: T) | UCSFFSX |
| RUNDATE_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 |  (Type: D) | UCSFFSX |
| STATUS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 |  (Type: T) (Rangeval: complete/partial) | UCSFFSX |
| OVERALLQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | An overall quality rating. Refer to additional QC variables for Partial rating. (Type: T) (Code: Pass/Fail/Partial) | UCSFFSX |
| TEMPQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of temporal lobe. Fail affects the following regions: LeftTemporalPole (ST60); RightTempor (Type: T) (Code: Pass/Fail) | UCSFFSX |
| FRONTQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the frontal lobe. Fail affects the following regions: LeftFrontalPole (ST25); RightFron (Type: T) (Code: Pass/Fail) | UCSFFSX |
| PARQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the parietal lobe. Fail affects the following regions: LeftPostcentral (ST49); RightPos (Type: T) (Code: Pass/Fail) | UCSFFSX |
| INSULAQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the insula. Fail affects the following regions: LeftInsula (ST129); RightInsula (ST130) (Type: T) (Code: Pass/Fail) | UCSFFSX |
| OCCQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the occipital lobe. Fail affects the following regions: LeftLingual (ST38); RightLingua (Type: T) (Code: Pass/Fail) | UCSFFSX |
| BGQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the basal ganglia. Fail affects the following regions: LeftPutamen (ST53); RightPutamen (Type: T) (Code: Pass/Fail) | UCSFFSX |
| CWMQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the cerebral WM. Fail affects the following regions: LeftCerebralWM (ST20); RightCerebr (Type: T) (Code: Pass/Fail) | UCSFFSX |
| VENTQC_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | QC rating of the ventricles. Fail affects the following regions: LeftLateralVentricle (ST37); RightL (Type: T) (Rangeval: Pass/Fail) | UCSFFSX |
| ST100SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightNonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST101SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightPallidum (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST102CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST102SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST102TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST102TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST103CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST103SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST103TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST103TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST104CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST104SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST104TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST104TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST105CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST105SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST105TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST105TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST106CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST106SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST106TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST106TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST107CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST107SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST107TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST107TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST108CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST108SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST108TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST108TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST109CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST109SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST109TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST109TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST10CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of Icv (Type: N) (Length: 15) (Decimal: 8) (Units: mm3) | UCSFFSX |
| ST110CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST110SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST110TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST110TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST111CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST111SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST111TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST111TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST112SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightPutamen (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST113CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST113SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST113TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST113TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST114CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST114SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST114TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST114TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST115CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST115SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST115TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST115TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST116CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST116SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST116TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST116TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST117CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST117SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST117TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST117TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST118CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST118SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST118TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST118TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST119CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST119SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST119TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST119TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST11SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftAccumbensArea (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST120SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightThalamus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST121CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST121SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST121TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST121TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST122SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightUndetermined (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST123CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST123SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST123TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST123TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST124SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightVentralDC (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST125SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightVessel (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST126SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST127SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of ThirdVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST128SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of WMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST129CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST129SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST129TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST129TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST12SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftAmygdala (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST130CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST130SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightInsula (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST130TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST130TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightInsula (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST13CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST13SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST13TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST13TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST14CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST14SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST14TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST14TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST15CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST15SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST15TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST15TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST16SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftCaudate (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST17SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftCerebellumCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST18SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftCerebellumWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST19SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftCerebralCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST1SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of Brainstem (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST20SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftCerebralWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST21SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftChoroidPlexus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST22CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST22SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST22TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST22TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST23CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST23SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST23TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST23TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST24CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST24SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST24TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST24TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST25CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST25SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST25TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST25TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST26CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST26SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST26TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST26TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST27SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftHemisphere (Type: N) (Length: 16) (Decimal: 2) (Units: mm2) | UCSFFSX |
| ST28CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftHemisphereWM (Type: N) (Length: 10) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST29SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftHippocampus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST2SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of CorpusCallosumAnterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST30SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftInferiorLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST31CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST31SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST31TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST31TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST32CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST32SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST32TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST32TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST33SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftInterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST34CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST34SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST34TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST34TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST35CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST35SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST35TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST35TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST36CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST36SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST36TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST36TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST37SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST38CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST38SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST38TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST38TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST39CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST39SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST39TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST39TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST3SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of CorpusCallosumCentral (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST40CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST40SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST40TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST40TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST41SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftNonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST42SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftPallidum (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST43CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST43SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftParacentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST43TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST43TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftParacentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST44CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST44SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftParahippocampal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST44TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST44TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftParahippocampal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST45CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST45SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftParsOpercularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST45TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST45TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftParsOpercularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST46CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST46SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftParsOrbitalis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST46TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST46TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftParsOrbitalis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST47CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST47SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftParsTriangularis (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST47TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST47TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftParsTriangularis (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST48CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST48SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftPericalcarine (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST48TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST48TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftPericalcarine (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST49CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST49SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftPostcentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST49TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST49TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftPostcentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST4SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of CorpusCallosumMidAnterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST50CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST50SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftPosteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST50TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST50TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftPosteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST51CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST51SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftPrecentral (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST51TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST51TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftPrecentral (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST52CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST52SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftPrecuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST52TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST52TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftPrecuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST53SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftPutamen (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST54CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST54SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftRostralAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST54TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST54TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftRostralAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST55CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST55SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftRostralMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST55TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST55TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftRostralMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST56CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST56SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftSuperiorFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST56TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST56TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST57CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST57SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftSuperiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST57TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST57TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST58CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST58SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftSuperiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST58TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST58TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftSuperiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST59CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST59SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftSupramarginal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST59TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST59TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftSupramarginal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST5SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of CorpusCallosumMidPosterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST60CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST60SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftTemporalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST60TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST60TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftTemporalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST61SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftThalamus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST62CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST62SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftTransverseTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST62TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST62TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftTransverseTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST63SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftUndetermined (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST64CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of LeftUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST64SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of LeftUnknown (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST64TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of LeftUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST64TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of LeftUnknown (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST65SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftVentralDC (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST66SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftVessel (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST67SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of LeftWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST68SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of NonWMHypoIntensities (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST69SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of OpticChiasm (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST6SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of CorpusCallosumPosterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST70SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightAccumbensArea (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST71SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightAmygdala (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST72CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST72SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightBankssts (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST72TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST72TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightBankssts (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST73CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST73SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightCaudalAnteriorCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST73TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST73TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightCaudalAnteriorCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST74CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST74SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightCaudalMiddleFrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST74TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST74TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightCaudalMiddleFrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST75SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightCaudate (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST76SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightCerebellumCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST77SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightCerebellumWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST78SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightCerebralCortex (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST79SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightCerebralWM (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST7SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of Csf (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST80SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightChoroidPlexus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST81CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST81SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightCorpusCallosum (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST81TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST81TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightCorpusCallosum (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST82CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST82SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightCuneus (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST82TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST82TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightCuneus (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST83CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST83SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightEntorhinal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST83TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST83TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightEntorhinal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST84CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST84SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightFrontalPole (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST84TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST84TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightFrontalPole (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST85CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST85SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightFusiform (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST85TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST85TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightFusiform (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST86SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightHemisphere (Type: N) (Length: 16) (Decimal: 2) (Units: mm2) | UCSFFSX |
| ST87CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightHemisphereWM (Type: N) (Length: 10) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST88SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightHippocampus (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST89SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightInferiorLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST8SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of FifthVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST90CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST90SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightInferiorParietal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST90TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST90TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightInferiorParietal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST91CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST91SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightInferiorTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST91TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST91TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightInferiorTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST92SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightInterior (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST93CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST93SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightIsthmusCingulate (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST93TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST93TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightIsthmusCingulate (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST94CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST94SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightLateralOccipital (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST94TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST94TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightLateralOccipital (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST95CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST95SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightLateralOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST95TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST95TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightLateralOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST96SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of RightLateralVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| ST97CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST97SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightLingual (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST97TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST97TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightLingual (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST98CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST98SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightMedialOrbitofrontal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST98TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST98TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightMedialOrbitofrontal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST99CV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (Cortical Parcellation) of RightMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm3) | UCSFFSX |
| ST99SA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Surface Area of RightMiddleTemporal (Type: N) (Length: 5) (Decimal: 0) (Units: mm2) | UCSFFSX |
| ST99TA_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Average of RightMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST99TS_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Cortical Thickness Standard Deviation of RightMiddleTemporal (Type: N) (Length: 4) (Decimal: 3) (Units: mm) | UCSFFSX |
| ST9SV_UCSFFSX_11_02_15_UCSFFSX51_08_01_16 | Volume (WM Parcellation) of FourthVentricle (Type: N) (Length: 8) (Decimal: 1) (Units: mm3) | UCSFFSX |
| RID_BAIPETNMRC_09_12_16 | Participant roster ID (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | BAIPETNMRC |
| VISCODE_BAIPETNMRC_09_12_16 | Visit code | BAIPETNMRC |
| VISCODE2_BAIPETNMRC_09_12_16 | Translated visit code (Additional notes: Months from baseline rounded to nearest 6 months) | BAIPETNMRC |
| EXAMDATE_BAIPETNMRC_09_12_16 | Examination Date (Additional notes: Please use MM/DD/YYYY format) | BAIPETNMRC |
| VERSION_BAIPETNMRC_09_12_16 | Version of Table | BAIPETNMRC |
| LONIUID_BAIPETNMRC_09_12_16 | LONI Unique Image Identifier (Additional notes: This is a longer description if necessary.) | BAIPETNMRC |
| RUNDATE_BAIPETNMRC_09_12_16 | DATE analysis performed (Additional notes: Please use MM/DD/YYYY format) | BAIPETNMRC |
| STATUS_BAIPETNMRC_09_12_16 | Complete/Incomplete | BAIPETNMRC |
| HIPPL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Hippocampus_L (Units: Normalized Counts) (Additional notes: (1). Included baseline FDG-PET scans after excluding scans with QA/acquisioon concerns, ANOVA  desig) | BAIPETNMRC |
| FRTSUPL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_sup_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTMIDL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_mid_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARAHIPL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from ParaHippocampal_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FUSFRML01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Fusiform_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| OCCMIDL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Occipital_mid_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| ANGULL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Angular_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARIINFL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| SUPMRGL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from SupraMarginal_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPMIDL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal _mid_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PRECUNL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Precuneus_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGPSTL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Post_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARAHIPR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from ParaHippocampal_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTSUPR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Sup_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| OCCMIDR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Occipital_mid_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FUSFRMR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Fusiform_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTMIDR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_mid_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| ANGULR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Angular_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARIINFR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Inf_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPMIDR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_mid_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| SUPMRGR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from SupraMarginal_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PRCUNSR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Prcuneus_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| HIPPR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Hippocampus_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| LINGUALL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Lingual_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| LINGUALR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Lingual_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGPSTR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Post_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTINFL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTINFR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Inf_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARISUPL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Sup_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| PARISUPR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Sup_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| INSULAL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Insula_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| INSULAR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Insula_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGANTL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Ant_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGANTR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Ant_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGMIDL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Mid_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| CINGMIDR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Mid_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPSUPL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal _Sup_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPSUPR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal _Sup_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPINFL01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| TMPINFR01_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Inf_R (Units: Normalized Counts) (Additional notes: Same as for HippL01) | BAIPETNMRC |
| FRTSUPL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Sup_L (Units: Normalized Counts) (Additional notes: (1). Included baseline FDG-PET scans after excluding scans with QA/acquisioon concerns, ANOVA  desig) | BAIPETNMRC |
| FRTMIDL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Mid_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGPSTL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Post_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGMIDL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Mid_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTSMEDL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Sup_Medial_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FUSFRML02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Fusiform_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPMIDL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Mid_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| OCCMIDL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Occipital_Mid_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPINFL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PRECUNL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Precuneus_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGANTL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Ant_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTMIDOR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Mid_Orb_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTMIDR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Mid_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTSUPR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Sup_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| ANGULR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Angular_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| ANGULL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Angular_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PARIINFR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Inf_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPMIDR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Mid_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| INSULAR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Insula_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPPOSR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Pole_Sup_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGANTR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Ant_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGMIDR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Mid_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PRECUNR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Precuneus_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| RECTUSR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Rectus_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| CINGPSTR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Cingulum_Post_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PARIINFL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| INSULAL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Insula_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTINFL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTINFR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Inf_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| OCCMIDR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Occipital_Mid_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTMIDOL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Mid_Orb_Right (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTSMEDR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Frontal_Sup_Medial_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FUSFMR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Fusiform_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| RECTUSL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Rectus_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPPOSL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Pole_Sup_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PARISUPL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Sup_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| PARISUPR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Parietal_Sup_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| SUPMRGL02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from SupraMarginal_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| SUPMRGR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from SupraMarginal_R (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| TMPINFR02_BAIPETNMRC_09_12_16 | Globally normalized CMRgl from Temporal_Inf_L (Units: Normalized Counts) (Additional notes: Same as for FrtSupL02) | BAIPETNMRC |
| FRTMIDL03_BAIPETNMRC_09_12_16 | Frontal_Mid_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/6 month FDG-PET scan pairs for AD patients after excluding scans with QA/acqu) | BAIPETNMRC |
| FRTMIDR03_BAIPETNMRC_09_12_16 | Frontal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTSUPL03_BAIPETNMRC_09_12_16 | Frontal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTSUPR03_BAIPETNMRC_09_12_16 | Frontal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTSMEDL03_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTSMEDR03_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPSUPL03_BAIPETNMRC_09_12_16 | Temporal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPSUPR03_BAIPETNMRC_09_12_16 | Temporal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPMIDL03_BAIPETNMRC_09_12_16 | Temporal_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPMIDR03_BAIPETNMRC_09_12_16 | Temporal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPINFL03_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| TMPINFR03_BAIPETNMRC_09_12_16 | Temporal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FUSFRML03_BAIPETNMRC_09_12_16 | Fusiform_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FUSFRMR03_BAIPETNMRC_09_12_16 | Fusiform_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| LINGUALL03_BAIPETNMRC_09_12_16 | Lingual_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| LINGUALR03_BAIPETNMRC_09_12_16 | Lingual_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARAHIPL03_BAIPETNMRC_09_12_16 | ParaHippocampal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARAHIPR03_BAIPETNMRC_09_12_16 | ParaHippocampal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARISUPL03_BAIPETNMRC_09_12_16 | Parietal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARISUPR03_BAIPETNMRC_09_12_16 | Parietal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARIINFL03_BAIPETNMRC_09_12_16 | Parietal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PARIINFR03_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PRECUNL03_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| PRECUNR03_BAIPETNMRC_09_12_16 | Precuneus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| CINGANT03_BAIPETNMRC_09_12_16 | Cingulum_Ant (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| CINGMID03_BAIPETNMRC_09_12_16 | Cingulum_Mid (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| CINGPST03_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| ANGULR03_BAIPETNMRC_09_12_16 | Angular_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCMIDL03_BAIPETNMRC_09_12_16 | Occipital_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCMIDR03_BAIPETNMRC_09_12_16 | Occipital_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCSUPL03_BAIPETNMRC_09_12_16 | Occipital_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCSUPR03_BAIPETNMRC_09_12_16 | Occipital_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCINFL03_BAIPETNMRC_09_12_16 | Occipital_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| OCCINFR03_BAIPETNMRC_09_12_16 | Occipital_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| THALAML03_BAIPETNMRC_09_12_16 | Thalamus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| THALAMR03_BAIPETNMRC_09_12_16 | Thalamus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTMEDL03_BAIPETNMRC_09_12_16 | Frontal_Medial_Left (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTMEDR03_BAIPETNMRC_09_12_16 | Frontal_Medial_Right (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| SUPMRGL03_BAIPETNMRC_09_12_16 | SupraMarginal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| SUPMRGR03_BAIPETNMRC_09_12_16 | SupraMarginal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL03) | BAIPETNMRC |
| FRTMIDL04_BAIPETNMRC_09_12_16 | Frontal_Mid_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/6 month FDG-PET scan pairs after excluding scans with QA/acquisition concerns) | BAIPETNMRC |
| FRTMIDR04_BAIPETNMRC_09_12_16 | Frontal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTSUPL04_BAIPETNMRC_09_12_16 | Frontal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTSUPR04_BAIPETNMRC_09_12_16 | Frontal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTSMEDL04_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTSMEDR04_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPSUPL04_BAIPETNMRC_09_12_16 | Temporal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPSUPR04_BAIPETNMRC_09_12_16 | Temporal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPMIDL04_BAIPETNMRC_09_12_16 | Temporal_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPMIDR04_BAIPETNMRC_09_12_16 | Temporal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPINFL04_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| TMPINFR04_BAIPETNMRC_09_12_16 | Temporal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FUSFRML04_BAIPETNMRC_09_12_16 | Fusiform_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FUSFRMR04_BAIPETNMRC_09_12_16 | Fusiform_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| LINGUALL04_BAIPETNMRC_09_12_16 | Lingual_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| LINGUALR04_BAIPETNMRC_09_12_16 | Lingual_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARAHIPL04_BAIPETNMRC_09_12_16 | ParaHippocampal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARAHIPR04_BAIPETNMRC_09_12_16 | ParaHippocampal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARISUPL04_BAIPETNMRC_09_12_16 | Parietal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARISUPR04_BAIPETNMRC_09_12_16 | Parietal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARIINFL04_BAIPETNMRC_09_12_16 | Parietal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PARIINFR04_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PRECUNL04_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| PRECUNR04_BAIPETNMRC_09_12_16 | Precuneus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| CINGANT04_BAIPETNMRC_09_12_16 | Cingulum_Ant (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| CINGMID04_BAIPETNMRC_09_12_16 | Cingulum_Mid (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| CINGPST04_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCMIDL04_BAIPETNMRC_09_12_16 | Occipital_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCMIDR04_BAIPETNMRC_09_12_16 | Occipital_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCSUPL04_BAIPETNMRC_09_12_16 | Occipital_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCSUPR04_BAIPETNMRC_09_12_16 | Occipital_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCINFL04_BAIPETNMRC_09_12_16 | Occipital_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| OCCINFR04_BAIPETNMRC_09_12_16 | Occipital_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| THALAML04_BAIPETNMRC_09_12_16 | Thalamus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| THALAMR04_BAIPETNMRC_09_12_16 | Thalamus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTMEDL04_BAIPETNMRC_09_12_16 | Frontal_Medial_Left (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTMEDR04_BAIPETNMRC_09_12_16 | Frontal_Medial_Right (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| SUPMRGL04_BAIPETNMRC_09_12_16 | SupraMarginal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| SUPMRGR04_BAIPETNMRC_09_12_16 | SupraMarginal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| ANGULL04_BAIPETNMRC_09_12_16 | Angular_L (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| ANGULR04_BAIPETNMRC_09_12_16 | Angular_R (Units: Normalized Counts) (Additional notes: same as FrtMidL04) | BAIPETNMRC |
| FRTMIDL05_BAIPETNMRC_09_12_16 | Frontal_Mid_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/6 month FDG-PET scan pairs for 101 MCI patients after excluding scans with QA) | BAIPETNMRC |
| FRTMIDR05_BAIPETNMRC_09_12_16 | Frontal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTSUPL05_BAIPETNMRC_09_12_16 | Frontal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTSUPR05_BAIPETNMRC_09_12_16 | Frontal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTSMEDL05_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTSMEDR05_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPSUPL05_BAIPETNMRC_09_12_16 | Temporal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPSUPR05_BAIPETNMRC_09_12_16 | Temporal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPMIDL05_BAIPETNMRC_09_12_16 | Temporal_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPMIDR05_BAIPETNMRC_09_12_16 | Temporal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPINFL05_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| TMPINFR05_BAIPETNMRC_09_12_16 | Temporal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FUSFRML05_BAIPETNMRC_09_12_16 | Fusiform_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FUSFRMR05_BAIPETNMRC_09_12_16 | Fusiform_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARAHIPL05_BAIPETNMRC_09_12_16 | ParaHippocampal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARAHIPR05_BAIPETNMRC_09_12_16 | ParaHippocampal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARISUPL05_BAIPETNMRC_09_12_16 | Parietal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARISUPR05_BAIPETNMRC_09_12_16 | Parietal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARIINFL05_BAIPETNMRC_09_12_16 | Parietal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PARIINFR05_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PRECUNL05_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| PRECUNR05_BAIPETNMRC_09_12_16 | Precuneus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CINGANT05_BAIPETNMRC_09_12_16 | Cingulum_Ant (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CINGMID05_BAIPETNMRC_09_12_16 | Cingulum_Mid (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CINGPST05_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCMIDL05_BAIPETNMRC_09_12_16 | Occipital_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCMIDR05_BAIPETNMRC_09_12_16 | Occipital_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCSUPL05_BAIPETNMRC_09_12_16 | Occipital_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCSUPR05_BAIPETNMRC_09_12_16 | Occipital_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCINFL05_BAIPETNMRC_09_12_16 | Occipital_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| OCCINFR05_BAIPETNMRC_09_12_16 | Occipital_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| THALAML05_BAIPETNMRC_09_12_16 | Thalamus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| THALAMR05_BAIPETNMRC_09_12_16 | Thalamus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTMEDL05_BAIPETNMRC_09_12_16 | Frontal_Medial_Left (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTMEDR05_BAIPETNMRC_09_12_16 | Frontal_Medial_Right (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| ANGULR05_BAIPETNMRC_09_12_16 | Angular_Right (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| ANGULL05_BAIPETNMRC_09_12_16 | Angular_Left (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| CALCARL05_BAIPETNMRC_09_12_16 | Calcarine_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CALCARR05_BAIPETNMRC_09_12_16 | Calcarine_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| LINGUALL05_BAIPETNMRC_09_12_16 | Lingual_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| LINGUALR05_BAIPETNMRC_09_12_16 | Lingual_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CEREB8L05_BAIPETNMRC_09_12_16 | Cerebelum_8_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CEREB8R05_BAIPETNMRC_09_12_16 | Cerebelum_8_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CERBCR2L05_BAIPETNMRC_09_12_16 | Cerebelum_Crus2_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| CERBCR2R05_BAIPETNMRC_09_12_16 | Cerebelum_Crus2_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| SUPMRGL05_BAIPETNMRC_09_12_16 | SupraMarginal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| SUPMRGR05_BAIPETNMRC_09_12_16 | SupraMarginal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL05) | BAIPETNMRC |
| FRTMIDL06_BAIPETNMRC_09_12_16 | Frontal_Mid_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/6 month FDG-PET scan pairs after excluding scans with QA/acquisition concerns) | BAIPETNMRC |
| FRTMIDR06_BAIPETNMRC_09_12_16 | Frontal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTSUPL06_BAIPETNMRC_09_12_16 | Frontal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTSUPR06_BAIPETNMRC_09_12_16 | Frontal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTSMEDL06_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTSMEDR06_BAIPETNMRC_09_12_16 | Frontal_Sup_Medial_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPSUPL06_BAIPETNMRC_09_12_16 | Temporal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPSUPR06_BAIPETNMRC_09_12_16 | Temporal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPMIDL06_BAIPETNMRC_09_12_16 | Temporal_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPMIDR06_BAIPETNMRC_09_12_16 | Temporal_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPINFL06_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| TMPINFR06_BAIPETNMRC_09_12_16 | Temporal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FUSFRML06_BAIPETNMRC_09_12_16 | Fusiform_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FUSFRMR06_BAIPETNMRC_09_12_16 | Fusiform_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| LINGUALL06_BAIPETNMRC_09_12_16 | Lingual_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| LINGUALR06_BAIPETNMRC_09_12_16 | Lingual_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARAHIPL06_BAIPETNMRC_09_12_16 | ParaHippocampal_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARAHIPR06_BAIPETNMRC_09_12_16 | ParaHippocampal_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARISUPL06_BAIPETNMRC_09_12_16 | Parietal_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARISUPR06_BAIPETNMRC_09_12_16 | Parietal_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARIINFL06_BAIPETNMRC_09_12_16 | Parietal_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PARIINFR06_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PRECUNL06_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| PRECUNR06_BAIPETNMRC_09_12_16 | Precuneus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| CINGANT06_BAIPETNMRC_09_12_16 | Cingulum_Ant (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| CINGMID06_BAIPETNMRC_09_12_16 | Cingulum_Mid (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| CINGPST06_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCMIDL06_BAIPETNMRC_09_12_16 | Occipital_Mid_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCMIDR06_BAIPETNMRC_09_12_16 | Occipital_Mid_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCSUPL06_BAIPETNMRC_09_12_16 | Occipital_Sup_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCSUPR06_BAIPETNMRC_09_12_16 | Occipital_Sup_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCINFL06_BAIPETNMRC_09_12_16 | Occipital_Inf_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| OCCINFR06_BAIPETNMRC_09_12_16 | Occipital_Inf_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| THALAML06_BAIPETNMRC_09_12_16 | Thalamus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| THALAMR06_BAIPETNMRC_09_12_16 | Thalamus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTMEDL06_BAIPETNMRC_09_12_16 | Frontal_Medial_Left (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| FRTMEDR06_BAIPETNMRC_09_12_16 | Frontal_Medial_Right (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| HIPPL06_BAIPETNMRC_09_12_16 | Hippocampus_L (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| HIPPR06_BAIPETNMRC_09_12_16 | Hippocampus_R (Units: Normalized Counts) (Additional notes: same as FrtMidL06) | BAIPETNMRC |
| INDGLBNDX_BAIPETNMRC_09_12_16 | Individualized Global Index (Units: Percentage) (Additional notes: (1). Included 298 baseline FDG-PET scans after excluding scans with QA/acquisioon concerns.  (2) eac) | BAIPETNMRC |
| INDTEPNDX_BAIPETNMRC_09_12_16 | Individualized Temporal index  (Units: Percentage) (Additional notes: (1). Included 298 baseline FDG-PET scans after excluding scans with QA/acquisioon concerns.  (2) eac) | BAIPETNMRC |
| PRECUNL07_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs for AD patients. Within group baseline vs. 12-mon) | BAIPETNMRC |
| CINGPST07_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as PrecunL07) | BAIPETNMRC |
| PARIINFR07_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as PrecunL07) | BAIPETNMRC |
| TMPMIDL07_BAIPETNMRC_09_12_16 | Temporal_Mid_L (Units: Normalized Counts) (Additional notes: same as PrecunL07) | BAIPETNMRC |
| CUNEUSL08_BAIPETNMRC_09_12_16 | Cuneus_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs, repeated ANOVA? design (factors such as age, gen) | BAIPETNMRC |
| TMPMIDR08_BAIPETNMRC_09_12_16 | Temporal_Mid_R (Units: Normalized Counts) (Additional notes: same asCuneusL08) | BAIPETNMRC |
| TMPINFL09_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs for MCI patients. Within group baseline vs. 12-mo) | BAIPETNMRC |
| CINGPST09_BAIPETNMRC_09_12_16 | Cingulum_Post (Units: Normalized Counts) (Additional notes: same as TmpInfL09) | BAIPETNMRC |
| PRECUNL09_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as TmpInfL09) | BAIPETNMRC |
| PARIINFR09_BAIPETNMRC_09_12_16 | Parietal_Inf_R (Units: Normalized Counts) (Additional notes: same as TmpInfL09) | BAIPETNMRC |
| TMPINFL10_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs, repeated ANOVA? design (factors such as age, gen) | BAIPETNMRC |
| PRECUNL10_BAIPETNMRC_09_12_16 | Precuneus_L (Units: Normalized Counts) (Additional notes: same as TmpInfL10) | BAIPETNMRC |
| TMPINFL11_BAIPETNMRC_09_12_16 | Temporal_Inf_L (Units: Normalized Counts) (Additional notes: (1). Included baseline/18 month FDG-PET scan pairs for MCI patients. Within group baseline vs. 18-mo) | BAIPETNMRC |
| OCCMIDL11_BAIPETNMRC_09_12_16 | Occipital_Mid_L (Units: Normalized Counts) (Additional notes: same as TmpInfL11) | BAIPETNMRC |
| CINGPST11_BAIPETNMRC_09_12_16 | Cingulum_Post_L (Units: Normalized Counts) (Additional notes: same as TmpInfL11) | BAIPETNMRC |
| CINGMID11_BAIPETNMRC_09_12_16 | Cingulum_Post_R/Cingulum_Mid_R (Units: Normalized Counts) (Additional notes: same as TmpInfL11) | BAIPETNMRC |
| TMPPOSR12_BAIPETNMRC_09_12_16 | Temporal_Pole_Sup_R (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs for AD patients. Within group baseline vs. 12-mon) | BAIPETNMRC |
| CINGPSTR12_BAIPETNMRC_09_12_16 | Cingulum_Post_R/Cingulum_Mid_R (Units: Normalized Counts) (Additional notes: (1). Included baseline/12 month FDG-PET scan pairs for AD patients. Within group baseline vs. 12-mon) | BAIPETNMRC |
| FROITRN001_BAIPETNMRC_09_12_16 | Training group, all subjects (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans, paired t-test (factors such as age, gender, apoe4) | BAIPETNMRC |
| FROITRN002_BAIPETNMRC_09_12_16 | Training group, exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans after excluding scans with QA/acquisition concerns) | BAIPETNMRC |
| FROITST001_BAIPETNMRC_09_12_16 | Testing group, all scans (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans, paired t-test (factors such as age, gender, apoe4) | BAIPETNMRC |
| FROITST002_BAIPETNMRC_09_12_16 | Testing group, exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans after excluding scans with QA/acquisition concerns) | BAIPETNMRC |
| FROIWHL001_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans, paired t-test (factors such as age, gender, apoe4) | BAIPETNMRC |
| FROIWHL002_BAIPETNMRC_09_12_16 | Exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1). Included baseline and month 12 FDG-PET scans after excluding scans with QA/acquisition concerns) | BAIPETNMRC |
| FRPMSK001_BAIPETNMRC_09_12_16 | Exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline, month 06 and month 12 FDG-PET scans for subjects identif) | BAIPETNMRC |
| FRPMSK002_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline, month 06 and month 12 FDG-PET scans for ALL subjects ide) | BAIPETNMRC |
| FRTMSK003_BAIPETNMRC_09_12_16 | Exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline, month 06 and month 12 FDG-PET scans for subjects identif) | BAIPETNMRC |
| FRTMSK004_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline, month 06 and month 12 FDG-PET scans for subjects identif) | BAIPETNMRC |
| FRTMSK005_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline and month 18 FDG-PET scans for ONLY MCI subjects identifi) | BAIPETNMRC |
| FRTMSK006_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline and month 24 FDG-PET scans for AD, MCI and NC subjects id) | BAIPETNMRC |
| FRTMSK007_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Same as fRtMsk005 but with data from additional subjects, analyses were performed using baseline) | BAIPETNMRC |
| FRTMSK008_BAIPETNMRC_09_12_16 | Exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1) As fRtMsk007 excluding HRRT and HiRez scan data, and  with data from additional subjects, analys) | BAIPETNMRC |
| FRTMSK009_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Same as fRtMsk006 but with data from additonal subjects, analyses were performed using baseline ) | BAIPETNMRC |
| FRTMSK010_BAIPETNMRC_09_12_16 | Exclude HRRT and BioGraph HiRez (Units: Normalized Counts) (Additional notes: (1) Same as fRtMsk009 but excluding subjects whose scans were frmo HRRT and hiRez, and also with dat) | BAIPETNMRC |
| FRTMSK011_BAIPETNMRC_09_12_16 | All subjects (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline and month 36 FDG-PET scans for ONLY MCI subjects identifi) | BAIPETNMRC |
| HCISUB1_BAIPETNMRC_09_12_16 | hypometabolic convergence index for 74 AD subjects (Units: unitless) (Additional notes: (1) Analyses were performed using baseline FDG-PET scans from 74 AD subjects.  (2) In this analysis ) | BAIPETNMRC |
| HCI99_BAIPETNMRC_09_12_16 | hypometabolic convergence index for normal controls, stable MCI, MCI converter and ADs (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available ADNI1 and ADNI-GO subjects and ALL available time point) | BAIPETNMRC |
| HCI_BAIPETNMRC_09_12_16 | hypometabolic convergence index for ADNI1/ADNI2/ADNIGO subjects (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available ADNI subjects and ALL available time points FDG-PET sca) | BAIPETNMRC |
| NL1HIPP_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months and 12 months to 24 months from H (Units: Normalized Counts) (Additional notes: (1) For SPM voxel-wise analysis of  58 AD patients: Hippocampal CMRgl shows no significant decline f) | BAIPETNMRC |
| NL1PTEMP_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months and 12 months to 24 months from t (Units: Normalized Counts) (Additional notes: (1) Similar as nl1Hipp, but for analysis of 58 AD patient in two other regions: parietotemporal and ) | BAIPETNMRC |
| NL1PSTCG_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months and 12 months to 24 months from t (Units: Normalized Counts) (Additional notes: same as nl1ptemp) | BAIPETNMRC |
| NL2PSTCG_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months and 12 months to 24 months from P (Units: Normalized Counts) (Additional notes: (1) The globally corrected CMRglu difference in the first year and the second year were measured for) | BAIPETNMRC |
| NL2PARI_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from 12 months to 24 months from the inferior parietal regio (Units: Normalized Counts) (Additional notes: (1) The globally corrected CMRglu difference in the second year was measured for the 129 MCI patient) | BAIPETNMRC |
| NL3FRONT_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months and 12 months to 24 months from s (Units: Normalized Counts) (Additional notes: (1) The globally corrected CMRglu difference in the first year and the second year were measured for) | BAIPETNMRC |
| DECLADFR_BAIPETNMRC_09_12_16 | difference of globally normalized CMRgl from Baseline to 12 months from the superior frontal region  (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline and 12 months FDG-PET scans from 74 AD subjects.? (2) For) | BAIPETNMRC |
| DECLADTMP_BAIPETNMRC_09_12_16 | CMRgl from Baseline from the inferior temporal region of 74 AD patients (Units: Normalized Counts) (Additional notes: (1) Analyses were performed using baseline FDG-PET scans from 74 AD subjects.? (2) For this analysis) | BAIPETNMRC |
| LONGHCI_BAIPETNMRC_09_12_16 | Extension of HCI to longitudinal data (Units: unitless) (Additional notes: Data is derived from brain, both hemispheres, gray and white matter only, from FDG PET scans) | BAIPETNMRC |
| BSLVBM_BAIPETNMRC_09_12_16 | VBManalysis of structural MRI data (Units: unitless) (Additional notes: Data is derived from brain, both hemispheres, gray matter volume from T1 MRI.) | BAIPETNMRC |
| ACI_BAIPETNMRC_09_12_16 | amyloid convergence index for AV-45 subjects (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available AV-45 scans for ADNI-GO subjects. (2) The AD group amyl) | BAIPETNMRC |
| MCSUVR_BAIPETNMRC_09_12_16 | mean cortical standard uptake value ratio (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available AV-45 scans for ADNI-GO subjects. (2) Mean Cortical SUV) | BAIPETNMRC |
| FNMPREC_BAIPETNMRC_09_12_16 | precuneus FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Mild Cognitive Impairme) | BAIPETNMRC |
| FNAPREC_BAIPETNMRC_09_12_16 | precuneus FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Alzheimers Disease (AD)) | BAIPETNMRC |
| FNAPC_BAIPETNMRC_09_12_16 | posterior cingulate FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Alzheimers Disease (AD)) | BAIPETNMRC |
| FEAPREC_BAIPETNMRC_09_12_16 | precuneus FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Alzheimers Disease (AD)) | BAIPETNMRC |
| FMAPREC_BAIPETNMRC_09_12_16 | precuneus FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Alzheimers Disease (AD)) | BAIPETNMRC |
| FMAPC_BAIPETNMRC_09_12_16 | posterior cingulate FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the FDG PET differences between Alzheimers Disease (AD)) | BAIPETNMRC |
| AVNEFRONT_BAIPETNMRC_09_12_16 | frontal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between early Mild Co) | BAIPETNMRC |
| AVNMFRONT_BAIPETNMRC_09_12_16 | frontal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between Mild Cognitiv) | BAIPETNMRC |
| AVNAFRONT_BAIPETNMRC_09_12_16 | frontal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between Alzheimers Di) | BAIPETNMRC |
| AVEMTEMP_BAIPETNMRC_09_12_16 | temporal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between early Mild Co) | BAIPETNMRC |
| AVEATEMP_BAIPETNMRC_09_12_16 | temporal AV-45 measure  (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between early Mild Co) | BAIPETNMRC |
| AVMAOCCIP_BAIPETNMRC_09_12_16 | occipital AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM5, we examined the AV-45 amyloid PET differences between Mild Cognitiv) | BAIPETNMRC |
| FEAPC2_BAIPETNMRC_09_12_16 | posterior cingulate FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between early Mild Cognitive Im) | BAIPETNMRC |
| FEMPC2_BAIPETNMRC_09_12_16 | posterior cingulate FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between early Mild Cognitive Im) | BAIPETNMRC |
| FMAPREC2_BAIPETNMRC_09_12_16 | precuneus FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between Mild Cognitive Impairme) | BAIPETNMRC |
| FNAPARI2_BAIPETNMRC_09_12_16 | parietal FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between healthy control (NL) su) | BAIPETNMRC |
| FNEHC2_BAIPETNMRC_09_12_16 | hippocampal FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between early Mild Cognitive Im) | BAIPETNMRC |
| FNMTEMP2_BAIPETNMRC_09_12_16 | temporal FDG measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the FDG PET differences between Mild Cognitive Impairme) | BAIPETNMRC |
| AVEATEMP2_BAIPETNMRC_09_12_16 | temporal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between early Mild Co) | BAIPETNMRC |
| AVEMTEMP2_BAIPETNMRC_09_12_16 | temporal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between early Mild Co) | BAIPETNMRC |
| AVMAFRNT2_BAIPETNMRC_09_12_16 | frontal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between Mild Cognitiv) | BAIPETNMRC |
| AVNATEMP2_BAIPETNMRC_09_12_16 | temporal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between healthy contr) | BAIPETNMRC |
| AVNEFRNT2_BAIPETNMRC_09_12_16 | frontal AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between healthy contr) | BAIPETNMRC |
| AVNMPREC2_BAIPETNMRC_09_12_16 | precuneus AV-45 measure (Units: unitless) (Additional notes: With a factorial design in SPM8, we examined the AV-45 amyloid PET differences between healthy contr) | BAIPETNMRC |
| MMPLS_BAIPETNMRC_09_12_16 | AVfdgPLS (Units: unitless) (Additional notes: using multi-modal partial least square (MMPLS) technique to anazlye data preprocessed by SPM8, we ex) | BAIPETNMRC |
| ICA_BAIPETNMRC_09_12_16 | AV_ICA (Units: unitless) (Additional notes: using multivariate technique  Independent Component (ICA) technique to anazlye data preprocessed by ) | BAIPETNMRC |
| PCA2_BAIPETNMRC_09_12_16 | AV_SSM (Units: unitless) (Additional notes: using multivariate technique  scaled subprofile modeling (SSM) based on principal component analysis) | BAIPETNMRC |
| PLSFDG01_BAIPETNMRC_09_12_16 | PLS for FDG PET (Units: unitless) (Additional notes: Using informed partial least square (PLS) technique to analyze data preprocessed by SPM8; we examine) | BAIPETNMRC |
| HCI001_BAIPETNMRC_09_12_16 | Hypometabolic Convergence Index (Units: unitless) (Additional notes: As a global index hypometabolic convergence index (HCI) measures how strongly the pattern of FDG-PET) | BAIPETNMRC |
| MCSUVRWM_BAIPETNMRC_09_12_16 | Mean Cortical SUVR Corpus Callosum and Centrum Semiovale Combined (Units: unitless) (Additional notes: see note for mcSUVRwm2 below. The procedure is the same but for 332 subjects we uploaded before ) | BAIPETNMRC |
| MCSUVRWM2_BAIPETNMRC_09_12_16 | Mean Cortical SUVR Corpus Callosum and Centrum Semiovale Combined (Units: unitless) (Additional notes: (1) Analyses were performed on baseline and followup  florbetapir scans for 593 subjects, primarily ) | BAIPETNMRC |
| HCI_2014_BAIPETNMRC_09_12_16 | Hypometabolic Convergence Index (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available ADNI subjects and ALL available time points FDG-PET sca) | BAIPETNMRC |
| SROI_BAIPETNMRC_09_12_16 | statistical region of interest (sROI) developed and validated for optimal longitudinal FDG-PET CMRgl (Units: unitless) (Additional notes: (1) Analyses were performed on ALL available ADNI subjects and ALL available time points FDG-PET sca) | BAIPETNMRC |
| MCSUVRWM3_BAIPETNMRC_09_12_16 | Mean Cortical SUVR with Corpus Callosum and Centrum Semiovale Combined as reference region (Units: unitless) (Additional notes: same as mcSUVRwm2 from BAIPETNMRC_07_08_2015, but with some minor pre-processing differences: scan a) | BAIPETNMRC |
| MCSUVRCERE_BAIPETNMRC_09_12_16 | Mean Cortical SUVR with Cerebellum as reference region (Units: unitless) (Additional notes: In addition to the SUVR computation using the cerebral white matter reference region, we also did th) | BAIPETNMRC |
| RID_UCBERKELEYAV45_10_17_16 | Participant roster ID (Type: T) (Length: 10) (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | UCBERKELEYAV45 |
| VISCODE_UCBERKELEYAV45_10_17_16 | Visit code (Type: T) (Length: 3) | UCBERKELEYAV45 |
| VISCODE2_UCBERKELEYAV45_10_17_16 | Translated visit code (Type: T) (Length: 3) (Additional notes: Months from baseline rounded to nearest 6 months) | UCBERKELEYAV45 |
| EXAMDATE_UCBERKELEYAV45_10_17_16 | Date of AV45 scan (Type: D) (Length: 7) | UCBERKELEYAV45 |
| CEREBELLUMGREYMATTER_UCBERKELEYAV45_10_17_16 | Reference region - florbetapir mean of cerebellar grey matter.  Regions defined by Freesurfer; see J (Type: N) (Decimal: 4) (Units: av45 uptake - reference region) | UCBERKELEYAV45 |
| WHOLECEREBELLUM_UCBERKELEYAV45_10_17_16 | Reference region - florbetapir mean of whole cerebellum.  Regions defined by Freesurfer; see Jagust  (Type: N) (Decimal: 4) (Units: av45 uptake - reference region) | UCBERKELEYAV45 |
| ERODED_SUBCORTICALWM_UCBERKELEYAV45_10_17_16 | Reference region - florbetapir mean of eroded subcortical white matter.  Regions defined by Freesurf (Type: N) (Decimal: 4) (Units: av45 uptake - reference region) | UCBERKELEYAV45 |
| COMPOSITE_REF_UCBERKELEYAV45_10_17_16 | Reference region - florbetapir mean of composite ref region (avg of whole cerebellum, pons/brainstem (Type: N) (Decimal: 4) (Units: av45 uptake - reference region) | UCBERKELEYAV45 |
| FRONTAL_UCBERKELEYAV45_10_17_16 | Weighted florbetapir mean in frontal regions.  Regions defined by Freesurfer; see Jagust lab PDF on  (Type: N) (Decimal: 4) (Units: av45 uptake in cortical grey matter) | UCBERKELEYAV45 |
| CINGULATE_UCBERKELEYAV45_10_17_16 | Weighted florbetapir mean in anterior/posterior cingulate regions.  Regions defined by Freesurfer; s (Type: N) (Decimal: 4) (Units: av45 uptake in cortical grey matter) | UCBERKELEYAV45 |
| PARIETAL_UCBERKELEYAV45_10_17_16 | Weighted florbetapir mean in lateral parietal regions.  Regions defined by Freesurfer; see Jagust la (Type: N) (Decimal: 4) (Units: av45 uptake in cortical grey matter) | UCBERKELEYAV45 |
| TEMPORAL_UCBERKELEYAV45_10_17_16 | Weighted florbetapir mean in lateral temporal regions.  Regions defined by Freesurfer; see Jagust la (Type: N) (Decimal: 4) (Units: av45 uptake in cortical grey matter) | UCBERKELEYAV45 |
| SUMMARYSUVR_WHOLECEREBNORM_UCBERKELEYAV45_10_17_16 | Summary florbetapir cortical SUVR normalized by whole cerebellum.  See Jagust lab PDF on LONI for de (Type: N) (Decimal: 4) (Units: av45 ratio (cortical grey matter/whole cerebellum)) | UCBERKELEYAV45 |
| SUMMARYSUVR_WHOLECEREBNORM_1.11CUTOFF_UCBERKELEYAV45_10_17_16 | Amyloid positivity determined by applying a cutoff value of 1.11 to the summary florbetapir cortical (Type: N) (Decimal: 0) (Units: binary) | UCBERKELEYAV45 |
| SUMMARYSUVR_COMPOSITE_REFNORM_UCBERKELEYAV45_10_17_16 | Summary florbetapir cortical SUVR normalized by composite ref region.  See Jagust lab PDF on LONI fo (Type: N) (Decimal: 4) (Units: av45 ratio (cortical grey matter/composite ref region)) | UCBERKELEYAV45 |
| SUMMARYSUVR_COMPOSITE_REFNORM_0.79CUTOFF_UCBERKELEYAV45_10_17_16 | Amyloid positivity determined by applying a cutoff value of 0.79 to the summary florbetapir cortical (Type: N) (Decimal: 0) (Units: binary) | UCBERKELEYAV45 |
| BRAINSTEM_UCBERKELEYAV45_10_17_16 | Reference region - florbetapir mean of brainstem.  Regions defined by Freesurfer; see Jagust lab PDF (Type: N) (Decimal: 4) (Units: av45 uptake - reference region) | UCBERKELEYAV45 |
| BRAINSTEM_SIZE_UCBERKELEYAV45_10_17_16 | brain-stem ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| VENTRICLE_3RD_UCBERKELEYAV45_10_17_16 | 3rd-ventricle (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| VENTRICLE_3RD_SIZE_UCBERKELEYAV45_10_17_16 | 3rd-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| VENTRICLE_4TH_UCBERKELEYAV45_10_17_16 | 4th-ventricle (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| VENTRICLE_4TH_SIZE_UCBERKELEYAV45_10_17_16 | 4th-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| VENTRICLE_5TH_UCBERKELEYAV45_10_17_16 | 5th-ventricle (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| VENTRICLE_5TH_SIZE_UCBERKELEYAV45_10_17_16 | 5th-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CC_ANTERIOR_UCBERKELEYAV45_10_17_16 | cc-anterior (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CC_ANTERIOR_SIZE_UCBERKELEYAV45_10_17_16 | cc-anterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CC_CENTRAL_UCBERKELEYAV45_10_17_16 | cc-central (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CC_CENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | cc-central ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CC_MID_ANTERIOR_UCBERKELEYAV45_10_17_16 | cc-mid-anterior (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CC_MID_ANTERIOR_SIZE_UCBERKELEYAV45_10_17_16 | cc-mid-anterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CC_MID_POSTERIOR_UCBERKELEYAV45_10_17_16 | cc-mid-posterior (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CC_MID_POSTERIOR_SIZE_UCBERKELEYAV45_10_17_16 | cc-mid-posterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CC_POSTERIOR_UCBERKELEYAV45_10_17_16 | cc-posterior (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CC_POSTERIOR_SIZE_UCBERKELEYAV45_10_17_16 | cc-posterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CSF_UCBERKELEYAV45_10_17_16 | csf (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CSF_SIZE_UCBERKELEYAV45_10_17_16 | csf ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_BANKSSTS_UCBERKELEYAV45_10_17_16 | ctx-lh-bankssts (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_BANKSSTS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-bankssts ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_CAUDALANTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-lh-caudalanteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_CAUDALANTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-caudalanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_CAUDALMIDDLEFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-lh-caudalmiddlefrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_CAUDALMIDDLEFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-caudalmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_CUNEUS_UCBERKELEYAV45_10_17_16 | ctx-lh-cuneus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_CUNEUS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-cuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_ENTORHINAL_UCBERKELEYAV45_10_17_16 | ctx-lh-entorhinal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_ENTORHINAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-entorhinal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_FRONTALPOLE_UCBERKELEYAV45_10_17_16 | ctx-lh-frontalpole (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_FRONTALPOLE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-frontalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_FUSIFORM_UCBERKELEYAV45_10_17_16 | ctx-lh-fusiform (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_FUSIFORM_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-fusiform ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_INFERIORPARIETAL_UCBERKELEYAV45_10_17_16 | ctx-lh-inferiorparietal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_INFERIORPARIETAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-inferiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_INFERIORTEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-lh-inferiortemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_INFERIORTEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-inferiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_INSULA_UCBERKELEYAV45_10_17_16 | ctx-lh-insula (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_INSULA_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-insula ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_ISTHMUSCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-lh-isthmuscingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_ISTHMUSCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-isthmuscingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_LATERALOCCIPITAL_UCBERKELEYAV45_10_17_16 | ctx-lh-lateraloccipital (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_LATERALOCCIPITAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-lateraloccipital ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_LATERALORBITOFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-lh-lateralorbitofrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_LATERALORBITOFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-lateralorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_LINGUAL_UCBERKELEYAV45_10_17_16 | ctx-lh-lingual (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_LINGUAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-lingual ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_MEDIALORBITOFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-lh-medialorbitofrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_MEDIALORBITOFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-medialorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_MIDDLETEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-lh-middletemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_MIDDLETEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-middletemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PARACENTRAL_UCBERKELEYAV45_10_17_16 | ctx-lh-paracentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PARACENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-paracentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PARAHIPPOCAMPAL_UCBERKELEYAV45_10_17_16 | ctx-lh-parahippocampal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PARAHIPPOCAMPAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-parahippocampal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PARSOPERCULARIS_UCBERKELEYAV45_10_17_16 | ctx-lh-parsopercularis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PARSOPERCULARIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-parsopercularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PARSORBITALIS_UCBERKELEYAV45_10_17_16 | ctx-lh-parsorbitalis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PARSORBITALIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-parsorbitalis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PARSTRIANGULARIS_UCBERKELEYAV45_10_17_16 | ctx-lh-parstriangularis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PARSTRIANGULARIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-parstriangularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PERICALCARINE_UCBERKELEYAV45_10_17_16 | ctx-lh-pericalcarine (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PERICALCARINE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-pericalcarine ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_POSTCENTRAL_UCBERKELEYAV45_10_17_16 | ctx-lh-postcentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_POSTCENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-postcentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_POSTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-lh-posteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_POSTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-posteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PRECENTRAL_UCBERKELEYAV45_10_17_16 | ctx-lh-precentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PRECENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-precentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_PRECUNEUS_UCBERKELEYAV45_10_17_16 | ctx-lh-precuneus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_PRECUNEUS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-precuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_ROSTRALANTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-lh-rostralanteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_ROSTRALANTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-rostralanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_ROSTRALMIDDLEFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-lh-rostralmiddlefrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_ROSTRALMIDDLEFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-rostralmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-lh-superiorfrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-superiorfrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORPARIETAL_UCBERKELEYAV45_10_17_16 | ctx-lh-superiorparietal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORPARIETAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-superiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORTEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-lh-superiortemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_SUPERIORTEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-superiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_SUPRAMARGINAL_UCBERKELEYAV45_10_17_16 | ctx-lh-supramarginal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_SUPRAMARGINAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-supramarginal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_TEMPORALPOLE_UCBERKELEYAV45_10_17_16 | ctx-lh-temporalpole (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_TEMPORALPOLE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-temporalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_TRANSVERSETEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-lh-transversetemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_TRANSVERSETEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-transversetemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_LH_UNKNOWN_UCBERKELEYAV45_10_17_16 | ctx-lh-unknown (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_LH_UNKNOWN_SIZE_UCBERKELEYAV45_10_17_16 | ctx-lh-unknown ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_BANKSSTS_UCBERKELEYAV45_10_17_16 | ctx-rh-bankssts (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_BANKSSTS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-bankssts ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_CAUDALANTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-rh-caudalanteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_CAUDALANTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-caudalanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_CAUDALMIDDLEFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-rh-caudalmiddlefrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_CAUDALMIDDLEFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-caudalmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_CUNEUS_UCBERKELEYAV45_10_17_16 | ctx-rh-cuneus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_CUNEUS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-cuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_ENTORHINAL_UCBERKELEYAV45_10_17_16 | ctx-rh-entorhinal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_ENTORHINAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-entorhinal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_FRONTALPOLE_UCBERKELEYAV45_10_17_16 | ctx-rh-frontalpole (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_FRONTALPOLE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-frontalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_FUSIFORM_UCBERKELEYAV45_10_17_16 | ctx-rh-fusiform (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_FUSIFORM_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-fusiform ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_INFERIORPARIETAL_UCBERKELEYAV45_10_17_16 | ctx-rh-inferiorparietal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_INFERIORPARIETAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-inferiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_INFERIORTEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-rh-inferiortemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_INFERIORTEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-inferiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_INSULA_UCBERKELEYAV45_10_17_16 | ctx-rh-insula (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_INSULA_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-insula ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_ISTHMUSCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-rh-isthmuscingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_ISTHMUSCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-isthmuscingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_LATERALOCCIPITAL_UCBERKELEYAV45_10_17_16 | ctx-rh-lateraloccipital (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_LATERALOCCIPITAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-lateraloccipital ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_LATERALORBITOFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-rh-lateralorbitofrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_LATERALORBITOFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-lateralorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_LINGUAL_UCBERKELEYAV45_10_17_16 | ctx-rh-lingual (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_LINGUAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-lingual ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_MEDIALORBITOFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-rh-medialorbitofrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_MEDIALORBITOFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-medialorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_MIDDLETEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-rh-middletemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_MIDDLETEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-middletemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PARACENTRAL_UCBERKELEYAV45_10_17_16 | ctx-rh-paracentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PARACENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-paracentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PARAHIPPOCAMPAL_UCBERKELEYAV45_10_17_16 | ctx-rh-parahippocampal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PARAHIPPOCAMPAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-parahippocampal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PARSOPERCULARIS_UCBERKELEYAV45_10_17_16 | ctx-rh-parsopercularis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PARSOPERCULARIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-parsopercularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PARSORBITALIS_UCBERKELEYAV45_10_17_16 | ctx-rh-parsorbitalis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PARSORBITALIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-parsorbitalis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PARSTRIANGULARIS_UCBERKELEYAV45_10_17_16 | ctx-rh-parstriangularis (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PARSTRIANGULARIS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-parstriangularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PERICALCARINE_UCBERKELEYAV45_10_17_16 | ctx-rh-pericalcarine (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PERICALCARINE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-pericalcarine ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_POSTCENTRAL_UCBERKELEYAV45_10_17_16 | ctx-rh-postcentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_POSTCENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-postcentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_POSTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-rh-posteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_POSTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-posteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PRECENTRAL_UCBERKELEYAV45_10_17_16 | ctx-rh-precentral (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PRECENTRAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-precentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_PRECUNEUS_UCBERKELEYAV45_10_17_16 | ctx-rh-precuneus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_PRECUNEUS_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-precuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_ROSTRALANTERIORCINGULATE_UCBERKELEYAV45_10_17_16 | ctx-rh-rostralanteriorcingulate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_ROSTRALANTERIORCINGULATE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-rostralanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_ROSTRALMIDDLEFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-rh-rostralmiddlefrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_ROSTRALMIDDLEFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-rostralmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORFRONTAL_UCBERKELEYAV45_10_17_16 | ctx-rh-superiorfrontal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORFRONTAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-superiorfrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORPARIETAL_UCBERKELEYAV45_10_17_16 | ctx-rh-superiorparietal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORPARIETAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-superiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORTEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-rh-superiortemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_SUPERIORTEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-superiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_SUPRAMARGINAL_UCBERKELEYAV45_10_17_16 | ctx-rh-supramarginal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_SUPRAMARGINAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-supramarginal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_TEMPORALPOLE_UCBERKELEYAV45_10_17_16 | ctx-rh-temporalpole (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_TEMPORALPOLE_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-temporalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_TRANSVERSETEMPORAL_UCBERKELEYAV45_10_17_16 | ctx-rh-transversetemporal (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_TRANSVERSETEMPORAL_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-transversetemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| CTX_RH_UNKNOWN_UCBERKELEYAV45_10_17_16 | ctx-rh-unknown (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| CTX_RH_UNKNOWN_SIZE_UCBERKELEYAV45_10_17_16 | ctx-rh-unknown ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_ACCUMBENS_AREA_UCBERKELEYAV45_10_17_16 | left-accumbens-area (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_ACCUMBENS_AREA_SIZE_UCBERKELEYAV45_10_17_16 | left-accumbens-area ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_AMYGDALA_UCBERKELEYAV45_10_17_16 | left-amygdala (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_AMYGDALA_SIZE_UCBERKELEYAV45_10_17_16 | left-amygdala ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_CAUDATE_UCBERKELEYAV45_10_17_16 | left-caudate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_CAUDATE_SIZE_UCBERKELEYAV45_10_17_16 | left-caudate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_CEREBELLUM_CORTEX_UCBERKELEYAV45_10_17_16 | left-cerebellum-cortex (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_CEREBELLUM_CORTEX_SIZE_UCBERKELEYAV45_10_17_16 | left-cerebellum-cortex ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_CEREBELLUM_WHITE_MATTER_UCBERKELEYAV45_10_17_16 | left-cerebellum-white-matter (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_CEREBELLUM_WHITE_MATTER_SIZE_UCBERKELEYAV45_10_17_16 | left-cerebellum-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_CEREBRAL_WHITE_MATTER_UCBERKELEYAV45_10_17_16 | left-cerebral-white-matter (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_CEREBRAL_WHITE_MATTER_SIZE_UCBERKELEYAV45_10_17_16 | left-cerebral-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_CHOROID_PLEXUS_UCBERKELEYAV45_10_17_16 | left-choroid-plexus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_CHOROID_PLEXUS_SIZE_UCBERKELEYAV45_10_17_16 | left-choroid-plexus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_HIPPOCAMPUS_UCBERKELEYAV45_10_17_16 | left-hippocampus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_HIPPOCAMPUS_SIZE_UCBERKELEYAV45_10_17_16 | left-hippocampus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_INF_LAT_VENT_UCBERKELEYAV45_10_17_16 | left-inf-lat-vent (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_INF_LAT_VENT_SIZE_UCBERKELEYAV45_10_17_16 | left-inf-lat-vent ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_LATERAL_VENTRICLE_UCBERKELEYAV45_10_17_16 | left-lateral-ventricle (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_LATERAL_VENTRICLE_SIZE_UCBERKELEYAV45_10_17_16 | left-lateral-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_PALLIDUM_UCBERKELEYAV45_10_17_16 | left-pallidum (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_PALLIDUM_SIZE_UCBERKELEYAV45_10_17_16 | left-pallidum ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_PUTAMEN_UCBERKELEYAV45_10_17_16 | left-putamen (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_PUTAMEN_SIZE_UCBERKELEYAV45_10_17_16 | left-putamen ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_THALAMUS_PROPER_UCBERKELEYAV45_10_17_16 | left-thalamus-proper (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_THALAMUS_PROPER_SIZE_UCBERKELEYAV45_10_17_16 | left-thalamus-proper ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_VENTRALDC_UCBERKELEYAV45_10_17_16 | left-ventraldc (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_VENTRALDC_SIZE_UCBERKELEYAV45_10_17_16 | left-ventraldc ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| LEFT_VESSEL_UCBERKELEYAV45_10_17_16 | left-vessel (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| LEFT_VESSEL_SIZE_UCBERKELEYAV45_10_17_16 | left-vessel ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| NON_WM_HYPOINTENSITIES_UCBERKELEYAV45_10_17_16 | non-wm-hypointensities (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| NON_WM_HYPOINTENSITIES_SIZE_UCBERKELEYAV45_10_17_16 | non-wm-hypointensities ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| OPTIC_CHIASM_UCBERKELEYAV45_10_17_16 | optic-chiasm (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| OPTIC_CHIASM_SIZE_UCBERKELEYAV45_10_17_16 | optic-chiasm ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_ACCUMBENS_AREA_UCBERKELEYAV45_10_17_16 | right-accumbens-area (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_ACCUMBENS_AREA_SIZE_UCBERKELEYAV45_10_17_16 | right-accumbens-area ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_AMYGDALA_UCBERKELEYAV45_10_17_16 | right-amygdala (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_AMYGDALA_SIZE_UCBERKELEYAV45_10_17_16 | right-amygdala ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_CAUDATE_UCBERKELEYAV45_10_17_16 | right-caudate (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_CAUDATE_SIZE_UCBERKELEYAV45_10_17_16 | right-caudate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_CEREBELLUM_CORTEX_UCBERKELEYAV45_10_17_16 | right-cerebellum-cortex (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_CEREBELLUM_CORTEX_SIZE_UCBERKELEYAV45_10_17_16 | right-cerebellum-cortex ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_CEREBELLUM_WHITE_MATTER_UCBERKELEYAV45_10_17_16 | right-cerebellum-white-matter (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_CEREBELLUM_WHITE_MATTER_SIZE_UCBERKELEYAV45_10_17_16 | right-cerebellum-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_CEREBRAL_WHITE_MATTER_UCBERKELEYAV45_10_17_16 | right-cerebral-white-matter (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_CEREBRAL_WHITE_MATTER_SIZE_UCBERKELEYAV45_10_17_16 | right-cerebral-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_CHOROID_PLEXUS_UCBERKELEYAV45_10_17_16 | right-choroid-plexus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_CHOROID_PLEXUS_SIZE_UCBERKELEYAV45_10_17_16 | right-choroid-plexus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_HIPPOCAMPUS_UCBERKELEYAV45_10_17_16 | right-hippocampus (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_HIPPOCAMPUS_SIZE_UCBERKELEYAV45_10_17_16 | right-hippocampus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_INF_LAT_VENT_UCBERKELEYAV45_10_17_16 | right-inf-lat-vent (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_INF_LAT_VENT_SIZE_UCBERKELEYAV45_10_17_16 | right-inf-lat-vent ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_LATERAL_VENTRICLE_UCBERKELEYAV45_10_17_16 | right-lateral-ventricle (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_LATERAL_VENTRICLE_SIZE_UCBERKELEYAV45_10_17_16 | right-lateral-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_PALLIDUM_UCBERKELEYAV45_10_17_16 | right-pallidum (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_PALLIDUM_SIZE_UCBERKELEYAV45_10_17_16 | right-pallidum ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_PUTAMEN_UCBERKELEYAV45_10_17_16 | right-putamen (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_PUTAMEN_SIZE_UCBERKELEYAV45_10_17_16 | right-putamen ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_THALAMUS_PROPER_UCBERKELEYAV45_10_17_16 | right-thalamus-proper (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_THALAMUS_PROPER_SIZE_UCBERKELEYAV45_10_17_16 | right-thalamus-proper ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_VENTRALDC_UCBERKELEYAV45_10_17_16 | right-ventraldc (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_VENTRALDC_SIZE_UCBERKELEYAV45_10_17_16 | right-ventraldc ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RIGHT_VESSEL_UCBERKELEYAV45_10_17_16 | right-vessel (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| RIGHT_VESSEL_SIZE_UCBERKELEYAV45_10_17_16 | right-vessel ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| WM_HYPOINTENSITIES_UCBERKELEYAV45_10_17_16 | wm-hypointensities (Type: N) (Decimal: 4) (Units: av45 uptake - subregion) | UCBERKELEYAV45 |
| WM_HYPOINTENSITIES_SIZE_UCBERKELEYAV45_10_17_16 | wm-hypointensities ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV45 |
| RID_UCBERKELEYAV1451_10_17_16 | Participant roster ID (Type: T) (Length: 10) (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | UCBERKELEYAV1451 |
| VISCODE_UCBERKELEYAV1451_10_17_16 | Visit code (Type: T) (Length: 3) | UCBERKELEYAV1451 |
| VISCODE2_UCBERKELEYAV1451_10_17_16 | Translated visit code (Type: T) (Length: 3) (Additional notes: Months from baseline rounded to nearest 6 months) | UCBERKELEYAV1451 |
| EXAMDATE_UCBERKELEYAV1451_10_17_16 | Examination Date (Type: D) (Length: 7) | UCBERKELEYAV1451 |
| CEREBELLUMGREYMATTER_UCBERKELEYAV1451_10_17_16 | Cerebellum grey matter (Type: N) (Decimal: 4) (Units: av1451 uptake - reference region) | UCBERKELEYAV1451 |
| CEREBELLUMGREYMATTER_SIZE_UCBERKELEYAV1451_10_17_16 | Cerebellum grey matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK1_UCBERKELEYAV1451_10_17_16 | Braak region 1 (Type: N) (Decimal: 4) (Units: av1451 uptake - reference region) | UCBERKELEYAV1451 |
| BRAAK1_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 1 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK2_UCBERKELEYAV1451_10_17_16 | Braak region 2 (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAAK2_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 2 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK3_UCBERKELEYAV1451_10_17_16 | Braak region 3 (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAAK3_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 3 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK4_UCBERKELEYAV1451_10_17_16 | Braak region 4 (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAAK4_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 4 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK5_UCBERKELEYAV1451_10_17_16 | Braak region 5 (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAAK5_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 5 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAAK6_UCBERKELEYAV1451_10_17_16 | Braak region 6 (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAAK6_SIZE_UCBERKELEYAV1451_10_17_16 | Braak region 6 ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| ERODED_SUBCORTICALWM_UCBERKELEYAV1451_10_17_16 | subcortical WM eroded away from cortex (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| ERODED_SUBCORTICALWM_SIZE_UCBERKELEYAV1451_10_17_16 | subcortical WM eroded away from cortex in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| BRAINSTEM_UCBERKELEYAV1451_10_17_16 | brain-stem (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| BRAINSTEM_SIZE_UCBERKELEYAV1451_10_17_16 | brain-stem ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| VENTRICLE_3RD_UCBERKELEYAV1451_10_17_16 | 3rd-ventricle (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| VENTRICLE_3RD_SIZE_UCBERKELEYAV1451_10_17_16 | 3rd-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| VENTRICLE_4TH_UCBERKELEYAV1451_10_17_16 | 4th-ventricle (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| VENTRICLE_4TH_SIZE_UCBERKELEYAV1451_10_17_16 | 4th-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| VENTRICLE_5TH_UCBERKELEYAV1451_10_17_16 | 5th-ventricle (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| VENTRICLE_5TH_SIZE_UCBERKELEYAV1451_10_17_16 | 5th-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CC_ANTERIOR_UCBERKELEYAV1451_10_17_16 | cc-anterior (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CC_ANTERIOR_SIZE_UCBERKELEYAV1451_10_17_16 | cc-anterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CC_CENTRAL_UCBERKELEYAV1451_10_17_16 | cc-central (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CC_CENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | cc-central ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CC_MID_ANTERIOR_UCBERKELEYAV1451_10_17_16 | cc-mid-anterior (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CC_MID_ANTERIOR_SIZE_UCBERKELEYAV1451_10_17_16 | cc-mid-anterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CC_MID_POSTERIOR_UCBERKELEYAV1451_10_17_16 | cc-mid-posterior (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CC_MID_POSTERIOR_SIZE_UCBERKELEYAV1451_10_17_16 | cc-mid-posterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CC_POSTERIOR_UCBERKELEYAV1451_10_17_16 | cc-posterior (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CC_POSTERIOR_SIZE_UCBERKELEYAV1451_10_17_16 | cc-posterior ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CSF_UCBERKELEYAV1451_10_17_16 | csf (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CSF_SIZE_UCBERKELEYAV1451_10_17_16 | csf ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_BANKSSTS_UCBERKELEYAV1451_10_17_16 | ctx-lh-bankssts (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_BANKSSTS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-bankssts ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_CAUDALANTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-lh-caudalanteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_CAUDALANTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-caudalanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_CAUDALMIDDLEFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-caudalmiddlefrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_CAUDALMIDDLEFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-caudalmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_CUNEUS_UCBERKELEYAV1451_10_17_16 | ctx-lh-cuneus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_CUNEUS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-cuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_ENTORHINAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-entorhinal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_ENTORHINAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-entorhinal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_FRONTALPOLE_UCBERKELEYAV1451_10_17_16 | ctx-lh-frontalpole (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_FRONTALPOLE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-frontalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_FUSIFORM_UCBERKELEYAV1451_10_17_16 | ctx-lh-fusiform (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_FUSIFORM_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-fusiform ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_INFERIORPARIETAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-inferiorparietal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_INFERIORPARIETAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-inferiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_INFERIORTEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-inferiortemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_INFERIORTEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-inferiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_INSULA_UCBERKELEYAV1451_10_17_16 | ctx-lh-insula (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_INSULA_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-insula ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_ISTHMUSCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-lh-isthmuscingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_ISTHMUSCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-isthmuscingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_LATERALOCCIPITAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-lateraloccipital (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_LATERALOCCIPITAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-lateraloccipital ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_LATERALORBITOFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-lateralorbitofrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_LATERALORBITOFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-lateralorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_LINGUAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-lingual (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_LINGUAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-lingual ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_MEDIALORBITOFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-medialorbitofrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_MEDIALORBITOFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-medialorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_MIDDLETEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-middletemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_MIDDLETEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-middletemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PARACENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-paracentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PARACENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-paracentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PARAHIPPOCAMPAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-parahippocampal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PARAHIPPOCAMPAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-parahippocampal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PARSOPERCULARIS_UCBERKELEYAV1451_10_17_16 | ctx-lh-parsopercularis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PARSOPERCULARIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-parsopercularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PARSORBITALIS_UCBERKELEYAV1451_10_17_16 | ctx-lh-parsorbitalis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PARSORBITALIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-parsorbitalis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PARSTRIANGULARIS_UCBERKELEYAV1451_10_17_16 | ctx-lh-parstriangularis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PARSTRIANGULARIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-parstriangularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PERICALCARINE_UCBERKELEYAV1451_10_17_16 | ctx-lh-pericalcarine (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PERICALCARINE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-pericalcarine ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_POSTCENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-postcentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_POSTCENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-postcentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_POSTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-lh-posteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_POSTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-posteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PRECENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-precentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PRECENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-precentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_PRECUNEUS_UCBERKELEYAV1451_10_17_16 | ctx-lh-precuneus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_PRECUNEUS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-precuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_ROSTRALANTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-lh-rostralanteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_ROSTRALANTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-rostralanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_ROSTRALMIDDLEFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-rostralmiddlefrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_ROSTRALMIDDLEFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-rostralmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiorfrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiorfrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORPARIETAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiorparietal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORPARIETAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORTEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiortemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_SUPERIORTEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-superiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_SUPRAMARGINAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-supramarginal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_SUPRAMARGINAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-supramarginal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_TEMPORALPOLE_UCBERKELEYAV1451_10_17_16 | ctx-lh-temporalpole (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_TEMPORALPOLE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-temporalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_TRANSVERSETEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-lh-transversetemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_TRANSVERSETEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-transversetemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_LH_UNKNOWN_UCBERKELEYAV1451_10_17_16 | ctx-lh-unknown (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_LH_UNKNOWN_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-lh-unknown ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_BANKSSTS_UCBERKELEYAV1451_10_17_16 | ctx-rh-bankssts (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_BANKSSTS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-bankssts ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_CAUDALANTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-rh-caudalanteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_CAUDALANTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-caudalanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_CAUDALMIDDLEFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-caudalmiddlefrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_CAUDALMIDDLEFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-caudalmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_CUNEUS_UCBERKELEYAV1451_10_17_16 | ctx-rh-cuneus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_CUNEUS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-cuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_ENTORHINAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-entorhinal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_ENTORHINAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-entorhinal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_FRONTALPOLE_UCBERKELEYAV1451_10_17_16 | ctx-rh-frontalpole (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_FRONTALPOLE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-frontalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_FUSIFORM_UCBERKELEYAV1451_10_17_16 | ctx-rh-fusiform (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_FUSIFORM_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-fusiform ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_INFERIORPARIETAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-inferiorparietal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_INFERIORPARIETAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-inferiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_INFERIORTEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-inferiortemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_INFERIORTEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-inferiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_INSULA_UCBERKELEYAV1451_10_17_16 | ctx-rh-insula (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_INSULA_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-insula ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_ISTHMUSCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-rh-isthmuscingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_ISTHMUSCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-isthmuscingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_LATERALOCCIPITAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-lateraloccipital (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_LATERALOCCIPITAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-lateraloccipital ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_LATERALORBITOFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-lateralorbitofrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_LATERALORBITOFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-lateralorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_LINGUAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-lingual (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_LINGUAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-lingual ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_MEDIALORBITOFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-medialorbitofrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_MEDIALORBITOFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-medialorbitofrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_MIDDLETEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-middletemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_MIDDLETEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-middletemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PARACENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-paracentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PARACENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-paracentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PARAHIPPOCAMPAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-parahippocampal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PARAHIPPOCAMPAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-parahippocampal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PARSOPERCULARIS_UCBERKELEYAV1451_10_17_16 | ctx-rh-parsopercularis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PARSOPERCULARIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-parsopercularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PARSORBITALIS_UCBERKELEYAV1451_10_17_16 | ctx-rh-parsorbitalis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PARSORBITALIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-parsorbitalis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PARSTRIANGULARIS_UCBERKELEYAV1451_10_17_16 | ctx-rh-parstriangularis (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PARSTRIANGULARIS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-parstriangularis ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PERICALCARINE_UCBERKELEYAV1451_10_17_16 | ctx-rh-pericalcarine (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PERICALCARINE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-pericalcarine ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_POSTCENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-postcentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_POSTCENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-postcentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_POSTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-rh-posteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_POSTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-posteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PRECENTRAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-precentral (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PRECENTRAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-precentral ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_PRECUNEUS_UCBERKELEYAV1451_10_17_16 | ctx-rh-precuneus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_PRECUNEUS_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-precuneus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_ROSTRALANTERIORCINGULATE_UCBERKELEYAV1451_10_17_16 | ctx-rh-rostralanteriorcingulate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_ROSTRALANTERIORCINGULATE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-rostralanteriorcingulate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_ROSTRALMIDDLEFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-rostralmiddlefrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_ROSTRALMIDDLEFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-rostralmiddlefrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORFRONTAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiorfrontal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORFRONTAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiorfrontal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORPARIETAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiorparietal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORPARIETAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiorparietal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORTEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiortemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_SUPERIORTEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-superiortemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_SUPRAMARGINAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-supramarginal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_SUPRAMARGINAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-supramarginal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_TEMPORALPOLE_UCBERKELEYAV1451_10_17_16 | ctx-rh-temporalpole (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_TEMPORALPOLE_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-temporalpole ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_TRANSVERSETEMPORAL_UCBERKELEYAV1451_10_17_16 | ctx-rh-transversetemporal (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_TRANSVERSETEMPORAL_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-transversetemporal ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| CTX_RH_UNKNOWN_UCBERKELEYAV1451_10_17_16 | ctx-rh-unknown (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| CTX_RH_UNKNOWN_SIZE_UCBERKELEYAV1451_10_17_16 | ctx-rh-unknown ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_ACCUMBENS_AREA_UCBERKELEYAV1451_10_17_16 | left-accumbens-area (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_ACCUMBENS_AREA_SIZE_UCBERKELEYAV1451_10_17_16 | left-accumbens-area ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_AMYGDALA_UCBERKELEYAV1451_10_17_16 | left-amygdala (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_AMYGDALA_SIZE_UCBERKELEYAV1451_10_17_16 | left-amygdala ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_CAUDATE_UCBERKELEYAV1451_10_17_16 | left-caudate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_CAUDATE_SIZE_UCBERKELEYAV1451_10_17_16 | left-caudate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_CEREBELLUM_CORTEX_UCBERKELEYAV1451_10_17_16 | left-cerebellum-cortex (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_CEREBELLUM_CORTEX_SIZE_UCBERKELEYAV1451_10_17_16 | left-cerebellum-cortex ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_CEREBELLUM_WHITE_MATTER_UCBERKELEYAV1451_10_17_16 | left-cerebellum-white-matter (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_CEREBELLUM_WHITE_MATTER_SIZE_UCBERKELEYAV1451_10_17_16 | left-cerebellum-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_CEREBRAL_WHITE_MATTER_UCBERKELEYAV1451_10_17_16 | left-cerebral-white-matter (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_CEREBRAL_WHITE_MATTER_SIZE_UCBERKELEYAV1451_10_17_16 | left-cerebral-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_CHOROID_PLEXUS_UCBERKELEYAV1451_10_17_16 | left-choroid-plexus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_CHOROID_PLEXUS_SIZE_UCBERKELEYAV1451_10_17_16 | left-choroid-plexus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_HIPPOCAMPUS_UCBERKELEYAV1451_10_17_16 | left-hippocampus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_HIPPOCAMPUS_SIZE_UCBERKELEYAV1451_10_17_16 | left-hippocampus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_INF_LAT_VENT_UCBERKELEYAV1451_10_17_16 | left-inf-lat-vent (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_INF_LAT_VENT_SIZE_UCBERKELEYAV1451_10_17_16 | left-inf-lat-vent ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_LATERAL_VENTRICLE_UCBERKELEYAV1451_10_17_16 | left-lateral-ventricle (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_LATERAL_VENTRICLE_SIZE_UCBERKELEYAV1451_10_17_16 | left-lateral-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_PALLIDUM_UCBERKELEYAV1451_10_17_16 | left-pallidum (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_PALLIDUM_SIZE_UCBERKELEYAV1451_10_17_16 | left-pallidum ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_PUTAMEN_UCBERKELEYAV1451_10_17_16 | left-putamen (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_PUTAMEN_SIZE_UCBERKELEYAV1451_10_17_16 | left-putamen ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_THALAMUS_PROPER_UCBERKELEYAV1451_10_17_16 | left-thalamus-proper (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_THALAMUS_PROPER_SIZE_UCBERKELEYAV1451_10_17_16 | left-thalamus-proper ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_VENTRALDC_UCBERKELEYAV1451_10_17_16 | left-ventraldc (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_VENTRALDC_SIZE_UCBERKELEYAV1451_10_17_16 | left-ventraldc ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| LEFT_VESSEL_UCBERKELEYAV1451_10_17_16 | left-vessel (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| LEFT_VESSEL_SIZE_UCBERKELEYAV1451_10_17_16 | left-vessel ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| NON_WM_HYPOINTENSITIES_UCBERKELEYAV1451_10_17_16 | non-wm-hypointensities (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| NON_WM_HYPOINTENSITIES_SIZE_UCBERKELEYAV1451_10_17_16 | non-wm-hypointensities ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| OPTIC_CHIASM_UCBERKELEYAV1451_10_17_16 | optic-chiasm (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| OPTIC_CHIASM_SIZE_UCBERKELEYAV1451_10_17_16 | optic-chiasm ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_ACCUMBENS_AREA_UCBERKELEYAV1451_10_17_16 | right-accumbens-area (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_ACCUMBENS_AREA_SIZE_UCBERKELEYAV1451_10_17_16 | right-accumbens-area ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_AMYGDALA_UCBERKELEYAV1451_10_17_16 | right-amygdala (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_AMYGDALA_SIZE_UCBERKELEYAV1451_10_17_16 | right-amygdala ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_CAUDATE_UCBERKELEYAV1451_10_17_16 | right-caudate (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_CAUDATE_SIZE_UCBERKELEYAV1451_10_17_16 | right-caudate ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_CEREBELLUM_CORTEX_UCBERKELEYAV1451_10_17_16 | right-cerebellum-cortex (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_CEREBELLUM_CORTEX_SIZE_UCBERKELEYAV1451_10_17_16 | right-cerebellum-cortex ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_CEREBELLUM_WHITE_MATTER_UCBERKELEYAV1451_10_17_16 | right-cerebellum-white-matter (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_CEREBELLUM_WHITE_MATTER_SIZE_UCBERKELEYAV1451_10_17_16 | right-cerebellum-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_CEREBRAL_WHITE_MATTER_UCBERKELEYAV1451_10_17_16 | right-cerebral-white-matter (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_CEREBRAL_WHITE_MATTER_SIZE_UCBERKELEYAV1451_10_17_16 | right-cerebral-white-matter ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_CHOROID_PLEXUS_UCBERKELEYAV1451_10_17_16 | right-choroid-plexus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_CHOROID_PLEXUS_SIZE_UCBERKELEYAV1451_10_17_16 | right-choroid-plexus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_HIPPOCAMPUS_UCBERKELEYAV1451_10_17_16 | right-hippocampus (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_HIPPOCAMPUS_SIZE_UCBERKELEYAV1451_10_17_16 | right-hippocampus ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_INF_LAT_VENT_UCBERKELEYAV1451_10_17_16 | right-inf-lat-vent (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_INF_LAT_VENT_SIZE_UCBERKELEYAV1451_10_17_16 | right-inf-lat-vent ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_LATERAL_VENTRICLE_UCBERKELEYAV1451_10_17_16 | right-lateral-ventricle (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_LATERAL_VENTRICLE_SIZE_UCBERKELEYAV1451_10_17_16 | right-lateral-ventricle ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_PALLIDUM_UCBERKELEYAV1451_10_17_16 | right-pallidum (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_PALLIDUM_SIZE_UCBERKELEYAV1451_10_17_16 | right-pallidum ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_PUTAMEN_UCBERKELEYAV1451_10_17_16 | right-putamen (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_PUTAMEN_SIZE_UCBERKELEYAV1451_10_17_16 | right-putamen ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_THALAMUS_PROPER_UCBERKELEYAV1451_10_17_16 | right-thalamus-proper (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_THALAMUS_PROPER_SIZE_UCBERKELEYAV1451_10_17_16 | right-thalamus-proper ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_VENTRALDC_UCBERKELEYAV1451_10_17_16 | right-ventraldc (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_VENTRALDC_SIZE_UCBERKELEYAV1451_10_17_16 | right-ventraldc ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RIGHT_VESSEL_UCBERKELEYAV1451_10_17_16 | right-vessel (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| RIGHT_VESSEL_SIZE_UCBERKELEYAV1451_10_17_16 | right-vessel ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| WM_HYPOINTENSITIES_UCBERKELEYAV1451_10_17_16 | wm-hypointensities (Type: N) (Decimal: 4) (Units: av1451 uptake - subregion) | UCBERKELEYAV1451 |
| WM_HYPOINTENSITIES_SIZE_UCBERKELEYAV1451_10_17_16 | wm-hypointensities ROI size in mm^3 (Type: N) (Decimal: 0) (Units: mm^3) | UCBERKELEYAV1451 |
| RID_DTIROI_04_30_14 | Participant roster ID (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | DTIROI |
| VISCODE_DTIROI_04_30_14 | Visit code | DTIROI |
| VISCODE2_DTIROI_04_30_14 | Translated visit code (Additional notes: Months from baseline rounded to nearest 6 months) | DTIROI |
| EXAMDATE_DTIROI_04_30_14 | Examination Date | DTIROI |
| VERSION_DTIROI_04_30_14 | Version | DTIROI |
| VISNAME_DTIROI_04_30_14 | Visit Code | DTIROI |
| VISITNO_DTIROI_04_30_14 | Visit | DTIROI |
| LONIUID_1_DTIROI_04_30_14 | LONI Image ID for FA | DTIROI |
| LONIUID_2_DTIROI_04_30_14 | LONI Image ID for MD | DTIROI |
| LONIUID_3_DTIROI_04_30_14 | LONI Image ID for RD | DTIROI |
| LONIUID_4_DTIROI_04_30_14 | LONI Image ID for AD | DTIROI |
| RUNDATE_DTIROI_04_30_14 | Date | DTIROI |
| STATUS_DTIROI_04_30_14 | Status | DTIROI |
| FA_CST_L_DTIROI_04_30_14 | Corticospinal tract left  (Units: FA) | DTIROI |
| FA_CST_R_DTIROI_04_30_14 | Corticospinal tract right  (Units: FA) | DTIROI |
| FA_ICP_L_DTIROI_04_30_14 | Inferior cerebellar peduncle left  (Units: FA) | DTIROI |
| FA_ICP_R_DTIROI_04_30_14 | Inferior cerebellar peduncle right  (Units: FA) | DTIROI |
| FA_ML_L_DTIROI_04_30_14 | Medial lemniscus left  (Units: FA) | DTIROI |
| FA_ML_R_DTIROI_04_30_14 | Medial lemniscus right  (Units: FA) | DTIROI |
| FA_SCP_L_DTIROI_04_30_14 | Superior cerebellar peduncle left  (Units: FA) | DTIROI |
| FA_SCP_R_DTIROI_04_30_14 | Superior cerebellar peduncle right  (Units: FA) | DTIROI |
| FA_CP_L_DTIROI_04_30_14 | Cerebral peduncle left  (Units: FA) | DTIROI |
| FA_CP_R_DTIROI_04_30_14 | Cerebral peduncle right  (Units: FA) | DTIROI |
| FA_ALIC_L_DTIROI_04_30_14 | Anterior limb of internal capsule left  (Units: FA) | DTIROI |
| FA_ALIC_R_DTIROI_04_30_14 | Anterior limb of internal capsule right  (Units: FA) | DTIROI |
| FA_PLIC_L_DTIROI_04_30_14 | Posterior limb of internal capsule left  (Units: FA) | DTIROI |
| FA_PLIC_R_DTIROI_04_30_14 | Posterior limb of internal capsule right  (Units: FA) | DTIROI |
| FA_PTR_L_DTIROI_04_30_14 | Posterior thalamic radiation left  (Units: FA) (Additional notes: includes optic radiation) | DTIROI |
| FA_PTR_R_DTIROI_04_30_14 | Posterior thalamic radiation right  (Units: FA) (Additional notes: includes optic radiation) | DTIROI |
| FA_ACR_L_DTIROI_04_30_14 | Anterior corona radiata left  (Units: FA) | DTIROI |
| FA_ACR_R_DTIROI_04_30_14 | Anterior corona radiata right  (Units: FA) | DTIROI |
| FA_SCR_L_DTIROI_04_30_14 | Superior corona radiata left  (Units: FA) | DTIROI |
| FA_SCR_R_DTIROI_04_30_14 | Superior corona radiata right  (Units: FA) | DTIROI |
| FA_PCR_L_DTIROI_04_30_14 | Posterior corona radiata left  (Units: FA) | DTIROI |
| FA_PCR_R_DTIROI_04_30_14 | Posterior corona radiata right  (Units: FA) | DTIROI |
| FA_CGC_L_DTIROI_04_30_14 | Cingulum left  (Units: FA) | DTIROI |
| FA_CGC_R_DTIROI_04_30_14 | Cingulum right  (Units: FA) | DTIROI |
| FA_CGH_L_DTIROI_04_30_14 | Cingulum (hippocampus) left  (Units: FA) | DTIROI |
| FA_CGH_R_DTIROI_04_30_14 | Cingulum (hippocampus) right  (Units: FA) | DTIROI |
| FA_FX_ST_L_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis left  (Units: FA) (Additional notes: can not be resolved with current resolution) | DTIROI |
| FA_FX_ST_R_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis right  (Units: FA) (Additional notes: can not be resolved with current resolution) | DTIROI |
| FA_SLF_L_DTIROI_04_30_14 | Superior longitudinal fasciculus left  (Units: FA) | DTIROI |
| FA_SLF_R_DTIROI_04_30_14 | Superior longitudinal fasciculus right  (Units: FA) | DTIROI |
| FA_SFO_L_DTIROI_04_30_14 | Superior fronto-occipital fasciculus left  (Units: FA) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| FA_SFO_R_DTIROI_04_30_14 | Superior fronto-occipital fasciculus right  (Units: FA) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| FA_IFO_L_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus left  (Units: FA) | DTIROI |
| FA_IFO_R_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus right  (Units: FA) | DTIROI |
| FA_SS_L_DTIROI_04_30_14 | Sagittal stratum left  (Units: FA) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| FA_SS_R_DTIROI_04_30_14 | Sagittal stratum right  (Units: FA) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| FA_EC_L_DTIROI_04_30_14 | External capsule left  (Units: FA) | DTIROI |
| FA_EC_R_DTIROI_04_30_14 | External capsule right  (Units: FA) | DTIROI |
| FA_UNC_L_DTIROI_04_30_14 | Uncinate fasciculus left  (Units: FA) | DTIROI |
| FA_UNC_R_DTIROI_04_30_14 | Uncinate fasciculus right  (Units: FA) | DTIROI |
| FA_FX_L_DTIROI_04_30_14 | Fornix  left  (Units: FA) (Additional notes: column and body of fornix) | DTIROI |
| FA_FX_R_DTIROI_04_30_14 | Fornix  right  (Units: FA) (Additional notes: column and body of fornix) | DTIROI |
| FA_GCC_L_DTIROI_04_30_14 | Genu of corpus callosum left  (Units: FA) | DTIROI |
| FA_GCC_R_DTIROI_04_30_14 | Genu of corpus callosum right  (Units: FA) | DTIROI |
| FA_BCC_L_DTIROI_04_30_14 | Body of corpus callosum  left  (Units: FA) | DTIROI |
| FA_BCC_R_DTIROI_04_30_14 | Body of corpus callosum  right  (Units: FA) | DTIROI |
| FA_SCC_L_DTIROI_04_30_14 | Splenium of corpus callosum left  (Units: FA) | DTIROI |
| FA_SCC_R_DTIROI_04_30_14 | Splenium of corpus callosum right  (Units: FA) | DTIROI |
| FA_RLIC_L_DTIROI_04_30_14 | Retrolenticular part of internal capsule left  (Units: FA) | DTIROI |
| FA_RLIC_R_DTIROI_04_30_14 | Retrolenticular part of internal capsule right  (Units: FA) | DTIROI |
| FA_TAP_L_DTIROI_04_30_14 | Tapatum left  (Units: FA) | DTIROI |
| FA_TAP_R_DTIROI_04_30_14 | Tapatum right  (Units: FA) | DTIROI |
| FA_SUMGCC_DTIROI_04_30_14 | Bilateral genu of the corpus callosum  (Units: FA) | DTIROI |
| FA_SUMBCC_DTIROI_04_30_14 | Bilateral body of  the corpus callosum  (Units: FA) | DTIROI |
| FA_SUMSCC_DTIROI_04_30_14 | Bilateral splenium of  the corpus callosum  (Units: FA) | DTIROI |
| FA_SUMCC_DTIROI_04_30_14 | Bilateral full corpus callosum  (Units: FA) | DTIROI |
| FA_SUMFX_DTIROI_04_30_14 | Bilateral fornix  (Units: FA) (Additional notes: column and body of fornix) | DTIROI |
| MD_CST_L_DTIROI_04_30_14 | Corticospinal tract left  (Units: MD) | DTIROI |
| MD_CST_R_DTIROI_04_30_14 | Corticospinal tract right  (Units: MD) | DTIROI |
| MD_ICP_L_DTIROI_04_30_14 | Inferior cerebellar peduncle left  (Units: MD) | DTIROI |
| MD_ICP_R_DTIROI_04_30_14 | Inferior cerebellar peduncle right  (Units: MD) | DTIROI |
| MD_ML_L_DTIROI_04_30_14 | Medial lemniscus left  (Units: MD) | DTIROI |
| MD_ML_R_DTIROI_04_30_14 | Medial lemniscus right  (Units: MD) | DTIROI |
| MD_SCP_L_DTIROI_04_30_14 | Superior cerebellar peduncle left  (Units: MD) | DTIROI |
| MD_SCP_R_DTIROI_04_30_14 | Superior cerebellar peduncle right  (Units: MD) | DTIROI |
| MD_CP_L_DTIROI_04_30_14 | Cerebral peduncle left  (Units: MD) | DTIROI |
| MD_CP_R_DTIROI_04_30_14 | Cerebral peduncle right  (Units: MD) | DTIROI |
| MD_ALIC_L_DTIROI_04_30_14 | Anterior limb of internal capsule left  (Units: MD) | DTIROI |
| MD_ALIC_R_DTIROI_04_30_14 | Anterior limb of internal capsule right  (Units: MD) | DTIROI |
| MD_PLIC_L_DTIROI_04_30_14 | Posterior limb of internal capsule left  (Units: MD) | DTIROI |
| MD_PLIC_R_DTIROI_04_30_14 | Posterior limb of internal capsule right  (Units: MD) | DTIROI |
| MD_PTR_L_DTIROI_04_30_14 | Posterior thalamic radiation left  (Units: MD) (Additional notes: includes optic radiation) | DTIROI |
| MD_PTR_R_DTIROI_04_30_14 | Posterior thalamic radiation right  (Units: MD) (Additional notes: includes optic radiation) | DTIROI |
| MD_ACR_L_DTIROI_04_30_14 | Anterior corona radiata left  (Units: MD) | DTIROI |
| MD_ACR_R_DTIROI_04_30_14 | Anterior corona radiata right  (Units: MD) | DTIROI |
| MD_SCR_L_DTIROI_04_30_14 | Superior corona radiata left  (Units: MD) | DTIROI |
| MD_SCR_R_DTIROI_04_30_14 | Superior corona radiata right  (Units: MD) | DTIROI |
| MD_PCR_L_DTIROI_04_30_14 | Posterior corona radiata left  (Units: MD) | DTIROI |
| MD_PCR_R_DTIROI_04_30_14 | Posterior corona radiata right  (Units: MD) | DTIROI |
| MD_CGC_L_DTIROI_04_30_14 | Cingulum left  (Units: MD) | DTIROI |
| MD_CGC_R_DTIROI_04_30_14 | Cingulum right  (Units: MD) | DTIROI |
| MD_CGH_L_DTIROI_04_30_14 | Cingulum (hippocampus) left  (Units: MD) | DTIROI |
| MD_CGH_R_DTIROI_04_30_14 | Cingulum (hippocampus) right  (Units: MD) | DTIROI |
| MD_FX_ST_L_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis left  (Units: MD) (Additional notes: can not be resolved with current resolution) | DTIROI |
| MD_FX_ST_R_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis right  (Units: MD) (Additional notes: can not be resolved with current resolution) | DTIROI |
| MD_SLF_L_DTIROI_04_30_14 | Superior longitudinal fasciculus left  (Units: MD) | DTIROI |
| MD_SLF_R_DTIROI_04_30_14 | Superior longitudinal fasciculus right  (Units: MD) | DTIROI |
| MD_SFO_L_DTIROI_04_30_14 | Superior fronto-occipital fasciculus left  (Units: MD) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| MD_SFO_R_DTIROI_04_30_14 | Superior fronto-occipital fasciculus right  (Units: MD) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| MD_IFO_L_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus left  (Units: MD) | DTIROI |
| MD_IFO_R_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus right  (Units: MD) | DTIROI |
| MD_SS_L_DTIROI_04_30_14 | Sagittal stratum left  (Units: MD) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| MD_SS_R_DTIROI_04_30_14 | Sagittal stratum right  (Units: MD) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| MD_EC_L_DTIROI_04_30_14 | External capsule left  (Units: MD) | DTIROI |
| MD_EC_R_DTIROI_04_30_14 | External capsule right  (Units: MD) | DTIROI |
| MD_UNC_L_DTIROI_04_30_14 | Uncinate fasciculus left  (Units: MD) | DTIROI |
| MD_UNC_R_DTIROI_04_30_14 | Uncinate fasciculus right  (Units: MD) | DTIROI |
| MD_FX_L_DTIROI_04_30_14 | Fornix  left  (Units: MD) (Additional notes: column and body of fornix) | DTIROI |
| MD_FX_R_DTIROI_04_30_14 | Fornix  right  (Units: MD) (Additional notes: column and body of fornix) | DTIROI |
| MD_GCC_L_DTIROI_04_30_14 | Genu of corpus callosum left  (Units: MD) | DTIROI |
| MD_GCC_R_DTIROI_04_30_14 | Genu of corpus callosum right  (Units: MD) | DTIROI |
| MD_BCC_L_DTIROI_04_30_14 | Body of corpus callosum  left  (Units: MD) | DTIROI |
| MD_BCC_R_DTIROI_04_30_14 | Body of corpus callosum  right  (Units: MD) | DTIROI |
| MD_SCC_L_DTIROI_04_30_14 | Splenium of corpus callosum left  (Units: MD) | DTIROI |
| MD_SCC_R_DTIROI_04_30_14 | Splenium of corpus callosum right  (Units: MD) | DTIROI |
| MD_RLIC_L_DTIROI_04_30_14 | Retrolenticular part of internal capsule left  (Units: MD) | DTIROI |
| MD_RLIC_R_DTIROI_04_30_14 | Retrolenticular part of internal capsule right  (Units: MD) | DTIROI |
| MD_TAP_L_DTIROI_04_30_14 | Tapatum left  (Units: MD) | DTIROI |
| MD_TAP_R_DTIROI_04_30_14 | Tapatum right  (Units: MD) | DTIROI |
| MD_SUMGCC_DTIROI_04_30_14 | Bilateral genu of the corpus callosum  (Units: MD) | DTIROI |
| MD_SUMBCC_DTIROI_04_30_14 | Bilateral body of  the corpus callosum  (Units: MD) | DTIROI |
| MD_SUMSCC_DTIROI_04_30_14 | Bilateral splenium of  the corpus callosum  (Units: MD) | DTIROI |
| MD_SUMCC_DTIROI_04_30_14 | Bilateral full corpus callosum  (Units: MD) | DTIROI |
| MD_SUMFX_DTIROI_04_30_14 | Bilateral fornix  (Units: MD) (Additional notes: column and body of fornix) | DTIROI |
| RD_CST_L_DTIROI_04_30_14 | Corticospinal tract left  (Units: RD) | DTIROI |
| RD_CST_R_DTIROI_04_30_14 | Corticospinal tract right  (Units: RD) | DTIROI |
| RD_ICP_L_DTIROI_04_30_14 | Inferior cerebellar peduncle left  (Units: RD) | DTIROI |
| RD_ICP_R_DTIROI_04_30_14 | Inferior cerebellar peduncle right  (Units: RD) | DTIROI |
| RD_ML_L_DTIROI_04_30_14 | Medial lemniscus left  (Units: RD) | DTIROI |
| RD_ML_R_DTIROI_04_30_14 | Medial lemniscus right  (Units: RD) | DTIROI |
| RD_SCP_L_DTIROI_04_30_14 | Superior cerebellar peduncle left  (Units: RD) | DTIROI |
| RD_SCP_R_DTIROI_04_30_14 | Superior cerebellar peduncle right  (Units: RD) | DTIROI |
| RD_CP_L_DTIROI_04_30_14 | Cerebral peduncle left  (Units: RD) | DTIROI |
| RD_CP_R_DTIROI_04_30_14 | Cerebral peduncle right  (Units: RD) | DTIROI |
| RD_ALIC_L_DTIROI_04_30_14 | Anterior limb of internal capsule left  (Units: RD) | DTIROI |
| RD_ALIC_R_DTIROI_04_30_14 | Anterior limb of internal capsule right  (Units: RD) | DTIROI |
| RD_PLIC_L_DTIROI_04_30_14 | Posterior limb of internal capsule left  (Units: RD) | DTIROI |
| RD_PLIC_R_DTIROI_04_30_14 | Posterior limb of internal capsule right  (Units: RD) | DTIROI |
| RD_PTR_L_DTIROI_04_30_14 | Posterior thalamic radiation left  (Units: RD) (Additional notes: includes optic radiation) | DTIROI |
| RD_PTR_R_DTIROI_04_30_14 | Posterior thalamic radiation right  (Units: RD) (Additional notes: includes optic radiation) | DTIROI |
| RD_ACR_L_DTIROI_04_30_14 | Anterior corona radiata left  (Units: RD) | DTIROI |
| RD_ACR_R_DTIROI_04_30_14 | Anterior corona radiata right  (Units: RD) | DTIROI |
| RD_SCR_L_DTIROI_04_30_14 | Superior corona radiata left  (Units: RD) | DTIROI |
| RD_SCR_R_DTIROI_04_30_14 | Superior corona radiata right  (Units: RD) | DTIROI |
| RD_PCR_L_DTIROI_04_30_14 | Posterior corona radiata left  (Units: RD) | DTIROI |
| RD_PCR_R_DTIROI_04_30_14 | Posterior corona radiata right  (Units: RD) | DTIROI |
| RD_CGC_L_DTIROI_04_30_14 | Cingulum left  (Units: RD) | DTIROI |
| RD_CGC_R_DTIROI_04_30_14 | Cingulum right  (Units: RD) | DTIROI |
| RD_CGH_L_DTIROI_04_30_14 | Cingulum (hippocampus) left  (Units: RD) | DTIROI |
| RD_CGH_R_DTIROI_04_30_14 | Cingulum (hippocampus) right  (Units: RD) | DTIROI |
| RD_FX_ST_L_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis left  (Units: RD) (Additional notes: can not be resolved with current resolution) | DTIROI |
| RD_FX_ST_R_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis right  (Units: RD) (Additional notes: can not be resolved with current resolution) | DTIROI |
| RD_SLF_L_DTIROI_04_30_14 | Superior longitudinal fasciculus left  (Units: RD) | DTIROI |
| RD_SLF_R_DTIROI_04_30_14 | Superior longitudinal fasciculus right  (Units: RD) | DTIROI |
| RD_SFO_L_DTIROI_04_30_14 | Superior fronto-occipital fasciculus left  (Units: RD) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| RD_SFO_R_DTIROI_04_30_14 | Superior fronto-occipital fasciculus right  (Units: RD) (Additional notes: could be a part of anterior internal capsule) | DTIROI |
| RD_IFO_L_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus left  (Units: RD) | DTIROI |
| RD_IFO_R_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus right  (Units: RD) | DTIROI |
| RD_SS_L_DTIROI_04_30_14 | Sagittal stratum left  (Units: RD) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| RD_SS_R_DTIROI_04_30_14 | Sagittal stratum right  (Units: RD) (Additional notes: includes inferior longitudinal fasciculus and inferior fronto-occipital fasciculus) | DTIROI |
| RD_EC_L_DTIROI_04_30_14 | External capsule left  (Units: RD) | DTIROI |
| RD_EC_R_DTIROI_04_30_14 | External capsule right  (Units: RD) | DTIROI |
| RD_UNC_L_DTIROI_04_30_14 | Uncinate fasciculus left  (Units: RD) | DTIROI |
| RD_UNC_R_DTIROI_04_30_14 | Uncinate fasciculus right  (Units: RD) | DTIROI |
| RD_FX_L_DTIROI_04_30_14 | Fornix  left  (Units: RD) (Additional notes: column and body of fornix) | DTIROI |
| RD_FX_R_DTIROI_04_30_14 | Fornix  right  (Units: RD) (Additional notes: column and body of fornix) | DTIROI |
| RD_GCC_L_DTIROI_04_30_14 | Genu of corpus callosum left  (Units: RD) | DTIROI |
| RD_GCC_R_DTIROI_04_30_14 | Genu of corpus callosum right  (Units: RD) | DTIROI |
| RD_BCC_L_DTIROI_04_30_14 | Body of corpus callosum  left  (Units: RD) | DTIROI |
| RD_BCC_R_DTIROI_04_30_14 | Body of corpus callosum  right  (Units: RD) | DTIROI |
| RD_SCC_L_DTIROI_04_30_14 | Splenium of corpus callosum left  (Units: RD) | DTIROI |
| RD_SCC_R_DTIROI_04_30_14 | Splenium of corpus callosum right  (Units: RD) | DTIROI |
| RD_RLIC_L_DTIROI_04_30_14 | Retrolenticular part of internal capsule left  (Units: RD) | DTIROI |
| RD_RLIC_R_DTIROI_04_30_14 | Retrolenticular part of internal capsule right  (Units: RD) | DTIROI |
| RD_TAP_L_DTIROI_04_30_14 | Tapatum left  (Units: RD) | DTIROI |
| RD_TAP_R_DTIROI_04_30_14 | Tapatum right  (Units: RD) | DTIROI |
| RD_SUMGCC_DTIROI_04_30_14 | Bilateral genu of the corpus callosum  (Units: RD) | DTIROI |
| RD_SUMBCC_DTIROI_04_30_14 | Bilateral body of  the corpus callosum  (Units: RD) | DTIROI |
| RD_SUMSCC_DTIROI_04_30_14 | Bilateral splenium of  the corpus callosum  (Units: RD) | DTIROI |
| RD_SUMCC_DTIROI_04_30_14 | Bilateral full corpus callosum  (Units: RD) | DTIROI |
| RD_SUMFX_DTIROI_04_30_14 | Bilateral fornix  (Units: RD) (Additional notes: column and body of fornix) | DTIROI |
| AD_CST_L_DTIROI_04_30_14 | Corticospinal tract left  (Units: AD) | DTIROI |
| AD_CST_R_DTIROI_04_30_14 | Corticospinal tract right  (Units: AD) | DTIROI |
| AD_ICP_L_DTIROI_04_30_14 | Inferior cerebellar peduncle left  (Units: AD) | DTIROI |
| AD_ICP_R_DTIROI_04_30_14 | Inferior cerebellar peduncle right  (Units: AD) | DTIROI |
| AD_ML_L_DTIROI_04_30_14 | Medial lemniscus left  (Units: AD) | DTIROI |
| AD_ML_R_DTIROI_04_30_14 | Medial lemniscus right  (Units: AD) | DTIROI |
| AD_SCP_L_DTIROI_04_30_14 | Superior cerebellar peduncle left  (Units: AD) | DTIROI |
| AD_SCP_R_DTIROI_04_30_14 | Superior cerebellar peduncle right  (Units: AD) | DTIROI |
| AD_CP_L_DTIROI_04_30_14 | Cerebral peduncle left  (Units: AD) | DTIROI |
| AD_CP_R_DTIROI_04_30_14 | Cerebral peduncle right  (Units: AD) | DTIROI |
| AD_ALIC_L_DTIROI_04_30_14 | Anterior limb of internal capsule left  (Units: AD) | DTIROI |
| AD_ALIC_R_DTIROI_04_30_14 | Anterior limb of internal capsule right  (Units: AD) | DTIROI |
| AD_PLIC_L_DTIROI_04_30_14 | Posterior limb of internal capsule left  (Units: AD) | DTIROI |
| AD_PLIC_R_DTIROI_04_30_14 | Posterior limb of internal capsule right  (Units: AD) | DTIROI |
| AD_PTR_L_DTIROI_04_30_14 | Posterior thalamic radiation left  (Units: AD) | DTIROI |
| AD_PTR_R_DTIROI_04_30_14 | Posterior thalamic radiation right  (Units: AD) | DTIROI |
| AD_ACR_L_DTIROI_04_30_14 | Anterior corona radiata left  (Units: AD) | DTIROI |
| AD_ACR_R_DTIROI_04_30_14 | Anterior corona radiata right  (Units: AD) | DTIROI |
| AD_SCR_L_DTIROI_04_30_14 | Superior corona radiata left  (Units: AD) | DTIROI |
| AD_SCR_R_DTIROI_04_30_14 | Superior corona radiata right  (Units: AD) | DTIROI |
| AD_PCR_L_DTIROI_04_30_14 | Posterior corona radiata left  (Units: AD) | DTIROI |
| AD_PCR_R_DTIROI_04_30_14 | Posterior corona radiata right  (Units: AD) | DTIROI |
| AD_CGC_L_DTIROI_04_30_14 | Cingulum left  (Units: AD) | DTIROI |
| AD_CGC_R_DTIROI_04_30_14 | Cingulum right  (Units: AD) | DTIROI |
| AD_CGH_L_DTIROI_04_30_14 | Cingulum (hippocampus) left  (Units: AD) | DTIROI |
| AD_CGH_R_DTIROI_04_30_14 | Cingulum (hippocampus) right  (Units: AD) | DTIROI |
| AD_FX_ST_L_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis left  (Units: AD) | DTIROI |
| AD_FX_ST_R_DTIROI_04_30_14 | Fornix (cres) / Stria terminalis right  (Units: AD) | DTIROI |
| AD_SLF_L_DTIROI_04_30_14 | Superior longitudinal fasciculus left  (Units: AD) | DTIROI |
| AD_SLF_R_DTIROI_04_30_14 | Superior longitudinal fasciculus right  (Units: AD) | DTIROI |
| AD_SFO_L_DTIROI_04_30_14 | Superior fronto-occipital fasciculus left  (Units: AD) | DTIROI |
| AD_SFO_R_DTIROI_04_30_14 | Superior fronto-occipital fasciculus right  (Units: AD) | DTIROI |
| AD_IFO_L_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus left  (Units: AD) | DTIROI |
| AD_IFO_R_DTIROI_04_30_14 | Inferior fronto-occipital fasciculus right  (Units: AD) | DTIROI |
| AD_SS_L_DTIROI_04_30_14 | Sagittal stratum left  (Units: AD) | DTIROI |
| AD_SS_R_DTIROI_04_30_14 | Sagittal stratum right  (Units: AD) | DTIROI |
| AD_EC_L_DTIROI_04_30_14 | External capsule left  (Units: AD) | DTIROI |
| AD_EC_R_DTIROI_04_30_14 | External capsule right  (Units: AD) | DTIROI |
| AD_UNC_L_DTIROI_04_30_14 | Uncinate fasciculus left  (Units: AD) | DTIROI |
| AD_UNC_R_DTIROI_04_30_14 | Uncinate fasciculus right  (Units: AD) | DTIROI |
| AD_FX_L_DTIROI_04_30_14 | Fornix  left  (Units: AD) | DTIROI |
| AD_FX_R_DTIROI_04_30_14 | Fornix  right  (Units: AD) | DTIROI |
| AD_GCC_L_DTIROI_04_30_14 | Genu of corpus callosum left  (Units: AD) | DTIROI |
| AD_GCC_R_DTIROI_04_30_14 | Genu of corpus callosum right  (Units: AD) | DTIROI |
| AD_BCC_L_DTIROI_04_30_14 | Body of corpus callosum  left  (Units: AD) | DTIROI |
| AD_BCC_R_DTIROI_04_30_14 | Body of corpus callosum  right  (Units: AD) | DTIROI |
| AD_SCC_L_DTIROI_04_30_14 | Splenium of corpus callosum left  (Units: AD) | DTIROI |
| AD_SCC_R_DTIROI_04_30_14 | Splenium of corpus callosum right  (Units: AD) | DTIROI |
| AD_RLIC_L_DTIROI_04_30_14 | Retrolenticular part of internal capsule left  (Units: AD) | DTIROI |
| AD_RLIC_R_DTIROI_04_30_14 | Retrolenticular part of internal capsule right  (Units: AD) | DTIROI |
| AD_TAP_L_DTIROI_04_30_14 | Tapatum left  (Units: AD) | DTIROI |
| AD_TAP_R_DTIROI_04_30_14 | Tapatum right  (Units: AD) | DTIROI |
| AD_SUMGCC_DTIROI_04_30_14 | Bilateral genu of the corpus callosum  (Units: AD) | DTIROI |
| AD_SUMBCC_DTIROI_04_30_14 | Bilateral body of  the corpus callosum  (Units: AD) | DTIROI |
| AD_SUMSCC_DTIROI_04_30_14 | Bilateral splenium of  the corpus callosum  (Units: AD) | DTIROI |
| AD_SUMCC_DTIROI_04_30_14 | Bilateral full corpus callosum  (Units: AD) | DTIROI |
| AD_SUMFX_DTIROI_04_30_14 | Bilateral fornix  (Units: AD) | DTIROI |
| RID_UPENNBIOMK9_04_19_17 | Participant roster ID (Additional notes: The 4 digit roster ID (RID) should be used to merge data) | UPENNBIOMK9 |
| VISCODE_UPENNBIOMK9_04_19_17 | Visit code | UPENNBIOMK9 |
| VISCODE2_UPENNBIOMK9_04_19_17 | Translated visit code (Additional notes: Months from baseline rounded to nearest 6 months) | UPENNBIOMK9 |
| EXAMDATE_UPENNBIOMK9_04_19_17 | Examination Date | UPENNBIOMK9 |
| PHASE_UPENNBIOMK9_04_19_17 | Study Phase | UPENNBIOMK9 |
| BATCH_UPENNBIOMK9_04_19_17 | Analytical batch of results | UPENNBIOMK9 |
| KIT_UPENNBIOMK9_04_19_17 | Reagents lot number | UPENNBIOMK9 |
| STDS_UPENNBIOMK9_04_19_17 | Calibrators and Quality Controls lot number | UPENNBIOMK9 |
| RUNDATE_UPENNBIOMK9_04_19_17 | Date of analytical run | UPENNBIOMK9 |
| ABETA_UPENNBIOMK9_04_19_17 | Result (Units: pg/ml) | UPENNBIOMK9 |
| TAU_UPENNBIOMK9_04_19_17 | Result (Units: pg/ml) | UPENNBIOMK9 |
| PTAU_UPENNBIOMK9_04_19_17 | Result (Units: pg/ml) | UPENNBIOMK9 |
| COMMENT_UPENNBIOMK9_04_19_17 | Comment (Additional notes: Extrapolated ABETA result) | UPENNBIOMK9 |


## Data sources

Please see the `TADPOLE_readme.txt` document that accompanies the TADPOLE data for more information on the following.

| Data source | Description |
| ADNIMERGE | Key ADNI tables merged into one table |
| UCSFFSL | Longitudinal FreeSurfer (FreeSurfer Version 4.4) |
| UCSFFSX | Cross-Sectional FreeSurfer (FreeSurfer Version 4.3) |
| BAIPETNMRC | Banner Alzheimer's Institute PET NMRC Summaries |
| UCBERKELEYAV45 | UC Berkeley - AV45 analysis |
| UCBERKELEYAV1451 | UC Berkeley - AV1451 analysis |
| DTIROI | DTI ROI summary measures |
| UPENNBIOMK9 | UPENN CSF Biomarkers Elecsys |
