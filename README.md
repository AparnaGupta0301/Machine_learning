# Quantitative Analysis of Mathematical Problem Types: A Machine Learning Approach to Curriculum Assessment and Educational Data Mining

## Project Overview

This project focuses on using machine learning, specifically Support Vector Machines (SVM), to classify mathematical problems from the American Invitational Mathematics Olympiad (AIMO) by type and difficulty. The goal is to enhance educational strategies and curriculum development through automated problem classification and data-driven insights.

## Abstract

By applying SVM classifiers to categorize AIMO problems based on type and difficulty, we processed and analyzed problem statements using advanced natural language processing (NLP) techniques, including trigram analysis. Our results showed that the SVM classifier achieved an overall accuracy of 32%, highlighting both the potential and the need for further optimization in machine learning applications within educational settings.

## Introduction

The project addresses the increasing interest in machine learning for educational purposes, specifically the classification of mathematical problems. By classifying AIMO problems, known for their complexity, into categories such as algebra, combinatorics, geometry, and number theory, and further by difficulty level, we aim to provide valuable insights for students, educators, and AI researchers.

## Methods

### Tools Used

- **SQL and SQLite3**: For robust data querying and database management.
- **Python**: The primary language for data analysis and machine learning tasks.
- **Pandas**: For high-performance data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Matplotlib and Seaborn**: For data visualization.
- **NLTK**: For text processing and analysis.
- **NumPy and re**: For scientific computing and regular expression support.

### Data Analysis

The dataset consisted of 12,500 problems categorized into seven types (Algebra, Counting and Probability, Intermediate Algebra, Geometry, Number Theory, Prealgebra, Precalculus) and five difficulty levels. The analysis involved visualizing the distribution of problem types and difficulty levels using bar plots and histograms.

### Tokenization and Feature Selection

Problem statements were tokenized into trigrams to capture contextual information. The top 50 trigrams were identified based on frequency and relevance. Irrelevant tokens, such as LaTeX commands and common English stop words, were filtered out to refine the feature set.

### Classification Model

An SVM classifier with a linear kernel was used to categorize the mathematical problems. The dataset was split into training (60%) and testing (40%) sets. The model was trained on the trigram features and its performance was evaluated based on accuracy in classifying problem types and difficulties.

## Results

### Data Summary and Visualization

The analysis showed a significant focus on intermediate-level problems, indicating an educational strategy to enhance problem-solving skills. Histograms illustrated the distribution of problem lengths across different mathematical subjects, revealing strategic approaches in the AIMO curriculum design.

### Trigram Analysis

Top trigrams for each mathematical category were analyzed, providing insights into core themes and concepts within different subjects. This analysis aids in improving automated classification systems and informs curriculum design.

### Classification Model Performance

The SVM classifier achieved an overall accuracy of 32%. Performance varied across different categories, highlighting the need for further optimization. Recommendations for improvement include expanding the training dataset, refining feature selection, and exploring advanced machine learning architectures.

## Conclusion

This project demonstrates the potential of machine learning and NLP in educational content analysis. By automating the classification of mathematical problems, we can provide targeted insights for curriculum development and enhance educational strategies. Future work will focus on improving model performance through dataset expansion, feature refinement, and advanced algorithms.

## Future Work

- **Expanding the Training Dataset**: Including more diverse problem statements to improve model generalization.
- **Refining Feature Selection**: Optimizing features to capture unique attributes of each mathematical category.
- **Exploring Advanced Algorithms**: Investigating sophisticated machine learning models to better capture the nuances of problem statements.

## Repository Contents

- **Data**: Dataset of 12,500 categorized mathematical problems.
- **Code**: Python scripts for data processing, feature extraction, and model training.
- **Models**: Trained SVM models for problem classification.
- **Results**: Analysis and visualization of model performance.

For more details, visit the [GitHub repository](https://github.com/AparnaGupta0301/Machine_learning).

## References
https://www.kaggle.com/competitions/ai-mathematical-olympiad-prize/discussion/488264
