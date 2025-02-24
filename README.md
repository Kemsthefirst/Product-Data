# Product-Data

**Project Overview: Data Cleaning and Title Optimization**  

This project aims to enhance the quality of a product dataset by applying systematic data cleaning techniques and optimizing product titles for improved readability and SEO performance. The dataset contains multiple attributes, including product IDs, titles, descriptions, bullet points, product types, and length measurements. However, several data quality issues were identified, including missing values, duplicate entries, inconsistent formats, and redundant product title components.  

### **Data Cleaning Process**  

The first step involved assessing the dataset’s structure using pythonto identify missing values, duplicate records, and formatting inconsistencies. The following key cleaning actions were performed:  

- **Handling Missing Values**: Missing bullet points and descriptions were replaced with placeholders such as “No bullet points provided” and “No description available.” Missing product type IDs were filled with “Unknown,” while missing product lengths were replaced with the median value.
  
- **Removing Duplicates**: Duplicate entries based on product ID and title were identified and removed to ensure data integrity.
  
- **Standardizing Formats**: Column names were converted to lowercase with underscores to maintain consistency. Anomalous values, such as negative product lengths, were filtered out.  

### **Short Title Optimization**  
To improve product title clarity and effectiveness, a short_title feature was created using Excel functions. The approach involved extracting essential details while removing redundant words such as “Set of,” “Includes,” and “Features.” The goal was to limit short titles to 30–50 characters while preserving key information. For example:  

### **Visualization and Reporting**  
To demonstrate the impact of data cleaning, bar charts comparing missing values before and after processing were created using Python. The cleaned dataset, along with the optimized titles, is now structured for further analysis.  
