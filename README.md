# Call Center Data Analysis and Visualization Project

## Overview
This project involves analyzing a call center dataset, focusing on data cleaning, visualization, and transcript analysis to uncover actionable insights. The goal is to identify process inefficiencies, analyze customer-agent interactions, and provide data-driven recommendations to improve overall customer service and operational efficiency.

## Project Workflow
The project is divided into three key phases:
1. **Data Cleaning**
2. **Data Visualization**
3. **Transcript Analysis**

### 1. Data Cleaning
- **Null & NaN Handling**: We identified and handled missing values across all datasets to ensure data integrity.
- **Normalization & Standardization**: Applied relevant techniques to normalize and standardize numerical columns, ensuring consistency across different datasets.
- **Data Aggregation**: Merged multiple datasets into a single, comprehensive dataset to facilitate a unified analysis.

### 2. Data Visualization
- **Histograms**: Explored distributions of waiting and handling times to detect bottlenecks and inefficiencies in call handling.
- **Scatterplots**: Analyzed the relationship between waiting time and handling time, along with the effect of silence percentage on handling duration.
- **Density Plots**: Visualized concentrations of call durations, highlighting frequently occurring values.
- **Pie Charts**: Illustrated primary call reasons by frequency, total handling time, and average handling time.
- **Heatmaps**: Showed correlations between numerical columns, uncovering hidden relationships.
- **Bar Plots**: Compared handling times and sentiment based on customer and agent tone, offering insights into how communication styles impact performance.

### 3. Transcript Analysis
- **Natural Language Processing (NLP)**: Preprocessed call transcripts using tokenization, stop word removal, and lemmatization to extract key insights from conversations.
- **Sentiment Analysis**: Assessed customer sentiment based on call transcript data, helping to identify emotional tones during customer interactions.
- **Call Reason Identification**: Used frequency analysis to identify the top recurring issues customers contact the call center about, paving the way for improved self-service solutions.
- **Word Cloud**: Visualized common themes and keywords from preprocessed transcripts, offering a clear view of prevalent customer concerns.

## Key Insights
- Identified major bottlenecks in call handling times, particularly during periods of high silence.
- Revealed common customer issues that could be resolved via improved IVR (Interactive Voice Response) options.
- Highlighted the relationship between customer-agent communication tones and their impact on handling time and satisfaction.

## Technologies Used
- **Python**: For data manipulation and analysis.
- **Pandas**: Data cleaning and aggregation.
- **Matplotlib & Seaborn**: Data visualization.
- **NLP Techniques**: Tokenization, stop word removal, lemmatization.
- **Scikit-learn**: Standardization and normalization of data.
- **WordCloud**: Visualizing transcript data.
- **Jupyter Notebook**: For running the analysis and sharing results.

## Installation
To run this project, clone the repository and install the required dependencies:
```
git clone https://github.com/username/repository-name.git
cd repository-name
pip install -r requirements.txt
```
