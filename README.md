# Nutosis

This project involves analyzing data from the **2018 Central Park Squirrel Census** to gain insights into the behaviors, health, and various characteristics of squirrels observed in Central Park. This dataset is complemented with additional files containing specific information on squirrel health (e.g., diseased squirrels) and anecdotal stories from observers.

## Project Structure

The project files include:

1. **2018_Central_Park_Squirrel_Census_-_Squirrel_Data.csv**: Primary dataset with 31 columns, including data on squirrel behaviors, physical characteristics, and locations. This data includes fields like date, shift (AM/PM), fur color, and behavior indicators (e.g., "Running," "Eating").

2. **2018_Central_Park_Squirrel_Census_-_Stories.csv**: Contains 12 columns with anecdotal stories about squirrel interactions in the park. Topics include park experiences, census taker stories, and squirrel behaviors.

3. **Diseased_Squirrels.csv**: A single-column dataset containing IDs of squirrels identified as diseased. This can be used to link with other datasets to study health patterns.

4. **Nutosis.ipynb**: Jupyter Notebook containing the project code for data cleaning, exploration, and analysis. The notebook provides detailed steps for loading, preprocessing, and analyzing the squirrel data.

## Key Questions

This project aims to answer the following:

1. **Health Analysis**: How does the health of squirrels (e.g., disease status) relate to other features such as location, fur color, or behavior patterns?
2. **Behavioral Insights**: What behavioral trends can be observed in squirrels based on time (AM/PM shifts) or locations within the park?
3. **Demographic Patterns**: Are there specific demographic patterns (e.g., fur color distribution, age) that correlate with squirrel behaviors or health outcomes?

## Project Requirements

- **Python** (v3.8 or higher)
- **Jupyter Notebook**
- Required libraries: `pandas`, `matplotlib`, `seaborn`, `scikitlearn`
