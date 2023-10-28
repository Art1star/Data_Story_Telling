# Data Visualization: Story Telling

![data_story3_sq-1](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/c44e7c77-6134-432c-add6-1bf5a4ca17e7)

This repository is dedicated to the art of data visualization and data storytelling. In today's data-driven world, effectively conveying information through compelling visualizations and narratives is essential. Whether you are a data scientist, analyst, or anyone interested in making data more accessible and insightful, this repository provides resources and examples to help you master the craft of data storytelling.

## Introduction

Data storytelling is creating a narrative that explains the insights derived from data. It involves selecting and presenting data through visualizations, combining them into a coherent narrative, and effectively communicating your findings to your audience. This repository serves as a guide to help you create engaging and informative data stories.

## Why Data Visualization Matters

Data visualization is the cornerstone of effective data storytelling. It helps in:

- **Understanding Data**: Visualizations provide an intuitive way to grasp complex data.

- **Spotting Trends**: Patterns and trends become evident when data is presented visually.

- **Engaging Audiences**: Visual elements captivate the audience and make data more accessible.

- **Informing Decision-Making**: Data-driven decisions are more informed and effective.

## Tools and Libraries
These are the tools and libraries that we are going to use today.

- [Jupyter Notebook](https://jupyter.org)
- [Pandas](https://pandas.pydata.org)
- [Numpy](https://numpy.org)
- [Matplotlib](https://matplotlib.org)
- [Seaborn](https://seaborn.pydata.org)

## Data Understanding
### Source Data
![Amazon_Books_logo svg](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/688f3d54-a0fc-48a7-bb68-f1bc51b04828)

- [Amazon Top 50 Bestselling Books 2009 - 2019](https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019/data)
- 7 Column
- 550 Rows
  
### Data Dictionary
Dataset on Amazon's Top 50 bestselling books from 2009 to 2019. Contains 550 books, data has been categorized into fiction and non-fiction using Goodreads

- Name : Name of the Book
- Author : The author of the Book
- User Ring : Amazon User Rating
- Reviews : Number of written reviews on amazon
- Price : The price of the book
- Year : The Year(s) it ranked on the bestseller
- Genre : Whether fiction or non-fiction

## Data Preparation 
The first step is to import the necessary library and load the dataset.

![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/343cb089-eee4-476a-b112-c26bdf5adcee)

## Data Cleansing
![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/17f15a39-4956-471c-a96a-1fb0e09d196e)

The data is clean, with correct data types, and free from missing values and duplicates.

## Exploratory Data Analysis & Data Visualization
### Genre of the bestseller books
![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/f5eb5338-6598-47c0-9d40-f3691555d69d)

![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/34df8bc5-54c1-48a2-9ea9-f9f66cc973fe)

Based on the data, Non-fiction books dominate the reviewed book category, representing a substantial 56% share, while fiction books make up the remaining 44% of the reviewed books. This suggests that non-fiction literature tends to generate more reader engagement and feedback compared to their fictional counterparts.

### Distribution of User Ratings for Books
![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/c84ddcf4-95a4-4f7a-b97f-3e8d25f602d0)

![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/30eb2681-4037-423a-8516-7539b92d2e1e)

In this dataset of 550 user ratings for books, we can observe the distribution of ratings on a scale from 0 to 5. The most common rating is 4.8, which accounts for approximately 23% of all ratings. Following closely, ratings of 4.7 and 4.6 are also quite popular, making up about 19.6% and 19.1% of all ratings, respectively. This insight provides a clear picture of the distribution of user ratings in the dataset that over 81.7% of ratings are 4.5 or higher, indicating that a majority of books in the dataset have been positively rated by users.

### Profits by Genre Over the Years
![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/234ba437-1957-4a2c-a2a0-d7a449d80bbb)

![image](https://github.com/Art1star/Data_Visualization_Story_Telling/assets/70962598/e11781c9-2890-4879-8692-5794ae29301d)

In this dataset of book sale profits by year, we observe that fiction books consistently comprised a lower percentage of profits compared to non-fiction. In 2010, non-fiction books accounted for approximately 71% of total profits, whereas fiction books made up about 29%. This trend continued in subsequent years. It is notable that while both fiction and non-fiction profits fluctuated annually, the dominance of non-fiction remained evident throughout the years, with a substantial 64.6% of total profits in 2019.



