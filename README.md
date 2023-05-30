# Data Mining Sales-Bank
## 1. Introduce
The project uses 2 data sets: Sales data and Bank data
- Data mining a sales is an important activity for businesses today, especially in the analysis of sales data. Business data analytics plays an important role in improving warehouse management, chain stores, improving pricing decisions and marketing strategies. Using predictive analytics can help businesses reduce inventory management costs, increase shelf efficiency, focus resources on high-demand areas, and capture trends quickly. sales and optimize shipping.
- Data mining this dataset describes a bank's data about the criteria it considers to agree to lend money to a customer. Some criteria such as whether this customer has a family, how many children, has a car, has a savings account, has a current account... and then will decide whether to agree to a loan or not.
- Dataset in folder Data
## 2. Data cleaning
- Data preprocessing is an important stage in Data Mining process. It includes the steps of data preparation before applying mining algorithms. The goal of this process is to clean, normalize, and transform the data to ensure its integrity, accuracy, and match the requirements of the mining algorithm.
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/fc7faf59-9b1a-4678-a561-7e1431888d89)
- Remove unnecessary categorical columns along with columns with null values.
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/64634ba9-5623-467a-8ba7-f6d9b7bbabb2)

## 3. Data Mining Using SSAS Tools
- SSAS (SQL Server Analysis Services) is a data analysis tool of Microsoft SQL Server. It allows users to create multidimensional and tabular data models to analyze data from different sources.
### 3.1 Microsoft Clustering (Sales Data)
- Microsoft Clustering is one of the popular clustering methods in data mining. This method helps to organize and group data objects into groups based on their similarity. Microsoft Clustering uses clustering algorithms to determine structure and relationships in data.
- Cluster number: 5
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/b7d158b0-a241-4b4d-9da2-41109e29e2c7)
- Cluster Profiles 
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/66a0037a-a4e4-47f8-b150-e1a27d16b34f)

### 3.2 Association Rule (Bank Data)
- Association Rule Mining is one of the popular methods in the field of data mining. It is used to find association rules between targets in the data set. Specifically, this method looks for association patterns between attributes or targets that occur together in the data.
- Dependency Network
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/43be9dbc-02bc-43ed-87bd-d472cf010973)
- Mining Model Prediction
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/7dd1cedc-424f-4aad-97bc-506424b3383a)

### 3.3 Microsoft Decision Trees (Bank Data)
- Microsoft Decision Trees are one of the popular decision methods in data mining. This method uses a decision tree structure to make decisions and predictions based on the analysis of logical rules and relationships in the data.
- Dependency Network
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/ca74658f-7aa5-4cd8-8f90-0331892175ea)
- Decision Trees
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/394efa03-3f78-4c7f-b052-1c7021f1a66d)
- Lift Chart
![image](https://github.com/TheKhoiLv/Data-Mining-Sales-Bank/assets/134827421/f866a4fd-18a1-4c53-b174-6738dbf5c9b4)

