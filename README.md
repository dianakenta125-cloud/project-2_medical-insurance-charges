# Project-2_Medical Insurance Charges
Project uses multiple linear regression to predict medical insurance charges based on patients characteristics.
Source:Medical Cost Personal Dataset
  ##features
   age
  -sex
  - bmi
  - number of children
  - smoking status 
  - region 
- insurance charges
  
  ##variable used
 ### independent variables
     bmi
     children
    age
    smoker
  ### Dependent variables
      charges
#Libraries
  pandas
  scikit-learn
  
#Work flow
## 1.data inspection
   load data to check the dataset to check data types and summary statistics
   
### 2.Data preparation
    missing values were checked and smoking variable converted into numerical format
    0 = Non-smoker
    1 = Smoker
 #### 3.train-test-slit method
 ##### 4.model evaluation
    model evaluated using the Mean Squared Error
 ###### 5.Coefficient Interpretation
     model shows how changes in age , bmi ,number of children and smoking status      affect predicted insurance charges while keeping the other variable              constant
 ###### 6.prediction
     Model used to predict insurance charges for new individual based on
     age, bmi, number of children and smoking status
    
    
 



 
