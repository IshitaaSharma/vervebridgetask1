# NBA Draft Combine Analysis

-*Project Overview:*

This project focuses on analyzing NBA Draft Combine measurements using data collected over multiple years. The primary objective is to explore the relationships between various player attributes and provide insights into potential draft outcomes.


-*Data Description:*

The data can also be found on https://drive.google.com/drive/folders/1f3fyziQIgff5bTL-9CWoc5pxEgLCqnH7
The dataset used in this project, nba_draft_combine_all_years.csv, contains measurements from the NBA Draft Combine across multiple years. The dataset includes various physical and performance metrics such as height, weight, wingspan, and vertical leap, among others. This data is critical in evaluating the athletic potential of draft prospects.


-*Key Columns:*

Player Name: The name of the player.
Year: The year of the combine.
Measurements: Various physical measurements and performance metrics.
Position: The position the player is expected to play in the NBA.


-*The Python libraries used:*

pandas,
numpy,
seaborn,
matplotlib,
scikit-learn.

-*Workflow:*

Step 1: Data Loading and Inspection,
The dataset is loaded into a pandas DataFrame.
Initial inspection of the data is conducted to understand its structure and content.

Step 2: Data Preprocessing,
A custom function is used to convert relevant data to numeric values while handling any errors gracefully.
Missing values and inconsistencies in the data are addressed to prepare the data for analysis.

Step 3: Exploratory Data Analysis (EDA),
Visualization techniques such as histograms and scatter plots are used to explore relationships between variables.
Correlation analysis is performed to identify key factors that might influence draft outcomes.

Step 4: Modeling,
A Linear Regression model is built using sklearn.
The dataset is split into training and testing sets to validate the model's performance.


-*To use the project:*

Load the dataset.
Execute the cells in the Jupyter Notebook to perform the analysis and build the model.
Evaluate the model's performance and explore potential improvements.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or bug reports.
