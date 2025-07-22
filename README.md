Dataset:

product_recall dataset----- https://docs.google.com/spreadsheets/d/1m7VERkHaYXCz1pr61q6bxII4ZjMO09lnzMed8AFzQSU/edit?gid=75932470#gid=75932470

● Product ID- Unique identifier for each product.
● Batch Number- Identifier for the production batch of the product.
● Manufacturing Date- Date the product was manufactured.
● Recall Date- Date the product was recalled. Recall is defined as the product retrieval
due to defects
● Defect Rate- Proportion indicating the rate of defects in the product. To convert it to a
percentage, you would multiply the value by 100.
● Units Recalled-The total number of units recalled for the product.
● Reason for Recall-The reason specified for the product's recall.

Tasks to be performed:

● Use CONDITIONAL FORMATTING with a CUSTOM formula that utilizes the
AND(logical_expression1, [logical_expression2, …]) function to highlight rows where
the ‘Defect Rate’ exceeds 15% and the ‘Units Recalled’ are greater than 500. After
highlighting, determine how many such rows exist, and use FILTERS to find the most
common reason for recall among these highlighted rows.
● Calculate the ‘Total Defect Impact’ by multiplying the ‘Defect Rate’ and ‘Units
Recalled’. What is the average Total Defect Impact across all products?
● Create a formula with absolute REFERENCING to calculate penalties for recalls,
where the penalty is determined by multiplying the ‘Units Recalled’ by a fixed penalty rate of 2, which is stored in a specific cell. What is the total penalty for all recalls
based on this calculation?
● Use the ‘Reason for Recall’ column to count the number of recalls for each unique
reason. Which reason has the highest number of recalls?
● Find the earliest and latest Recall Date in the dataset. What is the time gap in days
between the two dates?
● Determine the number of products with a ‘Defect Rate’ between 10% and 20% by
using filters.
● Combine the ‘Product ID’ and ‘Batch Number’ into a single identifier for each
product using the ‘&’ OPERATOR with a '-' in between the two values. What is the
identifier for the first product in the dataset?
● Identify products where the Defect Rate is in the top 10% of the dataset. Highlight
these rows and calculate the total Units Recalled for these products.
● Classify the ‘Defect Rate’ into the following categories using the CONDITIONAL
FORMATTING: Low for a Defect Rate less than or equal to 10%, Medium for a
Defect Rate greater than 10% and less than or equal to 20%, and High for a Defect
Rate greater than 20%. Then, determine how many products fall into each category
using FILTERS.

