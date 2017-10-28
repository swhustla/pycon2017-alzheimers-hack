# PyCon UK: Alzheimer's Disease Challenge Hackathon

**[Frank Kelly | Sunday 14:30 | Room L](http://2017.pyconuk.org/sessions/workshops/alzheimer-s-disease-challenge-hackathon/)**

> This workshop is a chance to take part in the [TADPOLE Grand Challenge](https://tadpole.grand-challenge.org/), to use data science to help identify people at risk of Alzheimer's Disease.
> 
> The TADPOLE Challenge was set up by volunteers at UCL with the aim of better understanding Alzheimer's disease using open source data. The dataset behind this is the [Alzheimer's Disease Neuro-imaging Archive](http://adni.loni.usc.edu/). In the competition, data scientists from around the world are competing for a prize fund of £30K to come up with the best model to predict outcomes of the disease in patients at risk using personal, genetic and medical imaging data.
> 
> If this sounds interesting to you, then please come along and meet us on Sunday afternoon. We're hosting a hackathon version of the competition, complete with leaderboard where you'll be able to get your hands on a lot of medical data and put your ML skills to the test. If you're not a data scientist, yet still fancy contributing Python skills towards this great cause then there will be tasks tailored to each teams' skillset. Come and join us on Sunday, let's make Alzheimer's Disease history!
> 
> If you would like to participate in the PyCon UK hackathon but not participate in the prediction challenge (for example, your Python skills are far beyond any mere data scientist) please see [Hackathon Bonus Tasks](bonus.md). Any teams working on bonus tasks are also eligible for prizes.



## Background

AD, and dementia in general, is a key challenge for 21st century healthcare. The statistics are sobering: 7% of people over 65 and 20% over 80 suffer from dementia of which AD is the most common cause. Dementia has higher health and social care costs than cancer, stroke and chronic heart disease combined. This costs are projected to be $1T in 2018 and $2T in 2030. A treatment slowing progression by 50% would reduce annual care costs by about 10%, i.e. $100B in 2018.

No current treatments provably cure or even slow AD. Of the hundreds of clinical trials into putative treatments (often running to billions of dollars) fewer than 1% have proceeded to the regulatory approval stage and none have managed to prove a disease-modifying effect. One key reason for these failures is difficulty in identifying patients at early stages of the disease where treatments are most likely to be effective.

TADPOLE challenges you to identify what data and algorithms best predict AD progression. This facilitates early identification of patients likely to be receptive to treatment, thus purifying cohorts for clinical trials, highlighting positive treatment effects, and facilitating translation of effective treatments to market.



## TADPOLE

Data science will play a key role in the endeavour to learn more about the causes of Alzheimer’s Disease, currently believed to be a combination of genetic and environmental factors. The goal of [The Alzheimer's Disease Prediction Of Longitudinal Evolution (TADPOLE) Challenge)](https://tadpole.grand-challenge.org/) is to identify which people within an age group at risk of AD (Alzheimer's Disease) will start to show symptoms in the short to medium term (1-5 years). It focuses on "rollover individuals" (patients coming from a previous phase) in the Alzheimer's Disease Neuroimaging Initiative (ADNI) study. The challenge is to use historical measurements from these individuals to forecast future measurements. The following scientific questions motivate the challenge:

- How predictable is progression to Alzheimer’s Disease (AD) in at-risk individuals?
- Which data, processing pipelines, and predictive models best predict future AD progression?
- Can we use such methods to improve cohort selection for clinical trials?

The TADPOLE datasets contain a list of individuals at an age that puts them at risk of AD, with associated measurements to inform forecasts (from imaging, psychology, demographics, genetics, etc.). Each individual has agreed to a follow-on assessment.

Your challenge is to predict future measurements from these individuals and submit your predictions before the submission deadline of 15th November 2017. Once future measurements are available, TADPOLE will evaluate each forecast against them, collate and compare results, publish the results, award prizes and, ultimately, write up a scientific paper co-authored with active participants. The competition is open to anyone: from statisticians to neurologists; from industry or academic research; from professor to high-school student.

To find out more about TADPOLE and current approaches to predicting AD, please see the [TADPOLE website](https://tadpole.grand-challenge.org/background/).

![TADPOLE dataset overview](https://tadpole.grand-challenge.org/site/TADPOLE/serve/public_html/images/Figure_TrainForecast_new.png/)



## Outcome Variables

The essence of TADPOLE is very simple. We provide a list of individuals previously recruited to the Alzheimer's Disease Neuroimaging Initiative (ADNI). These individuals have all provided data within earlier ADNI studies and have agreed to provide follow-up data in [ADNI 3](http://adni3.org/), which is just starting. ADNI refers to these individuals as "rollovers"; we will use the same term here. You are asked to forecast three features of each rollover individual at the time of their future data provision. Each feature is a common or likely outcome measure for clinical trials:

#### 1. Clinical status

- `CN` - Cognitively normal;
- `MCI` - mild cognitive impairment; or
- `AD` - probable Alzheimer's Disease
- At any point in time, this is one of CN (cognitively normal), MCI (mild cognitive impairment) or AD (probable Alzheimer's Disease).
- Provide relative likelihood of each option for each individual. Methods/algorithms that don't produce probabilistic estimates can still participate by setting binary probabilites (zero or one). N.B. relative likelihoods != probabilities.
- _Example: relative likelihoods of 1, 2, and 3 for a particular individual in a particular future month mean the participant believes the probabilities pCN, pMCI, and pAD are 1/6, 1/3, and 1/2 for CN, MCI, and AD, respectively, at that future time point. Negative likelihoods will be set to zero._

#### 2. ADAS-Cog13 score

- The ADAS-Cog is frequently used as a primary outcome measure in clinical trials, e.g. [Doody et al., NEJM 2014](http://doi.org/10.1056/NEJMoa1312889); [Salloway et al., NEJM 2014](http://doi.org/10.1056/NEJMoa1304839).
- Continuous variable; provide a best-guess value as well as a 50% confidence interval for each individual.
- The intervals indicate the participant's confidence in the prediction. Participants should choose the intervals aiming for a coverage probability of 0.5, i.e. 50% of the best guesses should lie within the corresponding confidence interval.
- _Example: ADAS13 forecast for individual A is 25 with 50% CI of [21, 26]; ADAS13 forecast for individual B is 40 with 50% CI of [25, 50]. There is thus more confidence in the forecast for individual A (CI size 5) than for individual B (CI size 25)._

#### 3. Ventricles volume, divided by intracranial volume

- As estimated via the [standard ADNI image processing pipeline](http://adni.loni.usc.edu/methods/mri-analysis/mri-pre-processing/), which uses the [FreeSurfer](http://freesurfer.net/) software.
- Same as ADAS13 (continuous variable, provide best-guess prediction plus 50% CI).

Since we do not know the exact time of future data acquisitions for any individual, **participants must make month-by-month forecasts** for each feature of each individual. Evaluation will use forecasts at the months that correspond to data acquisition.

The table below summarises the format of the forecasts using the above examples:

![TADPOLE sample forecasts](https://tadpole.grand-challenge.org/site/TADPOLE/serve/public_html/images/sampleforecast_v1.png/)



## Data Sets

The ADNI study has [three phases](http://adni.loni.usc.edu/study-design/): ADNI1, ADNI GO and ADNI2. New participants were recruited across North America during each phase of the study and agreed to complete a variety of imaging and clinical assessments. Participants are followed and reassessed over time to track the pathology of the disease as it progresses. [ADNI3 launched in September 2016](https://fnih.org/what-we-do/current-research-programs/adni3) and will run until 2022, aiming to recruit 1,200 volunteers as well as re-evaluate 800 previous ADNI participants in this time.

There are three "standard" data sets that have been compiled from raw ADNI data for TADPOLE. From these three ADNI datasets (see the [ADNI website for more information on the standard D1, D2, D3 ADNI datasets](https://tadpole.grand-challenge.org/data/)), the following two datasets have been compiled for the PyCon UK 2017 Alzheimer's Hackathon:

**LB1_LB2: Longitudinal training set**
Longitudinal measurements (i.e. over multiple visits) with associated outcomes (i.e. labelled training set) compiled from the entire ADNI history. Contains all individuals that have provided data in at least two visits (different dates) across ADNI1, ADNI GO and ADNI2 **up until May 2010**. Data from sources such as MR & PET imaging, cognitive tests, CSF biomarkers and clinical assessment have been processed using standard ADNI data pipelines.

Individuals flagged under the `LB2` column are rollover individuals who will be participating in ADNI3. This is the population for whom TADPOLE predictions should be made. For the PyCon UK hackathon, predicted outcomes will be evaluated against a held-out test set (i.e. recent visits from LB2 rollover patients). For the wider TADPOLE Challenge, predicted outcomes will be evaluated against ADNI3 rollovers once this data is collected in 2018.

**LB4: Longitudinal held-out test set**
Longitudinal measurements for visits for LB2 patients **from May 2010 onwards**.

**Other data sets**
Many other open data sets are available that might serve as useful additional training data should participants wish to look at it. For example:

- [The Global Alzheimer’s Association Interactive Network (GAAIN)](http://www.gaain.org/)
- [Australian Imaging, Biomarker & Lifestyle (AIBL) Flagship Study of Ageing](https://aibl.csiro.au/)
- [The collection of data sets in the neuGRID for you project](https://neugrid4you.eu/datasets)
- [Longitudinal data in the Minimal Interval Resonance Imaging in Alzheimer's Disease (MIRIAD) data set](http://www.ucl.ac.uk/drc/research/methods/miriad-scan-database)



## TADPOLE Submission Types & Prize Categories

> N.B. These conditions and prizes are only relevant for TADPOLE entries, not for the PyCon UK Hackathon. **PLEASE SEE THE [TADPOLE PYCON PAGE](https://tadpole.grand-challenge.org/pyconuk/) FOR DETAILS ON EVALUATION METRICS FOR THE PYCON HACKATHON. YOU WILL NEED TO [REGISTER WITH TADPOLE](https://tadpole.grand-challenge.org/accounts/signin/?next=/) IN ORDER TO SUBMIT YOUR ENTRY FOR THE PYCON HACKATHON.**

There are two ways to enter the TADPOLE Grand Challenge: a [simple entry](https://tadpole.grand-challenge.org/site/tadpole/serve/public_html/TADPOLE_Simple_Submission_TeamName.xlsx) or a [full entry](https://tadpole.grand-challenge.org/site/tadpole/serve/public_html/TADPOLE_Simple_Submission_TeamName.xlsx).

**Simple entry:** Submit a month-by-month forecast on at least one of the outcome variables (clinical status, ADAS13 or ventrical volume), using any training data or prediction sets.

**Full entry:** Submit a month-by-month forecast of all three outcome variables, optionally using any "custom" (i.e. constructed by the participant) training or prediction data sets. Full entries should provide two sets of forecasts using the standard TADPOLE data sets only (i.e. D1 for training, and a separate forecast for each of the D2 and D3 prediction sets), and optionally an additional forecast only if using custom datasets.

#### Prizes
**1. £5K prize for best forecast of future clinical status.** The performance metric for evaluating predicted likelihoods of each clinical status category (CN/MCI/AD) will be the [multi-class area under the receiver-operating characteristic curve (mAUC)](https://tadpole.grand-challenge.org/performance_metrics/).

**2. £5K prize for best forecast of future ADAS13 score.** The performance metric for evaluating ADAS13 predictions will be [mean absolute error (MAE)](https://tadpole.grand-challenge.org/performance_metrics/).

**3. £5K prize for best forecast of future ventricle volume.** The performance metric for evaluating ventrical ICV predictions will be [mean absolute error (MAE)](https://tadpole.grand-challenge.org/performance_metrics/).

**4. £5K prize for overall best predictive performance.** Each team will be ranked in each of the above three categories. The team with the lowest sum of ranks will be the overall winner of TADPOLE. In the event of a tie, we will use mAUC on clinical status (i.e. prize 1) to decide the winner.

**5. £5K prize for the best forecast from a university student team.** Same criteria as prize 1.

**6. £5K prize for the best forecast from a high-school team.** Same criteria as prize 1.

For more information on submitting your entry, as well as how to provide details on your methods, please visit https://tadpole.grand-challenge.org/details/#Methods
