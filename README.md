import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
     
In [3]:

# Load the dataset
data = pd.read_csv("/content/E-commerce Website Logs.csv")
     
In [4]:

# Display basic information about the dataset
print("Dataset shape:", data.shape)
     
Dataset shape: (97752, 15)
In [5]:

print("\nColumns:", data.columns)
     
Columns: Index(['accessed_date', 'duration_(secs)', 'network_protocol', 'ip', 'bytes',
       'accessed_Ffom', 'age', 'gender', 'country', 'membership', 'language',
       'sales', 'returned', 'returned_amount', 'pay_method'],
      dtype='object')
In [6]:
print("\nData types:\n", data.dtypes)
     
Data types:
 accessed_date        object
duration_(secs)     float64
network_protocol     object
ip                   object
bytes               float64
accessed_Ffom        object
age                  object
gender               object
country              object
membership           object
language             object
sales               float64
returned             object
