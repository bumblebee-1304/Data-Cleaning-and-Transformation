# Data-Cleaning-and-Transformation
### 1. Handling Missing Values

- The **Filter** feature was used on the **Price** column to identify missing values. The blank price cells were replaced with the **mean price** of the available products, while products with no applicable price information were assigned a value of **0**.

- The `=ISBLANK()` function was used to identify missing values in the **Category** column. Where a suitable category could be determined from other entries, the corresponding category value was filled in. For products where no category information was available, **"Unknown"** was assigned.
### 2. Correcting Inconsistent Data

- Inconsistent text formats and spelling errors in the **Product Name** and **Category** columns were identified and corrected using the **Find and Replace** feature. This helped standardize the data and maintain consistency throughout the dataset.
### 3. Removing Duplicates

- Duplicate records were identified and removed using Excel's **Remove Duplicates** feature. This ensured that each record appeared only once and improved the overall accuracy and consistency of the dataset.
### 4. Splitting and Merging Data

- The **Text to Columns** feature was used to split the **Product ID** into separate columns to extract the **Manufacturing Date** and **Country Code**.

- The **CONCAT** function was used to merge the **Brand Name** and **Product Name** columns into a new **Product Brand** column, creating a combined and standardized product identifier.
### 5. Number Formatting

- The **Price** column was formatted as **US Dollar ($) currency** by changing its number format.

- The **Manufacturing Date** column was formatted as a **Short Date** by adjusting its number format, ensuring the dates were displayed consistently and clearly.
### 6. Conditional Formatting

- **Data Bars** were applied to the **Price** column using **Conditional Formatting** to visually represent the relative values.

- A **New Rule** under **Conditional Formatting** was used to highlight the cells in the **Category** column where the value is **"Electronics"**, making those entries easier to identify.
## Conclusion

The data was thoroughly **cleaned, standardized, and transformed** to improve its accuracy, consistency, and usability. Missing values and inconsistencies were addressed, duplicate records were removed, and the data was structured and formatted for clear presentation. The resulting dataset is **organized, reliable, and ready for further analysis.**  

