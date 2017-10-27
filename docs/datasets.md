# Alzheimer's Disease Challenge Hackathon: Datasets

There are three "standard" data sets that have been compiled from raw ADNI data for TADPOLE.

## D1: Longitudinal training set
> Longitudinal measurements (i.e. over multiple visits) with associated outcomes (i.e. labelled training set) compiled from the entire ADNI history. Contains all individuals that have provided data in at least two visits (different dates) across ADNI1, ADNI GO and ADNI2. Data from sources such as MR & PET imaging, cognitive tests, CSF biomarkers and clinical assessment have been processed using standard ADNI data pipelines.

For more information including a data dictionary, please see [dataset_d1.md](dataset_d1.md)


## D2: Longitudinal test set
> Longitudunal measurements for rollover individuals who will be participating in ADNI3. This is the population for whom TADPOLE predictions should be made. Predicted outcomes will be evaluated against ADNI3 rollovers once this data is collected in 2018.

For more information including a data dictionary, please see [dataset_d2.md](dataset_d2.md)


## D3: Cross-sectional test set
> Strict subset of D2, containing a single (most recent) time point and a limit set of variables for the individuals in D2. Although we expect worse forecasts from this data set than those generated from D2, D3 represents the information typically available when selecting a cohort for a clinical trial and therefore has its own intrinsic scientific value.

For more information including a data dictionary, please see [dataset_d3.md](dataset_d3.md)
