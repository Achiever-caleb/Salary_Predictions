# Salary Dataset - README  

## Description
The Salary Dataset is a simple CSV file designed for practicing and understanding **simple linear regression**. It has been widely used in various Machine Learning tutorials, including the **Machine Learning A to Z** series, to demonstrate how experience in years can be used to predict salary.  

---

## Columns  
1. YearsExperience:  
   - Represents the number of years an individual has worked in their field.  
   - Data Type: `float` or `integer`  

2. Salary:  
   - Represents the annual salary of the individual (in monetary units).  
   - Data Type: `float` or `integer`  
 

---

## Example Code to Load the Dataset

```python
import pandas as pd

# Load the dataset
file_path = "path_to_dataset/salary_dataset.csv"
data = pd.read_csv(file_path)

# View the first few rows
print(data.head())
```

---

## Applications  
- Predicting salary based on years of experience.  
- Visualizing data trends using scatter plots and regression lines.  
- Evaluating regression metrics such as MAE, MSE, and R².  

---

## License
This dataset is used for educational purposes only 
