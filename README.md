# Tarea2_RecPatrones
Tarea 2 para el curso de Reconocimiento de Patrones, II Cuatrimestre 2018. Maestría en Electrónica - Tecnológico de Costa Rica

## Install the following libraries to run code:

conda install numpy matplotlib pandas scikit-learn jupyter notebook seaborn 
pip install Cython
pip install auto-sklearn




""""
DESCRIPTION OF THE plot_learning_curve() FUNCTION:
Generate a simple plot of the test and training learning curve.

Parameters
----------
estimator : object type that implements the "fit" and "predict" methods
    An object of that type which is cloned for each validation.

title : string
    Title for the chart.

X : array-like, shape (n_samples, n_features)
    Training vector, where n_samples is the number of samples and
    n_features is the number of features.

y : array-like, shape (n_samples) or (n_samples, n_features), optional
    Target relative to X for classification or regression;
    None for unsupervised learning.

ylim : tuple, shape (ymin, ymax), optional
    Defines minimum and maximum yvalues plotted.

cv : int, cross-validation generator or an iterable, optional
    Determines the cross-validation splitting strategy.
    Possible inputs for cv are:
      - None, to use the default 3-fold cross-validation,
      - integer, to specify the number of folds.
      - An object to be used as a cross-validation generator.
      - An iterable yielding train/test splits.

    For integer/None inputs, if ``y`` is binary or multiclass,
    :class:`StratifiedKFold` used. If the estimator is not a classifier
    or if ``y`` is neither binary nor multiclass, :class:`KFold` is used.

    Refer :ref:`User Guide <cross_validation>` for the various
    cross-validators that can be used here.

n_jobs : integer, optional
    Number of jobs to run in parallel (default 1).
""""