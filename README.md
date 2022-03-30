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
* Download CWRU dataset for this journal: [Download here](https://drive.google.com/file/d/1pv-0E8hA77Nr5-gHwVgPq3PR2rdyCj_-/view?usp=sharing)

<img src="https://user-images.githubusercontent.com/38373000/160838885-b74dc1af-4bc9-4bd1-a76f-0bff7f5dd00a.png" alt="image-20220328150553353" style="zoom:50%;" />





For Feature Extraction 

* Statistical Features
* Complex Envelope Analysis
* Wavelet Package Analysis



For Feature Reduction/Selection Use only

- Sequential Forward Selection
- PCA



For Classification Use 

* SVM

* KNN

* Decision Tree

  ​

***Experiment***
Output: Accuracy & Confusion Matrix  

EX1. Without Selection
* Features:Statistical / Envelope / WPT / Global Pool 
* Classifer: SVM / K-NN / Decision Tree

![image](https://user-images.githubusercontent.com/38373000/160844618-4278e8d1-7504-44cb-bb7a-ceceb3d233c0.png)

EX2. With Selection/Reduction
* Features: Global Pool 
* Selection:  PCA / Forward selection
* Classifer: SVM / K-NN / Decision Tree

![image](https://user-images.githubusercontent.com/38373000/160844485-256380c6-5a2a-452e-88f3-36279ac55c04.png)

### Report

Submit  in mlx & mat files:  

* LAB_PHM_CWRU_Name.mlx  // for main src and report
* *.mat // for other necessary files

---
# Project : PHM



## Problem 1: PHM implementation

Select an open dataset/challenge dataset, other than CWRU from the [recommended dataset list]( https://ykkim.gitbook.io/wiki/industrial-ai/phm-dataset)

* You can also choose other PHM dataset for other mechanical parts such as Gears, Battery etc
* You can choose either or both Diagnostics/Prognostics
* You will get more score if you do both Diagnosis and Prognosis
* You can use different dataset for Diagnosis and Prediction



Read related journal papers that used the selected dataset



Then, Implement Diagnose (or/and) Predict failure system in MATLAB

* You can follow the reference journal


Analyze the results and Write a Report in *.mlx 



Give a short Presentation (5min)



## Problem 2: Journal Review



Select one recent (within 5 years) PHM related journal in your interested topic. 

* This journal can be the reference journal in Problem 1
* Also, this journal study may not be related to Problem 1



Give a short Presentation on Journal Review(5min)



### Recommended Journal Reference

You can see publication list in

1. CALCE: https://calce.umd.edu/prognostics-and-health-management

2. SK AI-PHM http://phm.skku.edu/wordpress/index.php/main/research-area/prognostics-and-health-management/

3. SNU- PHM https://shrm.snu.ac.kr/index.php?hCode=RESEARCH_03_02










