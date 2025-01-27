# Global Terrorism Analysis

This project provides a comprehensive analysis of global terrorism data. The dataset contains information on terrorist attacks around the world over the years, and the analysis aims to uncover patterns, trends, and insights related to global terrorism.

The project is implemented using Python and leverages powerful libraries such as `Pandas`, `NumPy`, `Matplotlib`, and `Seaborn` for data manipulation and visualization.

## Project Overview

The dataset used in this project includes a wide range of details on terrorist attacks, including:
- **Country**: The location where the attack occurred.
- **Year**: The year of the attack.
- **Attack Type**: The type of attack (e.g., bombing, armed assault).
- **Fatalities**: Number of people killed during the attack.
- **Injuries**: Number of people injured during the attack.

The project aims to answer questions such as:
- Which countries experience the highest number of terrorist attacks?
- How has the number of attacks changed over the years?
- What are the most common types of attacks?
- What are the trends in fatalities and injuries from terrorist attacks?

## Libraries Used

- **Pandas**: Used for data manipulation, cleaning, and preparation.
- **NumPy**: Utilized for numerical operations and handling large datasets.
- **Matplotlib**: For creating static visualizations, such as bar charts, line plots, and histograms.
- **Seaborn**: For more sophisticated visualizations like heatmaps and correlation plots.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/NishiSharma01/global_terriorism_analysis.git
2. Navigate into the project directory:
 ```bash
   cd global_terriorism_analysis
3. To create a virtual environment, run the following command: 

```
python -m venv venv
```
To activate the virtual environment, run the following command: On Windows: venv\Scripts\activate On macOS/Linux: source venv/bin/activate
To install the required dependencies, you can either manually install each dependency or use a requirements.txt file.
To create a requirements.txt file, open a text editor and enter the following lines: pandas, numpy, matplotlib, and seaborn. Then save the file as requirements.txt. You can then install the dependencies by running pip install -r requirements.txt.
Dataset
The dataset used in this project is publicly available and can be found in the repository as a CSV file (globalterrorismdb_0718dist.csv). The dataset includes over 170,000 records of terrorist attacks from around the world, spanning from 1970 to 2017.

Analysis Overview
Data Cleaning: The dataset is cleaned and preprocessed to handle missing values, duplicate rows, and inconsistent data formats.

Exploratory Data Analysis (EDA):

Visualize the distribution of attacks over the years.
Identify the top countries affected by terrorism.
Explore the types of attacks and their frequency.
Analyze the number of fatalities and injuries per attack type.
Visualization:

Heatmaps: To show the distribution of attacks over time and by region.
Bar and Pie charts: To visualize the top countries and attack types.
Line Plots: To analyze trends in attack frequency and casualties.
   
