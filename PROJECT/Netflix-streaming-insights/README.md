# Netflix Streaming Insights

## Project Overview

This project involves an in-depth analysis of Netflix's movie and TV show dataset to uncover valuable insights about the content available on the platform. The dataset includes information on shows and movies available on Netflix as of 2019, sourced from Flixable, a third-party Netflix search engine.

## Objectives

The objectives of this project are as follows:

1. **Content Distribution Analysis**: Investigate the distribution of TV shows versus movies and categorize content based on age ratings.
2. **Content Origin Analysis**: Examine the distribution of content based on the country of origin and release details.
3. **Visualization of Content Types**: Create histograms and heatmaps to visualize the distribution of different content types.
4. **Text Analysis**: Generate word clouds to identify the most frequently watched movies and shows.

## Data Source

The dataset for this analysis can be found at:
- [Netflix Movies and TV Shows - Movies and TV Shows Listings on Netflix](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Tools and Libraries

- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **Pandas Profiling**: For generating detailed data reports and visualizations.
- **Wordcloud**: For creating word cloud visualizations.

## Pandas Profiling

Pandas Profiling is used to generate comprehensive reports from DataFrames. To use pandas-profiling, follow these steps:

1. **Import pandas-profiling**:
    ```python
    import pandas_profiling
    ```

2. **Generate Data Report**:
    ```python
    data = # Your DataFrame here
    profile = pandas_profiling.ProfileReport(data)
    ```

3. **Export Report**:
    ```python
    profile.to_file('report.html')
    ```

**Note**: When using Pandas, ensure to consider encoding parameters and handle missing or anomalous values appropriately. Analyze data ranges and assess significant value discrepancies.

## Basic Goals

- Organize Netflix content data into categorical segments.

## Advanced Goals

- Create detailed visualizations, including heatmaps and word clouds, to enhance understanding and insight extraction.
