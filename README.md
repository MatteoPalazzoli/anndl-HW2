# Artificial Neural Networks and Deep Learning - homework 2
## Time series classification
### Challenge intro
Welcome to the second Homework of the Artificial Neural Networks and Deep Learning course! You have the opportunity to test what you have learnt during the course and to compete with your classmates! 😎  
In this homework, you are asked to correctly classify samples in the multivariate time series format. In other words, since this is a classification problem, the objective is to correctly map the information contained in the features calculated over time to their labels.  
#### Two-Phases Competition
We organized the homework as a two-phase competition:  
- **Phase 1**: development phase. We provide you with labelled training data. Your submissions will be evaluated on a hidden test set corresponding to 34% of the whole test set. The score obtained by your models will be displayed on the leaderboard.  
- **Phase 2**: final phase. Your submissions will be evaluated on a final hidden test set (different from the one of Phase 1 and corresponding to 66% of the whole test set) to compute the final Leaderboard. During this phase, you have the possibility of performing a maximum of 2 submissions. Choose the model you think is the best based on the results of Phase 1.  
To complete the Homework, your team must participate in both phases, and each team member must have successfully submitted at least one model in at least one phase. Please notice that the duration of Phase 2 is very short, as you will have only 2 days. This is because you must only re-submit your best model.  
### Files
- `dataset.zip` contains the dataset. It contains the numpy arrays `X_train` and `y_train`
- `model.ipynb` contains all the code
- `Report.pdf` final report  

### Results
```
Accuracy    Wish        Another     Comfortably   Money       Breathe       Time        Brain       Echoes        Wearing       Sorrow        Hey         Shine
Score       F1 Score    F1 Score    F1 Score      F1 Score    F1 Score      F1 Score    F1 Score    F1 Score      F1 Score      F1 Score      F1 Score    F1 Score
------------------------------------------------------------------------------------------------------------------------------------------------------------------
0.6872      0.3750      0.6475      0.9169        0.4808      0.0000        0.2805      0.7824      0.1250        0.9359        0.7416        0.8696      0.0976
```
More detailed results like the accuracy plot and the confusion matrix are present into the notebook.
