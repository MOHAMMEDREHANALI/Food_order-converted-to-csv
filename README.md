
# Food Order Dataset – Pandas

## Project Overview
This project demonstrates how to create a structured Food Order Dataset using Python and Pandas and export it into a CSV file for data storage and further analysis.

## Dataset Information
The dataset contains 15 food order records with the following columns:

- `order_id` – Unique order identification number
- `date` – Order date
- `customer` – Customer name
- `city` – Customer's city
- `cuisine` – Food category
- `amount` – Order amount
- `rating` – Customer rating
- `delivery_min` – Delivery time in minutes

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Operations
- Created a DataFrame using `pd.DataFrame()`
- Organized food order information into columns
- Displayed records using `df.head()`
- Exported the DataFrame into CSV using `df.to_csv()`
- Used `index=False` to avoid an additional index column

## Output
Generated CSV file: `food_order2.csv`

## How to Run

```python
import pandas as pd

df = pd.read_csv('food_order2.csv')

print(df.head())
```

## Learning Outcome
Learned how to create Pandas DataFrames, structure tabular data, and export datasets into CSV format for future data analysis.

---
**Author:** Python & Data Science Learner
