# Laptop-Price-Project

## Project Overview

This project involves the analysis and exploration of a dataset containing specifications of various laptops. The primary goal is to study the relationship between different hardware and software specifications and the prices of laptops across various brands. This dataset can be utilized for predictive modeling, price comparison, and understanding market trends in laptop configurations.

## Credit

source dataset: https://www.kaggle.com/datasets/muhammetvarl/laptop-price/

preprocessing code: https://www.kaggle.com/code/owm4096/laptop-prices-eda-w-ml-models-91-8-high

## Dataset Description

The dataset comprises several key columns that provide comprehensive information about each laptop model. Below are the details of the columns included:

|      Column Name  | 	Description  |
|-------------------|----------------|
| __Company__  |	The manufacturer or brand of the laptop. |
|  __Product__ |	The specific model name of the laptop.  |
|   __TypeName__  |	The type of laptop (e.g., gaming, business, ultrabook). |
| __Inches__ |	The screen size of the laptop measured in inches. |
|  __Ram__  |	The amount of RAM installed in the laptop (measured in GB).  |
|  __OS__  |	The operating system installed on the laptop (e.g., Windows, macOS, Linux).|
|  __Weight__  |	The weight of the laptop (measured in kg).  |
| __Price_euros__  |	The retail price of the laptop in euros.  |
|  __Screen__  |	The type of screen (e.g., LCD, OLED) used in the laptop.   |
|   __ScreenW__  |	The screen width measurement.  |
|  __RetinaDisplay__  |	Indicates if the laptop features a Retina display (yes/no).  |
|   __CPU_company__  |	The company that manufactures the CPU (e.g., Intel, AMD). |
|  __CPU_freq__ |	The frequency of the CPU (measured in GHz). |
|  __CPU_model__  |	The specific model of the CPU used in the laptop.  |
| __PrimaryStorage__   |	The primary storage capacity (e.g., SSD, HDD) of the laptop.  |
|  __SecondaryStorage__  |	The secondary storage option (if any) available.  |
|  __PrimaryStorageType__  |	The type of primary storage (e.g., SSD, HDD). |
|  __SecondaryStorageType__  |	The type of secondary storage (e.g., SSD, HDD). |
| __GPU_company__ | The manufacturer of the GPU (e.g., NVIDIA, AMD). |
|  __GPU_model__  |	The specific model of the GPU used in the laptop.  |


## Objectives


1. __Data Exploration__ : Understand the distribution of different laptop specifications, identify trends, and visualize relationships between variables.
   
2. __Predictive Modeling__ : Build models to predict laptop prices based on their specifications, evaluating the importance of different features.
   
3. __Market Trends Analysis__: Analyze how various specifications influence pricing, helping consumers make informed purchasing decisions.

## Technologies Used

1. __NumPy__ :

- A fundamental package for numerical computing in Python. NumPy provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to perform operations on these data structures. It is essential for efficient numerical calculations, making it easier to handle data transformations and computations required for analysis.


2. __Pandas__ :

- A powerful data manipulation and analysis library that offers data structures such as DataFrames. Pandas makes it easy to load, clean, and manipulate structured data. It allows for efficient handling of large datasets, making operations like filtering, grouping, and aggregating data straightforward.
  
3. __Matpltlib__ :

- A comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib provides a flexible way to produce high-quality plots and charts. It is widely used for visualizing data distributions, trends, and relationships, helping to communicate insights effectively through graphical representations.

4. __Seaborn__ :
 
  - A statistical data visualization library built on top of Matplotlib. Seaborn enhances the creation of complex visualizations by providing a high-level interface for drawing attractive and informative statistical graphics. It simplifies the process of visualizing relationships between variables and allows for easy customization of visual styles.
 
    
## Conclusion

This project serves as a comprehensive analysis of laptop specifications, providing valuable insights for consumers and researchers interested in the tech market. 
