# Data Preprocessing Steps.
<ol>
    <li>Load the Dataset</li>
    <li>Check for the heads</li>
    <li>Check for null values</li>
    <li>Check for percentage of missing values in each column using mean() * 100</li>
    <li>Treat the categorical and numerical nulls using mode and median or mean</li>
    <li>Check for duplicates</li>
    <li>Drop the duplicates</li>
    <li>Check the datatypes of columns using info()</li>
    <li>Check the shape of the dataset using shape</li>
    <li>Casting of numbers containing columns to numeric else leaving it as it is using pd.to_numeric function</li>
    <li>Check for Outliers using boxplot Q1, Q3, IQR etc</li>
    <li>Check for consistency in Categorical columns i.e object types and convert all of them into the lowercase values for maintaining the consistency</li>
</ol>