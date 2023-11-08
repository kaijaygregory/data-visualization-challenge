# __data-visualization-challenge__

## __Overview__

In this assignment, I analyzed data from a pharmaceutical company called Pymaceuticals, Inc. The company specializes in anti-cancer medications and has conducted an animal study to evaluate potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. The primary focus of the analysis is to assess the performance of Pymaceuticals' drug of interest, Capomulin, compared to other treatment regimens.

## __Data and Files__

I accessed the following data:
- `mouse_metadata.csv`: Metadata about the mice used in the study.
- `study_results.csv`: The results of the animal study, including timepoints, tumor volume, and other relevant information.

## __Tasks__

### __1. Data Preparation__

- I began by merging the `mouse_metadata` and `study_results` DataFrames into a single DataFrame to consolidate the data.
- I identified the number of unique mouse IDs and checked for any mouse IDs with duplicate time points.
- Duplicate data associated with the mouse ID was removed to create a cleaned DataFrame.

### __2. Summary Statistics__

- I generated summary statistics, including the mean, median, variance, standard deviation, and standard error of the mean (SEM) of tumor volume for each drug regimen.
- The summary statistics are organized in a DataFrame with drug regimens as the index and statistics as columns.

### __3. Data Visualization__

- I created bar charts using both Pandas and Matplotlib to display the total number of observed mouse timepoints for each drug regimen.
- I also generated pie charts to visualize the distribution of male and female mice in the study.

### __4. Quartiles, Outliers, and Box Plots__

- I calculated the final tumor volume of mice treated with Capomulin, Ramicane, Infubinol, and Ceftamin.
- Quartiles and potential outliers were determined for each treatment regimen, and the results are displayed using a box plot. Outliers are highlighted with custom styles.

### __5. Line and Scatter Plots__

- A line plot was created to show the tumor volume over time for a single mouse treated with Capomulin.
- A scatter plot displays the relationship between mouse weight and average tumor volume for the entire Capomulin regimen.

### __6. Correlation and Regression__

- The correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen was calculated.
- A linear regression model was generated to understand the relationship between mouse weight and tumor volume.
- The linear regression line was plotted on top of the scatter plot.

## __Analysis/Conclusion__

Drug Regimens Capomulin and Ramicane showed the highest number of observed mouse timepoints, indicating a strong focus on these treatments. Additionally, according to the pie plots, there was a higher distribution of male mice in the study. Quartile and outlier analysis revealed potential outliers for Infubinol, suggesting the need for further investigation. Notably, for a single mouse treated with Capomulin, the tumor volume was highest at a timepoint of approximately 20 days. Overall, this analysis provides a comprehensive overview of the animal study results and the performance of different drug regimens, which is crucial in supporting decision-making at Pymaceuticals, Inc.

## __Technologies Used__

- Python
- Pandas
- Matplotlib
- NumPy
- Jupyter Notebook


