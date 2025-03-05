# Multi-Language Text Summarization Project

Overview

This project focuses on multi-language text summarization using datasets from the csebuetnlp/xlsum dataset. The goal is to analyze and compare summarization performance across different sample sizes and languages. The project leverages Transformer models to generate concise summaries from multi-language text data.

Approach Used

1. Dataset Extraction

The project extracts training samples of different sizes (10, 50, 100, 500, 1000, and 5000) from the xlsum dataset.

It includes multiple languages: Telugu, Urdu, Marathi, Hindi, Tamil, Bengali, and English.

2. Preprocessing

The extracted data is converted into a structured Pandas DataFrame.

Necessary text preprocessing steps are applied to ensure data consistency.

3. Model Training

Transformer-based models are used for sequence-to-sequence learning.

The model takes in multi-language text data and generates concise summaries.

4. Evaluation

ROUGE (Recall-Oriented Understudy for Gisting Evaluation) scores are used to measure summarization accuracy.

The evaluation results help determine the effectiveness of the model across different languages and sample sizes.

5. Visualization

Matplotlib and Seaborn are used to generate insightful visualizations.

Trends are analyzed to understand the impact of dataset size on summarization performance.

Files Included

multi 10 samples.ipynb: Analysis with 10 samples.

multi 50 samples.ipynb: Analysis with 50 samples.

multi 100 samples.ipynb: Analysis with 100 samples.

multi 500 samples.ipynb: Analysis with 500 samples.

multi 1000 samples.ipynb: Analysis with 1000 samples.

multi 5k samples.ipynb: Analysis with 5000 samples.
