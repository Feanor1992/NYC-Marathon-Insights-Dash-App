# NYC Marathon Insights Dash App
This Dash app provides an advanced data analysis and visualization platform for NYC Marathon Results. The project involves data cleaning, feature engineering, outlier detection, and a user-friendly interface for visual exploration. The main features include:
1. Data Cleaning and Preprocessing:
    - Conversion of time-related columns (`overallTime`, `pace`, `ageGradeTime`) into seconds for better numerical analysis.
    - Creation of new features like `pace_to_age_ratio`, `speed` (meters per second), and `gender_age_rank` to provide deeper insights.
    - Binning ages into defined age groups for categorical analysis.
2. Outlier Detection and Removal:
    - Analysis of the `pace_sec` column to identify and remove extreme outliers using a threshold based on the interquartile range (IQR).
3. Interactive Dash App:
    - A dropdown menu allows users to select various visualizations:
        - Violin Plot: Distribution of pace by age group and gender.
        - Scatter Plot: Relationship between overall time and age.
        - Histogram: Distribution of pace values.
        - Scatter Plot: Speed vs. Age.
        - Bar Plot: Average speed by age group.
    - Users can save any generated visualization as an HTML file by clicking a dedicated button.
4. Code Enhancements and User Guidance:
    - Extensive inline comments explain each step of the process for clarity and learning purposes.
    - Configured for offline use with customizable data paths.

This app is ideal for understanding marathon performance patterns and extracting actionable insights from the NYC Marathon dataset.
