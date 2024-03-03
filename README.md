# Sales_prediction


This summary encapsulates the critical steps taken in preprocessing a sales prediction dataset and visualizing its key aspects, streamlining the original detailed explanation:
**Data PREPROCESSING**:

**1.	Data Loading**: The dataset 'sales_predictions_2023.csv' is imported from Google Drive into a pandas DataFrame, setting the stage for analysis.

**2.	Preliminary Checks**: Initial explorations with .head() and .info() methods provide insights into the dataset's structure, including data types and potential missing values.

**3.	Cleaning**: Duplicate rows are identified and handled. Missing values in 'Item_Weight' and 'Outlet_Size' are filled with placeholder values (-1 and 'Missing', respectively) to maintain data integrity without losing rows.

**4.	Standardization**: The 'Item_Fat_Content' column is standardized by replacing varying representations of 'Low Fat' and 'Regular' with uniform labels, ensuring categorical data consistency.

**5.	Exploratory Data Analysis (EDA)**: The distribution of categorical variables is examined through value counts, and descriptive statistics for numerical columns are obtained to understand data distribution.

**DATA VISUALSATION**:


**1.	Distribution Insights**: A histogram of 'Item_Outlet_Sales' reveals the sales distribution, while a boxplot of 'Item_Weight' shows weight distribution across products:                                        

![Histogram of col item_outlet_sales](https://github.com/HABIB5585/Sales_prediction/assets/154558342/34e691df-797c-4cae-a6fa-26ac02f779ea)                                                         ![Item_weight(boxplot)](https://github.com/HABIB5585/Sales_prediction/assets/154558342/7130a92a-855f-4280-98ef-77a98fbd6246)
      
      

**2.	Comparative Analysis**: Barplots and boxenplots compare item outlet sales across different item types highlighting which items contribute most to sales and their sales distribution.:![gkf](https://github.com/HABIB5585/Sales_prediction/assets/154558342/4e510d12-c2ab-4bc1-84ec-3f00d5c5d0b4)

      


**3.	Market Segmentation**: A countplot of 'Outlet_Size' visualizes the frequency distribution of different outlet sizes, useful for strategic planning.![Item_weight(boxplot)](https://github.com/HABIB5585/Sales_prediction/assets/154558342/7130a92a-855f-4280-98ef-77a98fbd6246)


**4.	Correlation Analysis**: A heatmap of the correlation between numeric columns helps identify potential predictors for sales and insights into data dynamics. This condensed overview maintains the essence of the data preprocessing and visualization steps, highlighting the methods used to clean, analyze, and draw insights from the dataset efficiently.![corr map](https://github.com/HABIB5585/Sales_prediction/assets/154558342/f347ff35-8f9e-4302-b066-fd11e6ea005b)


!

