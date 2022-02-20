## Description
Attached is a CSV file which has the following details about products from various ecommerce sites.
```
- UUID (Primary Key)
- Price (String)
- Price_unfiltered (String)
- Product Type
- Category
- Level 1 -> This is just a classification of a product.
```

CSV FILE -> [DOWNLOAD](https://github.com/manishleo10/bezen_ecommerce_data_engineering_task/blob/main/test.rar)

### Task: Use the database to find the following results from this data.
1. Products without prices
2. Count of products without prices and with prices in each Product Type, Category, Level 1
3. Correct Product Prices in the correct format (eg: $56) wherever possible and separate them into currency and value columns.
4. List out the categories with average price of product.

>Libraries used in this notebook for analysis

```python
# importing necessary libraries for analysis
import matplotlib.pyplot as plt

plt.style.use("fivethirtyeight")
import seaborn as sns
import numpy as np
import pandas as pd
import re
import locale

```

The `locale` module is part of Python’s internationalization and localization support library. It provides a standard way to handle operations that may depend on the language or location of a user. For example, it handles formatting numbers as currency, comparing strings for sorting, and working with dates.

All the dependency required to run this notebook are listed in `requirements.txt`

At last, to run the notebook. Install all the dependency list in `requirements.txt` and run the notebook cells from the starting.



