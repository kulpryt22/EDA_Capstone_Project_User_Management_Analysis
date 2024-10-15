# EDA_Capstone_Project_User_Management_Analysis
This repository contains an Exploratory Data Analysis (EDA) project focused on user management and engagement levels across different features. The notebook explores user activity, certification status, and various metrics that help understand user behavior.

## Project Overview

This project performs the following:

- Analysis of user engagement based on different activity levels.
- Visualization of user completion rates using **pie charts** and **boxplots**.
- Identification of trends in certification rates.
- Exploration of relationships between various features like sessions count, time spent, and number of events.

## Files

- **EDA_Capstone_Project_User_Management_Analysis.ipynb**: The primary Jupyter Notebook file where the analysis is conducted.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (install them using `pip`):

  ```bash
  pip install pandas matplotlib seaborn
  ```

### How to Run

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repository
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook EDA_Capstone_Project_User_Management_Analysis.ipynb
   ```

4. Run the cells sequentially to perform the analysis.

## Key Features

### 1. Pie Chart of User Engagement Levels
- The pie chart visualizes the proportion of users based on their engagement levels. Small categories are grouped into an "Other" category to avoid clutter in the chart.

### 2. Boxplot of Certified Courses
- A boxplot was initially used to understand the spread of users completing courses but was replaced with a countplot for better representation due to the binary nature of the data (certified or uncertified).

### 3. Countplot for Certified Users
- A more appropriate **countplot** was implemented to visualize the number of certified vs uncertified users, replacing the boxplot to give a clearer insight.

## Visualizations

This notebook contains the following visualizations:
- **Pie Charts** for user engagement distribution.
- **Countplot** showing the count of certified versus uncertified users.
- Additional visualizations to understand relationships between key features like time spent, number of sessions, and completed courses.

## Future Enhancements

- Adding advanced insights such as correlations between user activities and certification rates.
- Applying machine learning models to predict user certification based on engagement metrics.
- Further optimization of visualizations for complex datasets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
