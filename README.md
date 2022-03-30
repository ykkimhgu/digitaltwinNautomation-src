# digitaltwinNautomation-src

# Assignment



## Assignment:  Pre-Processing & Feature Extraction



### Preparation

Download Template source file ([download here](https://github.com/ykkimhgu/digitaltwinNautomation-src/blob/main/Assignment/Assignment_FeatureExtraction_CWRU/DTA_Assignment_CWRU_FeatureExtraction_student.mlx))

Download small CWRU Dataset (**[download here](https://github.com/ykkimhgu/digitaltwinNautomation-src/blob/main/Assignment/Assignment_FeatureExtraction_CWRU/Assignment_FeatureExtraction_CWRU_data.zip)**)

* 1 data file for each fault state
* Normal / Outer Race fault / Inner Race fault




### Extract  and Analyze Features   

**Part 1:** 

* Time Statistical Features
* Plot FFT/PSD
* Frequency Statistical Features
* Compare analyzed features for each states



**Part 2**:

* Envelope Extraction
* Plot STFT of given signal
* Plot Spectral Kurtosis
* Plot Kurtogram





### Report

Submit  in mlx file:  Assignment_FeatureExtraction_Name.mlx





---

## Assignment:  Machine Learning

Submit all tutorial exercise files





# LAB

## LAB: Bearing Fault Diagnosis

Read the reference journal and implement in MATLAB

* Thomas W. Rauber et al. "Heterogeneous Feature Models and Feature Selection Applied to Bearing Fault Diagnosis", IEEE TRANSACTIONS ON INDUSTRIAL ELECTRONICS, VOL. 62, NO. 1, JANUARY 2015


For Dataset 

* CWRU dataset similarly to Journal dataset

<img src="https://user-images.githubusercontent.com/38373000/160838885-b74dc1af-4bc9-4bd1-a76f-0bff7f5dd00a.png" alt="image-20220328150553353" style="zoom:50%;" />

* Download CWRU dataset for this journal: [Download here](https://drive.google.com/file/d/1pv-0E8hA77Nr5-gHwVgPq3PR2rdyCj_-/view?usp=sharing)



For Feature Extraction 

* Statistical Features
* Complex Envelope Analysis
* Wavelet Package Analysis



For Feature Reduction/Selection Use only

- Sequential Forward Selection



For Classification Use 

* SVM

* KNN

* Decision Tree

  ​

### Report

Submit  in mlx & mat files:  

* LAB_PHM_CWRU_Name.mlx  // for main src and report
* *.mat // for other necessary files
