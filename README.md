## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
       # INCLUDE YOUR CODING AND OUTPUT SCREENSHOTS HERE
       ![Screenshot 2024-11-19 104650](https://github.com/user-attachments/assets/214cd844-86b2-4de1-894c-4c7561ee951c)
![Screenshot 2024-11-19 104704](https://github.com/user-attachments/assets/087cc4c6-082c-483a-b1fa-6f6b38523d6c)
![Screenshot 2024-11-19 104718](https://github.com/user-attachments/assets/3407c553-a488-4e34-946d-a24aa6ba73ba)
![Screenshot 2024-11-19 104732](https://github.com/user-attachments/assets/bed4880c-73ec-40ee-bb3d-e307d599074b)
![Screenshot 2024-11-19 104752](https://github.com/user-attachments/assets/8addb6cd-b5d0-4e39-b8ed-9d6d5a949ee9)
![Screenshot 2024-11-19 104809](https://github.com/user-attachments/assets/1122bed0-9367-4a27-84a2-f7dcaf2c66b5)
![Screenshot 2024-11-19 104826](https://github.com/user-attachments/assets/ce306a86-ade3-4efc-ac0b-518c1600d1e6)
![Screenshot 2024-11-19 104842](https://github.com/user-attachments/assets/51c2459c-f5cd-4151-9f91-e70aa5e96b60)
![Screenshot 2024-11-19 104853](https://github.com/user-attachments/assets/9c37b33c-91d2-4d47-a487-76a78af5c233)
![Screenshot 2024-11-19 104900](https://github.com/user-attachments/assets/8d15f68e-a9f6-461a-81e8-9e260ab27c35)
![Screenshot 2024-11-19 104911](https://github.com/user-attachments/assets/eca4e403-b442-47e3-bc84-54f540a93cfa)
![Screenshot 2024-11-19 104924](https://github.com/user-attachments/assets/07a6c571-a515-4318-acb7-59f7fd279530)
![Screenshot 2024-11-19 104941](https://github.com/user-attachments/assets/94d29a1d-1530-4445-84a9-ed804ef1b765)
![Screenshot 2024-11-19 104958](https://github.com/user-attachments/assets/4bde0698-a43b-4681-b36a-6d96c1a2befc)
![Screenshot 2024-11-19 105018](https://github.com/user-attachments/assets/641c0425-12d0-48cb-9407-e7b7a999ebe6)
![Screenshot 2024-11-19 105024](https://github.com/user-attachments/assets/e157123a-2742-48cf-823e-343ec4006ee9)
![Screenshot 2024-11-19 105033](https://github.com/user-attachments/assets/c2222ab9-6b35-4d8c-bfc6-25a9d7000dd8)
![Screenshot 2024-11-19 105039](https://github.com/user-attachments/assets/bd651d79-dbea-4259-a498-58cffb3edc66)

# RESULT:
      result include feature encoding.

       
