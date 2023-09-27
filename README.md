# Machine-Learning-Optimization

In this project, I explored and compared the run time and model performance of three hyperparameter tuning methods.

* Grid Search: This is a systematic and automated method for hyperparameter tuning. Think of it as a way of finding the best combination of hyperparameters for your model without having to manually try different values one by one. The time and resources to run every combinations becomes increase as the combination increases. Hence, it is very time consuming and inefficient for a production task. 

* Randomized Search: This is an alternative approach to Grid Search, which exhaustively tries all possible combinations of hyperparameter values. This method performs a random selection/combination of hyperparameters for find the optimal values. The downside to using this method might be the inability to find the optimal hyperparameters. 

* Optuna:  Optuna is a sophisticated technique for hyperparameter tuning, employing a Bayesian optimization approach. It harnesses the power of Bayesian reasoning by calculating probabilities to pinpoint the best hyperparameter values, which efficiently reduces computational overhead by eliminating combinations of parameters that are not contributing to model performance. Optuna stands out for its effectiveness in both sampling potential hyperparameters and pruning out less promising ones, making it a valuable tool for enhancing the efficiency of hyperparameter optimization. 
