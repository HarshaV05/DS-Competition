# DS-Competition
Competition Instructions:

The provided datasets(train_data.json) contains a feature space that describes various odorant molecules. The target is whether the molecules have a 'fruity' smell or not.

The task is to train a model that predicts whether unseen molecules have a fruity smell. use a classifier of your choice and tune the hell out of it, but make sure you retain a hold-out set for validating your parameter tuning.

The dataset and code to load it will be provided on Canvas during the practical when a sizable number of students have completed the previous parts.

Towards the end of the practical we will release a test set(test_data.json), from the same source, that allows you to verify your efforts.

# Summary:

I have used Naive Bayes, SVM and Neural networks(MLP) for this classification task. Hyperparameter tunig is applied and best paremeters for each algorithm are chosen using random and grid search techniques. I was able to obtain a best accuracy of around 78% with SVM algorithm. 

