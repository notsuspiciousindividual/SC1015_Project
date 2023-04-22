# SC1015 Mini Project
## Predicting winners at the Academy Awards (Oscars)


### About
___
A mini Project of SC1015 (Introduction to Data Science and Artificial Intelligence) aiming to predict winners of Oscars. Please refer to our code in the following order:
1. [Learning_TMDB_API.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/Learning_TMDB_API.ipynb)
2. [Data_Extraction.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/data_extraction.ipynb)
3. [Exporting_Oscar_Winners.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/Exporting_Oscar_Winners.ipynb)
4. [Data_Cleaning.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/Data_Cleaning.ipynb)
5. [Data_EDA.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/data_EDA.ipynb)
6. [Data_Anaylsis.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/data_analysis.ipynb)
7. [Resampling.ipynb](https://github.com/notsuspiciousindividual/SC1015_Project/blob/main/resampling.ipynb)

### Video
Video Presentation
[Link](https://youtu.be/zYE2KUYWkaM)

### Contributors
---
- @notsuspiciousindividual
- @Maarrttiinn
- @lcwlouis

### Problem Definition
---
- Which model best predict whether a movie would win Oscars?

### Models Used
---
- Decision Tree
- K-Nearest Neighbour (kNN)
- Random Forest

### Conclusion
---
- RandomOverSampler together with Random Forest Classification gave the best overall accuracy but low True Positive Rate
- ADASYN resampling with KNN gave decent overall accuracy and True Positive Rate of above 70%
- KNN classification generally gave consistently high True Positive Rate of above 70%

### Learnings
---
- API Usage
- Collaborating using GitHub
- Handling imbalanced datasets using over-sampling techniques (RandomOverSampler, SMOTE, ADASYN)
- Using SimpleImputer to fill in missing numerical variables with median
- Trying different models for analysis like Logistic Regression, Naive Bayes, Support Vector Machine

### References
---
- https://developers.themoviedb.org/3/getting-started/introduction
- https://github.com/nicklimmm/movie-analysis
- https://www.themoviedb.org/talk/621b62abd18572001df182ea 
- https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html
- https://towardsdatascience.com/7-over-sampling-techniques-to-handle-imbalanced-data-ec51c8db349f
