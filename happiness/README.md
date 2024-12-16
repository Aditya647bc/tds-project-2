# Automated Analysis Report

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Argentina', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
The dataset 'happiness.csv' encompasses a comprehensive analysis of various factors influencing happiness across different countries over a span of years. It includes a total of 2,363 entries covering multiple dimensions of well-being.

### Data Overview:
- **Country Coverage**: The dataset records information for 165 unique countries, with Argentina being the most frequently represented, with 18 entries.
- **Temporal Span**: The years represented range from 2005 to 2023, with a mean year of approximately 2014.76. Most entries fall between 2011 and 2019.

### Key Variables:
1. **Life Ladder**: This metric, which quantifies individual well-being on a scale, averages around 5.48, indicating a moderate level of reported happiness across nations, with notable variance (std = 1.13). The values range from a low of 1.281 to a high of 8.019.
  
2. **Log GDP per capita**: This variable indicates reasonably strong economic health, with a mean of about 9.4. Notably, this suggests that countries tend to reflect a higher GDP when correlated with increased happiness. Missing values (28 entries) indicate areas for improvement in data completeness.

3. **Social Support**: Averaging at 0.81, social support seems to play a crucial role in enhancing happiness, with a range from 0.228 to 0.987. This variable has 13 missing entries.

4. **Healthy Life Expectancy at Birth**: At around 63.4 years, this metric underscores the importance of health in overall happiness. With a standard deviation of 6.84, it indicates variability among nations. A significant number of entries (63) are missing, highlighting areas where data collection may be deficient.

5. **Freedom to Make Life Choices**: This metric also ranks high with a mean of 0.75. The ability to exercise personal freedom is evidently a crucial factor contributing to happiness.

6. **Generosity**: This variable appears less impactful, with a mean very close to zero (0.00009772), suggesting that overall generosity among countries might not be a significant predictor of happiness or may vary greatly across nations.

7. **Perceptions of Corruption**: Corruption perception is a critical variable, with a mean of about 0.7449. This indicates relatively moderate levels of perceived corruption, which could correlate inversely with happiness.

8. **Affect Metrics**: Positive affect averages at around 0.65, reflecting a generally favorable emotional state, while negative affect averages approximately 0.27. The distinction between these measures affirms the complex nature of happiness, where positive experiences often outweigh negative ones.

### Missing Values Analysis:
The analysis reveals considerable missing data, particularly in Generosity (81 missing), Perceptions of Corruption (125 missing), and Healthy Life Expectancy (63 missing). Handling these missing values will be crucial for deriving robust conclusions from the dataset. 

### Summary:
The overall synthesis of the happiness dataset signals a complex interplay of economic, social, and emotional factors that contribute to national happiness. While variables such as social support and life ladder stand out positively, the presence of significant missing data in some factors necessitates caution in interpreting correlations. A deeper examination into these predictors can facilitate better understanding and potential strategies to enhance happiness across various regions. Further research could explore the causal relationships among these variables and how they evolve over time.

## Visualizations
![Visualization](happiness\heatmap.png)
