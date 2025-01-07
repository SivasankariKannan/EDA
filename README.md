# EDA

 ### Objectives
- Conduct data cleaning and preprocessing.
- Perform EDA to visualize and understand patterns in the data.
- Validate hypotheses using statistical analysis.

 **Obesity Dataset**
**Description:**
   * This dataset contains information related to factors that may contribute to obesity. 

**Data Source:** 
   * Kaggle
    
**Data Dictionary:**
* **[Gender  ]:** Male or Female
* **[Age     ]:** Age of the individual in years
* **[Height  ]:** Height of the individual in meters
* **[Weight ] :** Weight of the individual in kilograms
* **[family_history_with_overweight]:** Has the individual a family history of overweight or obesity? Yes or No
* **[FAVC    ]:** Does the individual consume high caloric food frequently? Yes or No
* **[FCVC    ]:** How often does the individual consume vegetables? 1 (never) , 2 (sometimes), 3 (always)
* **[NCP     ]:** How many main meals does the individual have daily? 1 to 3
* **[CAEC    ]:** Does the individual monitor the calories they eat? Sometimes, Frequently, Always or No
* **[SMOKE   ]:** Does the individual smoke? Yes or No
* **[CH2O   ]:** How much water does the individual drink daily? 1 (less than a liter), 2 (1 to 2 liters), or 3 (more than 2 liters)
* **[SCC    ]:** Does the individual monitor the calories they burn? Yes or No
* **[FAF    ]:** How often does the individual engage in physical activity? 0 (never) to 3 (always)
* **[TUE    ]:** How many hours does the individual spend sitting on a typical day? 0 (less than an hour), 1 (1 to 2 hours), or 2 (more than 2 hours)
* **[CALC   ]:** Does the individual take extra calories? Always, Sometimes or No
* **[MTRANS  ]:** Transportation method used by the individual: Automobile, Bike, Motorbike, Public Transportation or Walking
* [NObeyesdad ]:  Obesity level of the individual, 
             classified into: Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II or Obesity_Type_III
  
### Steps and Methodology
- Import Library
- Load the dataset
- Understand the data
- Checking for duplicate values
- Check for data types of all columns and treating it
- Separating Numeric and Categorical Column
- Checking for outliers
- Plot Analysis 
- Statistical Analysis

**EDA Performed:**

* **Data Cleaning:** 
    Data type conversion
* **Exploratory Analysis:**
    * **Univariate Analysis:**
        * univariate analysis performed by using hist plots for all num column
    * **Bivariate Analysis:**
        * bivariate analysis performed by using Scatter plots for age and weight column
    * **Multivariate Analysis:**
        * multivariate analysis performed by using box plot for weight , smoke and FAVC column
     
* **Data Encoding:**
  *  Encoding the data on required  column
* **Data Scaling:**
  *  scaling a data on required  column

* **Data Transformation:**
  *  transforming the data on required  column


      
  ### Key Insights
- Higher consumption caloric food (FAVC column) correlates with family_history_with_overweight.
- NObeyesdad are negatively correlated with levels of physical activity ( FAF column).


