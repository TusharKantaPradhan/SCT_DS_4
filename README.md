US Road Accidents Analysis (2016-2023)
Project Overview
This project provides a comprehensive exploratory data analysis (EDA) of a large-scale dataset of road accidents in the United States, covering the period from February 2016 to March 2023. The primary objective is to identify and visualize the key factors that influence accident occurrences, such as temporal patterns, geographical locations, and environmental conditions. The findings are consolidated into an interactive web-based dashboard built with Streamlit, allowing for dynamic filtering and exploration of the complex data.

Dataset
The analysis is based on the US_Accidents_March23.csv dataset, a granular and extensive collection of accident data.

Source: The dataset is a countrywide car accident dataset, which covers 49 states of the USA. The data is collected from February 2016 to March 2023, using multiple API providers.

Size & Complexity: The dataset is exceptionally large, containing over 7.7 million records and 46 distinct features.

Challenge: Due to its immense size, a key challenge was handling the data efficiently within a standard development environment like Google Colab. The chosen strategy involved loading the full dataset from Google Drive, performing essential preprocessing, and then creating a smaller, representative random sample of 100,000 records to power the interactive dashboard, ensuring a fast and responsive user experience.
