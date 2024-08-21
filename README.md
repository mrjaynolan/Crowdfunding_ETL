# ETL Mini Project
Overview

This project involves extracting, transforming, and loading (ETL) data as part of a data engineering pipeline. The project includes working with multiple datasets, including contacts, campaign details, categories, and subcategories. The main objectives are to clean and process the data, and finally, store the processed data in a structured format.

Project Files

ETL_Mini_Project_JNolan_DJohnson.ipynb: The main Jupyter Notebook containing the ETL process and all related code.
contacts.csv: The cleaned dataset containing contact information.
campaign.csv: A dataset containing campaign details.
category.csv: A dataset containing campaign categories.
subcategory.csv: A dataset containing subcategories related to the campaigns.

Data Sources

1. contacts.csv
This dataset contains cleaned contact information extracted from the ETL process.


2. campaign.csv
This dataset contains detailed information about various crowdfunding campaigns.


3. category.csv
This dataset contains categories related to the crowdfunding campaigns.



Steps Performed

1. Data Extraction
Loaded the initial datasets into Pandas DataFrames.
Inspected the data to understand its structure and contents.
2. Data Transformation
Contacts Dataset:
Cleaned the contact_info column by extracting contact_id, name, and email.
Split the name column into first_name and last_name.
Converted contact_id to an integer data type.
Campaigns, Categories, and Subcategories:
Merged related datasets based on category_id and subcategory_id.
Converted columns such as goal, pledged, backers_count to appropriate numeric data types.
Formatted date columns like launch_date and end_date to datetime format.
3. Data Loading
Exported the cleaned and transformed datasets to CSV files.
Installation

To run the code in this project, you will need the following Python packages:

Pandas
NumPy
Jupyter Notebook
You can install these packages using pip:

bash
Copy code
pip install pandas numpy jupyter
Usage

Open the ETL_Mini_Project_JNolan_DJohnson.ipynb file in Jupyter Notebook.
Run the cells in the notebook sequentially to perform the ETL process.
The cleaned data will be saved in the Resources directory as CSV files.
