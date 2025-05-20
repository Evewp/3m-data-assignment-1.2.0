# Assignment

## Instructions

Paste the answer to each question in the answer code section below each question.

### Question 1

Given the following numpy array:

Python:
```
arr = np.array([1, 2, 3, 4, 5])
```

Write a Python code to multiply each element in the array by 2.

Answer:

Python:
```
arr * 2
```

### Question 2

Given the following 2D numpy array:

Python:
```
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to select the second row of the array.

Answer:

Python:
```
arr[1]
```
### Question 3

Given the following 2D numpy array:

Python:
```
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the average of all the elements.

Answer:

Python:
```
arr.average()
```
### Question 4

Question: Select all numeric columns except float from the DataFrame `dft`.

Answer:

Python:
```
dft.select_dtypes(include=['number'], exclude=['float'])
```

### Question 5

Question: How do you return the last 3 rows of a DataFrame `df`?

Answer:

Python:
```
df.tail(3)
```

### Question 6

Question: Return the minimum and maximum of a Series `x` as a new Series with the index `["min", "max"]`.

Answer:

Python:
```
pd.Series([x.min(), x.max()], index=["min", "max"])
```

### Question 7

Question: How do you select rows from a DataFrame where any value in the row exceeds a threshold?

Python:
```
import pandas as pd

df = pd.DataFrame({'A': [1, 2, 3, 4, 5], 'B': [10, 20, 30, 40, 50]})
threshold = 30
```

Answer:

Python:
```

```

### Question 8

Question: How do you compute the cumulative sum of a column in a DataFrame?

Python:
```
import pandas as pd

df = pd.DataFrame({'A': [1, 2, 3, 4, 5]})
```

Answer:

Python:
```

```

### Question 9

Question: How do you convert a Series of strings to uppercase?

Python:
```
import pandas as pd

series = pd.Series(['apple', 'banana', 'cherry'])
```

Answer:

Python:
```

```

### Question 10

Question: Calculate the correlation between 'MSFT' and 'IBM' returns from a DataFrame of stock returns.

Python:
```
import pandas as pd

# Assuming 'returns' is a DataFrame containing stock returns
returns = pd.DataFrame({
    'MSFT': [0.05, 0.07, -0.01],
    'IBM': [0.04, 0.02, 0.03]
})
```

Answer:

Python:
```

```

### Question 11

Question: Slice the Series to return data from 5th to 15th January.

Python:
```
import pandas as pd
import numpy as np

dates = pd.date_range("2023-01-01", "2023-01-31")
data = pd.Series(np.random.rand(len(dates)), index=dates)
```

Answer:

Python:
```

```

### Question 12

Question: How to plot a histogram with 30 bins for `data` in matplotlib? Label the x and y axis as `X` and `Y` respectively.

Python:
```
data = np.random.randn(1000)
```

Answer:

Python:
```

```

### Question 13

Question: How do you create a bar plot in seaborn using the `tips` dataset to show the average tip amount per day?

Python:
```
import seaborn as sns
tips = sns.load_dataset('tips')
```

Answer:

Python:
```

```

### Question 14

Question: How to create a box plot for total_bill categorized by day in the `tips` dataset using seaborn?

Answer:

Python:
```

```

## Submission

- Submit the GitHub URL of your assignment to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
