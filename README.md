# Heterogenous-bagging-ensemble

The idea behind this project is to compare an Heterogeneous Bagging Ensemble using Neural Networks (strong learners) and the same ensemble model consisted of a Decision tree, a Logistic Regression classifier and a Support Vector Classification (SVC) classifier (weak learners) and the impact of imbalanced data on those 2 ensembles.

The Confusion Matrix and the Classification Report of the Weak learners ensemble is expected to be like:
<p align="center">
<img width="400" height="400" alt="weak learner" src="https://user-images.githubusercontent.com/108266112/191858792-759d0533-b711-40e5-83e5-00293c481a1b.png">
</p>

The Confusion Matrix and the Classification Report of the Neural Network learners ensemble is expected to be like:

<p align="center">
<img width="400" height="400" alt="strong learners" src="https://user-images.githubusercontent.com/108266112/191858918-7ad48e33-28ce-47b8-b5b0-5f530ea12966.png">
</p>

The tests showed the negative impact of using imbalanced data on the models. But what is also shown, is that this problem can be fixed using different techniques, like Synthetic Minority Over-sampling Technique (SMOTE). For the comparison of the two models when trained with balanced data, it is shown that both models perform adequately, with the neural network ensemble being a bit better solution as far as results as concerned. But when the consumed time is factored in, the neural networks ensemble falls short of the weak models ensemble. So even though both models are acceptable, which one is preferred depends on how much time is available for the user.
