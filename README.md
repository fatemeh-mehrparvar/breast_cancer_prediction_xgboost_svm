# breast_cancer_prediction_xgboost_svm

1. Introduction

2. A brief explanation of the dataset

3. Data Dictionary

4. Data Analysis

4.1 Import Libraries

4.2 Import Dataset

4.3 Data Description

4.4 Noise Detection

4.5 Separation Dataset

4.6 Vizualization


"Breast Cancer"

A breast is made up of three main parts: lobules, ducts, and connective tissue. The lobules are the glands that produce milk. The ducts are tubes that carry milk to the nipple. The connective tissue (which consists of fibrous and fatty tissue) surrounds and holds everything together. Breast cancer is a disease in which cells in the breast grow out of control. There are different kinds of breast cancer. The kind of breast cancer depends on which cells in the breast turn into cancer. Most breast cancers begin in the ducts or lobules. Breast cancer can spread outside the breast through blood vessels and lymph vessels. When breast cancer spreads to other parts of the body, it is said to have metastasized.https://www.cdc.gov/cancer/breast/basic_info/what-is-breast-cancer.htm

 "A brief explanation of the dataset"

 This project is about breast cancer data in a group of people including the 213 patient observations obtained from the University of Calabar Teaching Hospital cancer registry over 24 months (January 2019–August 2021).The data involves eleven features: year of diagnosis, age, menopause status, tumor size in cm, number of invasive nodes, breast (left or right) affected, metastasis (yes or no), quadrant of the breast affected, history of breast disease.Furthurmore,the target(calss) is diagnosis result (benign or malignant). People who have breast cancer and healthy people . In this project, I try to analyse the dataset inorder to find the relationship between features and targetto have better understanding.

 "Data Dictionary"

 1. S/N : Unique identification for each patient

2. Year : The year diagnosis was conducted.

3. Age : Age of patient at the time of diagnose.

4. Menopause : Whether the patient is pro or postmenopausal at the time diagnose.(0 MEANS THAT THE PATIENT HAS REACHED MENOPAUSE WHILE 1 MEANS THAT THE PATIENT HAS NOT REACHED MENOPAUSE YET.)

5. Tumor size : The size in centimeter of the excised tumor.

6. Involved nodes : The number of axillary lymph nodes that contain metastatic.(CODED AS A BINARY DISTRI UTION OF EITHER PRESENT OR ASENT. 1 MEANS PRESENT, 0 MEANS ABSENT.)

7. Breast : If it occurs on the left or right side.(CODED AS A BINARY DISTRIBUTION 1 MEANS THE CANCER HAS SPREAD, 0 MEANS IT HASN'T SPREAD YET.)

8. Metastatic : If the cancer has spread to other part of the body or organ.

9. Breast quadrant : The gland is divided into 4 sections with nipple as a central point.

10. History : If the patient has any history or family history on cancer.(1 means there is a history of cancer , 0 means no history.)

11. Diagnosis result : Instances of the breast cancer dataset.
