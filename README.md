# Customer Call List Dataset Cleanup

## Project Overview
This is a small projectI worked on that focuses on cleaning and standardizing the **Customer Call List** dataset to prepare it for our customer service team. The objective was to filter, clean, and standardize the data to ensure accuracy and consistency, making it ready for efficient call outreach.

## Data Cleaning and Standardization Steps

1. **Removing Duplicates**: We identified and removed any duplicate records from the dataset.
   
2. **Cleaning Special Characters**: Special characters were removed from certain columns to ensure consistency and simplify future operations.

3. **Phone Number Standardization**: The phone numbers were standardized to a consistent format, ensuring they are all properly formatted for calling.

4. **Splitting Address Data**: The address column was split into multiple parts for better clarity and readability.

5. **Standardizing Categorical Columns**:
   - **Do Not Contact**: I replaced 'Y' and 'N' values with 'Yes' and 'No' values to ensure consistency.
   - **Paying Customer**: Similarly, this column was formatted in the same way as the previous one.

6. **Excluding "Do Not Contact" Customers**: We filtered out customers who requested not to be contacted.

7. **Retaining Records with Valid Phone Numbers**: Entries with missing phone numbers were removed.

## Output
The final cleaned and standardized dataset includes:
- Only customers who allowed us to contact them.
- Phone numbers in a consistent format.
 #### N.B: Only Pandas was used when working on this project
