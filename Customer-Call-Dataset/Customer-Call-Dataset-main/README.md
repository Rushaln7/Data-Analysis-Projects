# Customer Call List Data Cleaning Project

## Project Overview
This project involves cleaning and preparing a customer call list dataset using Pandas. The dataset includes various details such as customer names, phone numbers, addresses, and contact preferences. The goal of this project is to clean the dataset for further analysis and ensure that it is ready for use in customer outreach initiatives.

## Dataset Description
The dataset contains the following columns:
- **CustomerID**: A unique identifier for each customer.
- **First_Name**: The customer's first name.
- **Last_Name**: The customer's last name.
- **Phone_Number**: The customer's contact number.
- **Address**: The customer's physical address.
- **Paying Customer**: A boolean or categorical indicator showing if the customer is a paying customer.
- **Do_Not_Contact**: A boolean flag indicating customers who should not be contacted.
- **Not_Useful_Column**: A column containing data that is not relevant to the analysis.

## Project Structure
The project is organized as follows:
- **data/**: Contains the raw and cleaned customer call list dataset in CSV format.
- **notebooks/**: Jupyter notebooks used for data cleaning and preprocessing.
- **README.md**: Project documentation.

## Key Steps and Methodology
1. **Data Cleaning**
   - **Handling Duplicate Values**
   - **Data Type Conversion and striping the data**
   - **Removing Unnecessary Columns**
   - **Formatting Phone Number**
   - **Contact Preference Handling**

2. **Data Validation**:
   - Verified the cleaned dataset for consistency and accuracy.
   - Checked the integrity of `Phone_Number` formats to ensure they were valid for customer outreach.

3. **Final Data Preparation**:
   - Created a final cleaned dataset ready for further analysis or direct use in customer outreach campaigns.

## Tools and Libraries Used
- **Python**: The programming language used for data cleaning.
- **Pandas**: Used extensively for data manipulation and cleaning.
- **Jupyter Notebook**: For interactive data cleaning and documentation.
