# SC1015 Mini Project
## Predicting winners at the Academy Awards (Oscars)


### About
___
A mini Project of SC1015 (Introduction to Data Science and Artificial Intelligence) aiming to predict nominations and or winners. Please refer to our code in the following order:
1. Learning_TMDB_API.ipynb
2. Data_Extraction.ipynb
3. Data_Cleaning.ipynb
4. Data_EDA.ipynb
5. Data_Anaylsis.ipynb
6. Resampling.ipynb

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
- Logistic Regression

### Conclusion
---

- RandomOverSampler together with Random Forest Classification gave the best overall accuracy but low True Positive Rate
- ADASYN resampling with KNN gave decent overall accuracy and True Positive Rate of above 70%
- KNN classification generally gave consistently high True Positive Rate of above 70%

### Learnings
---
- WIP
- API Usage
- Collaborating using GitHub
- Handling imbalanced datasets using over-sampling techniques
- Using SimpleImputer to fill in missing numerical variables with median

### References
---
- https://developers.themoviedb.org/3/getting-started/introduction
- https://github.com/nicklimmm/movie-analysis
- https://www.themoviedb.org/talk/621b62abd18572001df182ea #Limit to page less then 500
- https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html