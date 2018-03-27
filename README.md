# Salvatore-200Longitudinal
This is a public dataset to be used as a benchmark in the field of automatic classification of Alzheimer's Disease.

This repository does not contain any data from patients itself. Data are taken from the <a href="http://adni.loni.usc.edu/" target="_blank">Alzheimer's Disease Neuroimaging Initiative (ADNI) public database</a>, from where they can be downloaded after registration. 

This repository actually provides:
  1. IDs of patients (corresponding to the Subject IDs in the ADNI database)
  2. MRI IDs (corresponding to the Image Data IDs in the ADNI database)
  3. to be updated -> cross-validation indexes for the AD+pMCI vs sMCI+CN binary classification task

Using this information, data of patients can be downloaded from the ADNI platform and used for classification purposes, thus obtaining results that can be easily compared to previously published studies.

This dataset consists of 200 patients, equally divided into 50 AD, 50 progressive MCI (pMCI, or converter MCI), 50 stable MCI (sMCI, or not-converter MCI), 50 Cognitively Normal (CN) subjects.

Subjects were followed up for 4 different time points, namely 24 months before stable diagnosis, 18 months before stable diagnosis, 12 months before stable diagnosis, and the stable-diagnosis time point (as a benchmark for the performance of classification).

It must be underlined that the 4 time points reported above are the common ones among all the subjects in the database. However, subjects were followed up for longer periods (up to 10 years), when possible. The subjects included in this dataset were the ones for which the diagnosis at the stable-diagnosis time point was confirmed during the entire follow-up period. Because of this, the diagnosis of these subjects is much more reliable than the one of the subjects in the [Salvatore-509](https://github.com/christiansalvatore/Salvatore-509) dataset, for which such a long follow up was not available.

### Previous literature
To be updated.

### State of the art
On this [page](https://christiansalvatore.github.io/2016-10-20/is-this-alzheimer/#Salvatore-200Longitudinal), up-to-date classification performance on this dataset are reported. Results are given in terms of accuracy or balanced accuracy of classification. Sensitivity, specificity and AUC are also reported (when provided).

### Citing
(to be updated)
>Salvatore, C. et al. (2015). Magnetic resonance imaging biomarkers for the early diagnosis of Alzheimer's disease: a machine learning approach. Frontiers in Neuroscience, 9. doi: 10.3389/fnins.2015.00307.

### ADNI policy
ADNI data cannot be publicly shared by private users. It was not possible to directly upload data in this repository. However, feel free to <a href="mailto:christian.salvatore@ibfm.cnr.it">contact me</a> if you need more information about how to access data or about data used in the original paper by Salvatore et al.

Remember to follow the [ADNI data sharing and publication policy](http://adni.loni.usc.edu/wp-content/uploads/how_to_apply/ADNI_DSP_Policy.pdf), if you are going to publish a work in which data from the ADNI database were used.
