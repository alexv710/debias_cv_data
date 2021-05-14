# debias_cv_data
Artificial Intelligence: Technology and Law FS21 course project.

In this project we explore the bias in AI-assisted CV screening that could lead to illigal discrimination and experiment with different techniques to mitigate it.

We will be using "Unintended Effects of Anonymous Résumés" dataset by [(Behaghel et al., 2015)](https://www.aeaweb.org/articles?id=10.1257/app.20140185).
Data files are uploaded in this repository, [data_candidates_mainsample.dta](https://github.com/alexv710/debias_cv_data/blob/main/data_candidates_mainsample.dta) is the main dataset file we use in our code. 

* [Bias analysis.ipynb](https://github.com/alexv710/debias_cv_data/blob/main/Bias%20analysis.ipynb) provides statistical analysis of the dataset distribution.
* [Bias_AI_Assisted_CV_Screening.ipynb](https://github.com/alexv710/debias_cv_data/blob/main/Bias_AI_Assisted_CV_Screening.ipynb) provides a simple Neural Network model's predictions, bias analysis and our experiments on de-biasing along with its results.
* [Control Models.ipynb](https://github.com/alexv710/debias_cv_data/blob/main/Control%20Models.ipynb) Experiment with random forest model as a control.
