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

Step 1: Data Loading and Inspection

The dataset is loaded into a pandas DataFrame.
Initial inspection of the data is conducted to understand its structure and content.

Step 2: Data Preprocessing

Missing values and inconsistencies in the data are addressed to prepare the data for analysis.

Step 3: Correlation Analysis

Correlation analysis is performed to identify key relationships between variables that might influence draft outcomes.

Step 4: Feature Engineering

New features are created based on existing data to enhance the predictive power of the analysis.

Step 5: Exploratory Data Analysis (EDA)

Visualization techniques such as histograms and scatter plots are used to explore relationships between variables.

Step 6: Year-wise Comparison

A comparison is made across different years to observe trends and variations in draft measurements.

Step 7: Key Metrics and Factors

Key metrics and factors affecting draft picks are identified and analyzed.

-*Key Insights:*

Body Fat: Body fat has a positive correlation with draft pick, so players should aim to lower their body fat percentage to improve their chances of being ranked higher in the draft.

Vertical Jump (Max): Vertical jump (max) has a negative correlation with draft pick, so players with a higher vertical jump may be ranked better in the draft. Improving vertical jump could enhance draft position.

Wingspan: Wingspan has a negative correlation with draft pick, indicating that players with longer wingspans are likely to be ranked higher. Increasing wingspan through training and conditioning could be beneficial.

Height: Height has a very weak negative correlation with draft pick, suggesting that while height may contribute slightly, it’s not a strong determinant of draft position. Players shouldn't overly focus on height alone for improving draft rank.

Agility and Sprint: Agility and sprint have positive correlations with draft pick, so players who are faster and more agile might need to focus on balancing these traits with other skills to avoid being ranked lower.

Hand Size: Hand size shows a weak negative correlation with draft pick, so having larger hands could slightly improve a player's draft rank, though it’s not a major factor.

-*To use the project:*

Load the dataset.
Execute the cells in the Jupyter Notebook to perform the analysis and build the model.
Evaluate the model's performance and explore potential improvements.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or bug reports.
