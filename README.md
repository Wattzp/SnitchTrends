## SnitchTrends

Snitch is a clothing line based in India*


### TABLE OF CONTENTS
- [PROJECT OVERVIEW](#project-overview)
- [OBJECTIVE](#objective)
- [KEY FEATURES](#key-features)
- 



[Download Here](https://www.kaggle.com/datasets/nayakganesh007/snitch-clothing-sales)


<img width="512" height="512" alt="100_Pizza" src="https://github.com/user-attachments/assets/53baa523-0cbb-48d4-a010-0254300dca2c" />



<img width="512" height="512" alt="100_Pizza" src="https://github.com/user-attachments/assets/bce28907-716d-42fb-b088-4b9ca29a52f8" />


### PROJECT OVERVIEW
🧥 Snitch Fashion Sales (Uncleaned) Dataset 📌 Context This is a synthetic dataset representing sales transactions from Snitch, a fictional Indian clothing brand. The dataset simulates real-world retail sales data with uncleaned records, designed for learners and professionals to practice data cleaning, exploratory data analysis (EDA), and dashboard building using tools like Python, Power BI, or ExceL

### OBJECTIVE 
What You’ll Find The dataset includes over 2,500 records of fashion product sales across various Indian cities. It contains common data issues such as:
Missing values

Incorrect date formats

Duplicates

Typos in categories and city names

Unrealistic discounts and profit values


### KEY FEATURES
🧾 Columns Explained Column --Description Order_ID ------Unique ID for each sale (some duplicates) Customer_Name ------Name of the customer (inconsistent formatting) Product_Category ---Clothing category (e.g., T-Shirts, Jeans — includes typos) Product_Name -----Specific product sold Units_Sold --Quantity sold (some negative or null) Unit_Price --Price per unit (some missing or zero) Discount_% ----Discount applied (some >100% or missing) Sales_Amount ------Total revenue after discount (some miscalculations) Order_Date ---------Order date (multiple formats or missing) City -------Indian city (includes typos like "Hyd", "bengaluru") Segment----- Market segment (B2C, B2B, or missing) Profit ---------Profit made on the sale (some unrealistic/negative)



```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
df = pd.read_csv("diabetes.csv")
```














