# Multi-Language Text Summarization Project


## Overview
This project focuses on multi-language text summarization using datasets from the csebuetnlp/xlsum dataset. The goal is to analyze and compare summarization performance across different sample sizes and languages. The project leverages Transformer models to generate concise summaries from multi-language text data.

## Approach Used

### 1. Dataset Extraction
- The project extracts training samples of different sizes (*10, 50, 100, 500, 1000, and 5000*) from the xlsum dataset.
- It includes multiple languages: *Telugu, Urdu, Marathi, Hindi, Tamil, Bengali, and English*.

### 2. Preprocessing
- The extracted data is converted into a structured *Pandas DataFrame*.
- Necessary text preprocessing steps are applied to ensure data consistency.

### 3. Model Training
- Transformer-based models are used for *sequence-to-sequence learning*.
- The model takes in multi-language text data and generates concise summaries.

