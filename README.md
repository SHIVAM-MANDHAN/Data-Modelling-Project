# Data-Modelling-Project

![Data Model Diagram](https://github.com/SHIVAM-MANDHAN/Data-Modelling-Project/assets/110061771/285bff16-0050-4274-8e51-1ad5fa0d06c5)

This project focuses on creating a comprehensive data model design for wealth-related datasets, leveraging data preprocessing, analysis, and PostgreSQL database implementation.

## Project Overview

The Wealth Data Modeling Project involves the following stages:

1. **Data Exploration and Preprocessing**: In this phase, the provided CSV files (wealth account, wealth countries, wealth series) are loaded into Pandas DataFrames. Data preprocessing techniques are applied to clean, transform, and prepare the data for modeling.

2. **Data Model Design**: A logical data model is designed to represent the relationships between entities and attributes within the datasets. This model serves as the foundation for creating structured tables in the database.

3. **Database Implementation**: A PostgreSQL database named `wealthdb` is created. Within this database, three tables—`accounts`, `countries`, and `series`—are defined based on the data model. The processed data is loaded into these tables.

