Emotion Analysis:

  This program contains multiple machine-learning models that classify an input sentence among 28 different emotions. The program initially uses a Naive-Bayes classifier to gauge the
  performance of a simple classifier algorithm. Then, the program uses a SVM with hyperparameter tuning using GridSearchCV() to fine-tune the parameters C and gamma and use the most
  appropriate choice of kernel. Finally, to get the most effective model, we use a pre-trained transformer from BERT using the Transformers model to generate a transformer that classifies
  the given text input among 28 emotion classes.

  Required modules:

      pandas
      numpy
      torch
      sklearn
      transformers

  To run the .ipynb file, install the modules mentioned above on your device before running the jupyter notebook.
      
      
  
  
