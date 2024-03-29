# SST: A Simplified Swin Transformer-based Model for Taxi Destination Prediction based on Existing Trajectory

Some highlights related to code grading rubric:
+ Code readability (including file organization, the naming of variables, comments, ...)
  + Notebook file [experiments.ipynb](experiments.ipynb) contains our main pipelines of data pre-processing and model experiments.
  + Since most of our experiments had been done in the Colab, we got Xinyue’s permission to submit .ipynb file.
  + We set the `random_seed=2023` to solve the reproducibility issue.
+ Correct Implementation of a non-deep-learning benchmark (or a second base-deep-learning model)
  + We got Xinyue’s permission not to include a non-deep-learning benchmark.
+ Correct Implementation of the base-deep-learning model
  + Notebook file [experiments.ipynb](experiments.ipynb) contains our main pipelines of data pre-processing and model experiments.
+ Thoughtful selection and correct implementation of the advanced model(s)
  + Notebook file [traditional_Swin_experiments.ipynb](traditional_Swin_experiments.ipynb) contains alternative experiments using traditional Swin Transformer.
+ Optimization (hyperparameter tuning) and regularization techniques
  + Notebook file [hyperparameters_tuning.ipynb](hyperparameters_tuning.ipynb) contains the hyperparameters tuning for the baseline MLP, CNN and LSTM models on a smaller sample.
  + For MLP and Swin modules, we use the idea of dropout.
  + Weight decay plays little effect in our experiment; hence, we do not use it in our project.

Our data is available at https://www.kaggle.com/competitions/pkdd-15-predict-taxi-service-trajectory-i/data?select=train.csv.zip

The code for Swin Transformer is partly from: https://github.com/microsoft/Swin-Transformer

Thanks to Professor Ungar, Professor Korald, TA Xinyue, and all the other TAs for their contributions this semester.

The paper has been accepted for publication at the 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC) (ITSC 2023)!
