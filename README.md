# QC_literature
Compiling published manuscripts for Automated Quality Control project


### (2018 Kustner) : [**A machine-learning framework for automatic reference-free quality assessment in MRI**](https://www.sciencedirect.com/science/article/pii/S0730725X18302893#bbb0145), Magnetic Resonance Imaging

* Automatic reference-free quality assessment of medical images
* Prediction of human observer scores based on underlying diagnostic question
* Reduced labeling effort by active learning
* Investigation on suitable features and classifiers (**SVM, DNN**)
* **Accuracy of 93.7%** for estimating quality classes on a 5-point Likert scale

### (2017 Esteban) : [**MRIQC: Advancing the automatic prediction of image quality in MRI from unseen sites**](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0184661), PLOS ONE

Introduced the MRI Quality Control tool (MRIQC), a tool for extracting quality measures and fitting a binary (accept/exclude) classifier. We perform model selection evaluating different normalization and feature exclusion approaches aimed at maximizing across-site generalization and estimate an accuracy of **76%±13% on new sites**, using leave-one-site-out cross-validation. MRIQC performs with high accuracy in intra-site prediction, but performance on unseen sites leaves space for improvement which might require more labeled data and new approaches to the between-site variability. 


### (2016 Pizarro) : [**Automated Quality Assessment of Structural Magnetic Resonance Brain Images Based on a Supervised Machine Learning Algorithm**](https://www.frontiersin.org/articles/10.3389/fninf.2016.00052/full), Frontiers in Neuroinformatics

One of the first to apply a **machine learning (SVM) algorithm** in the quality assessment of structural brain images, using global and region of interest (ROI) automated image quality features developed in-house. The performance (accuracy) of the automated SVM approach was assessed, by comparing the SVM-predicted quality labels to investigator-determined quality labels. For classifying 1457 3D-MRI volumes from our database using the SVM approach, the **accuracy is 80%**. These results are promising and illustrate the possibility of using SVM as an automated quality assessment tool for 3D-MRI.


### (2009 Mortamet) : [**Automatic quality assessment in structural brain magnetic resonance imaging**](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.21992), Magnetic Resonance in Medicine

Proposed a fully‐automatic method for measuring image quality of MRI. **Quality measures** are derived by analyzing the **air background** of magnitude images and are capable of detecting:
* bulk motion
* residual magnetization from incomplete spoiling
* blurring
* ghosting. 

The method was _validated on 749 3D T1‐weighted 1.5T and 3T head scans acquired at 36 ADNI_ study sites operating with various software and hardware combinations. Results are compared against qualitative grades assigned by the ADNI quality control center (taken as the reference standard). The derived quality indices are independent of the MRI system used and agree with the reference standard quality ratings with high **sensitivity and specificity (>85%)**.


### (2008 Gedamu) : [**Automated quality control of brain MR images**](https://onlinelibrary.wiley.com/doi/full/10.1002/jmri.21434), Journal of MRI

This work was performed in the context of clinical trials for multiple sclerosis. QC procedures included were: 
* patient brain identity verification
* alphanumeric parameter matching 
* signal‐to‐noise ratio estimation
* gadolinium‐enhancement verification
* detection of ghosting due to head motion

Each QC procedure produces a quantitative measurement which is compared against an acceptance threshold that was determined based on ROC analysis of traditional manual and visual QC performed by trained experts. The automated QC results have high sensitivity and specificity when compared with the visual QC. 
**Unclear actual values or if performance assessed on unseen data**










