# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:

       
![Screenshot 2025-04-12 112711](https://github.com/user-attachments/assets/92fca00e-849f-44a7-abd0-2356423ef946)
![Screenshot 2025-04-12 112744](https://github.com/user-attachments/assets/d257a4ad-6a5e-4561-965b-3c4cfc222f99)
![Screenshot 2025-04-12 112809](https://github.com/user-attachments/assets/c400da1b-39ed-4813-904d-a121733d31fe)
![Screenshot 2025-04-12 112821](https://github.com/user-attachments/assets/fced15de-3ecf-4000-88e2-247e59426c53)
![Screenshot 2025-04-12 112829](https://github.com/user-attachments/assets/358a16ec-2932-4399-8cd0-c7db4e7bc7d3)
![Screenshot 2025-04-12 112837](https://github.com/user-attachments/assets/4130fd3e-8015-4774-ba54-038d2f6fcfb5)
![Screenshot 2025-04-12 112848](https://github.com/user-attachments/assets/3781de8f-f1ef-4863-8064-4b2d578a1fdf)
![Screenshot 2025-04-12 112855](https://github.com/user-attachments/assets/0f9fd007-6e37-44f6-87bd-d32ffc344abe)
![Screenshot 2025-04-12 112902](https://github.com/user-attachments/assets/978e3707-e909-445a-a731-3798ca9490cf)
![Screenshot 2025-04-12 112910](https://github.com/user-attachments/assets/86e38000-71d4-4b8a-96f4-01b201e22e63)
![Screenshot 2025-04-12 112919](https://github.com/user-attachments/assets/cd27f884-1e90-436c-a5f3-5ab1039f9199)
![Screenshot 2025-04-12 112936](https://github.com/user-attachments/assets/9dfae0b0-b8ae-49f8-830a-d803f65108bd)
![Screenshot 2025-04-12 112944](https://github.com/user-attachments/assets/d94e6bfd-08be-4ea7-9e9b-11c8a6a20e24)
![Screenshot 2025-04-12 112952](https://github.com/user-attachments/assets/cd627b9d-d554-4b7d-a757-08e35758e344)

# RESULT:
       Therefore,feature scaling and feature slection has been implented successfully 
