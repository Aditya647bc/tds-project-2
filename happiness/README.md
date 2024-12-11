# Automated Analysis Report

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Argentina', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
The dataset 'happiness.csv' provides a comprehensive overview of various factors contributing to overall happiness across different countries and years. It includes several key indicators such as the Life Ladder, socio-economic metrics like the Log GDP per capita, social support systems, health metrics, and other subjective measures of well-being. 

### Key Characteristics of the Dataset:

1. **Dataset Composition**:
    - The dataset comprises 2,363 entries across 11 columns, with a diverse range of countries (165 unique country names).
    - The year span in the dataset is from 2005 to 2023, with an average year recorded of approximately 2014.76. 

2. **Missing Values**:
    - There are varying degrees of missing values across different columns. Notably, 'Log GDP per capita' has 28 missing entries, 'Healthy life expectancy at birth' has 63 missing entries, and 'Generosity' has the highest number of missing entries at 81. 
    - This could affect analysis, particularly for metrics that rely on these measures for correlation with happiness.

3. **Summary Statistics**:
    - **Life Ladder**: The average score is around 5.48, indicating a moderate level of happiness reported by respondents. The scores range from a minimum of 1.281 to a maximum of 8.019, suggesting significant variations in perceived well-being among different countries.
    - **Log GDP per capita**: With an average of approximately 9.40, this metric suggests a generally higher economic performance in wealthier nations. However, the standard deviation of about 1.15 indicates diversity in economic conditions across countries.
    - **Social Support**: The mean score of 0.81 reveals comparatively strong levels of social support reported by individuals, which correlates positively with happiness.
    - **Freedom to Make Life Choices**: The average score of 0.75 indicates a moderate to high level of perceived freedom among respondents.
    - **Negative and Positive Affect**: The positive affect score averages around 0.65, while negative affect averages at 0.27. The higher presence of positive emotions could be a contributing factor to the higher Life Ladder scores.

### Insights and Implications:

- **Socio-Economic Correlation**: Given that both GDP per capita and social support have significant averages, it would be worthwhile to explore their direct correlation with the Life Ladder scores through further statistical analysis, such as regression modeling. 
- **Health's Role**: The Healthy Life Expectancy at birth has a considerable impact on general happiness. With an average of around 63.4 years but a wide distribution (from 6.72 to 74.6), health disparities should be a focus area for policy makers aiming to boost national happiness.
- **Impact of Freedom and Generosity**: The perceptions of freedom to make life choices and levels of generosity, despite having high variability and notable missing values, could represent significant opportunities for enhancing community engagement and individual well-being.

### Conclusion:

The 'happiness.csv' dataset presents a multifaceted view of various determinants of happiness across different nations. While the data highlights correlations between economic, social, and emotional factors, the presence of missing values necessitates careful consideration in any subsequent analysis. Future research could delve deeper into the relationships among these variables and examine how national policies play a role in shaping happiness levels. Ultimately, understanding these trends can aid governments and organizations in implementing strategies that aim to improve the quality of life and happiness of their citizens.

## Visualizations
![Visualization](happiness\heatmap.png)
