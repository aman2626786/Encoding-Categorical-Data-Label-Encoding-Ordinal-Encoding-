Encoding categorical variables is a crucial step in data preprocessing for machine learning models.
Categorical variables are those that represent categories or labels, such as "red," "blue," and "green" for colors, or "cat," "dog," and "bird" for animals.
Since most machine learning algorithms require numerical input, we need to convert these categorical variables into numerical values. 
Here are some common techniques:

1.Label Encoding:This method assigns a unique integer to each category.
For example, "red" might be encoded as 0, "blue" as 1, and "green" as 2.
This method is simple but can introduce ordinal relationships where none exist.

2.Ordinal Encoding:
This method is used when the categorical variable has an inherent order. For example, "low," "medium," and "high" can be encoded as 0, 1, and 2, respectively.
This method preserves the ordinal relationship between categories.
