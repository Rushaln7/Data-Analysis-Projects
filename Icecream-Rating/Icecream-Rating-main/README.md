# Icecream Rating Visualization Project

## Project Overview
This project involves analyzing and visualizing an Icecream Rating dataset using Pandas. The dataset includes ratings for flavor, texture, and overall satisfaction over a period of time. The goal is to explore the relationships between these ratings and identify any trends or insights.

## Dataset Description
The dataset contains the following columns:
- **Date**: The date when the ratings were recorded.
- **Flavor Rating**: The rating of the ice cream's flavor.
- **Texture Rating**: The rating of the ice cream's texture.
- **Overall Rating**: The overall rating of the ice cream.

## Project Structure
The project is structured as follows:
- **data/**: Contains the Icecream Rating dataset in CSV format.
- **notebooks/**: Jupyter notebooks used for data exploration and visualization.
- **visualizations/**: Output visualizations generated during the analysis.
- **README.md**: Project documentation.

## Key Steps and Methodology
1. **Data Cleaning**: 
   - Handled missing or inconsistent data.
   - Ensured the correct data types for each column.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of flavor, texture, and overall ratings.
   - Investigated the correlation between the different ratings.
   
3. **Visualization**:
   - Created various plots to visualize the relationship between flavor, texture, and overall ratings.
   - In this project, various charts were created to explore and understand the Icecream Rating dataset. Below are descriptions of the key visualizations:

- **Line Plot - Daily Ratings**:
       
   ![output-1](https://github.com/user-attachments/assets/6652333b-b27a-4358-ac96-7bab6ee2702b)

  - The line plot shows the trend of different ratings (Flavor, Texture, and Overall) over time. This chart helps identify any upward or downward trends in the ratings.

- **Bar Plot - Flavor Rating**:
     
   ![output-2](https://github.com/user-attachments/assets/f4f21860-ccd9-4a60-a61b-0362d1460509)
  
  - The bar plot visualizes the frequency distribution of the flavor ratings. This chart highlights how often each flavor rating score was given.

- **Stacked Horizontal Bar Plot**:
      
   ![output - 3](https://github.com/user-attachments/assets/6d065c4d-9ab5-40e9-901c-79b53eef457a)
      
  - The stacked horizontal bar plot displays a comparison of the different rating categories (Flavor, Texture, Overall) across different entries. This visualization is useful for seeing the cumulative ratings and how they stack up against each other.

- **Scatter Plot - Texture vs. Overall Rating**:
     
   ![output-4](https://github.com/user-attachments/assets/dd4ef2f0-b81b-4012-a1c1-96b8ef1445c7)

  - The scatter plot shows the relationship between Texture Rating and Overall Rating. Each point represents a combination of these two ratings, and the plot helps in understanding how texture influences overall satisfaction.

 - **Histogram - Distribution of Ratings**:
   
   ![output-5](https://github.com/user-attachments/assets/1f0dbaf5-ceb3-4372-86aa-8c59f12f0428)

   - The histogram provides a distribution of all the ratings in the dataset. This chart is useful for identifying the most common rating scores and understanding the spread of the data.

 - **Box Plot - Rating Variability**:
   
   ![output-6](https://github.com/user-attachments/assets/f3d61253-7784-4f17-b9d7-028381dc0453)

   - The box plot summarizes the distribution of each rating category, highlighting the median, quartiles, and any outliers. This chart is essential for understanding the variability and central tendency of the ratings.

 - **Area Plot - Cumulative Ratings**:
  
  ![output-7](https://github.com/user-attachments/assets/d554d7c7-baaf-460f-932e-edaf5909b1c1)

   - The area plot shows the cumulative effect of all ratings over time. This visualization is effective in understanding the overall trend and comparing the magnitude of different ratings categories.

 - **Pie Chart - Flavor Rating Distribution**:
  
  ![output-8](https://github.com/user-attachments/assets/bd0c5807-b689-44f9-b49d-3c6daa9a8c70)
 
   - The pie chart visualizes the proportion of each flavor rating as a part of the whole. This chart provides a clear picture of how flavor ratings are distributed across the dataset.


## Tools and Libraries Used
- **Python**: Core programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For interactive analysis and visualization.
