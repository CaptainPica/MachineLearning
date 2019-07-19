# MachineLearning
Basic Machine Learning

# Assumptions
Our assumptions for data cleaning are that any columns that are constant or over 99% constant will have little effect on the calculations necessary to predict whether something is a planet given the variance in confirmations and false positives.

# Analysis
The data's relationship for planethood or not is linear. This is supported by the linear kernel having greater accuracy and better performance. Prescision is only somewhat higher, but recall is significantly higher, over double the rbf kernel's. This means that it is identifying many more of the potential planets, which is desirable. Missing planets is less optimal than misidentifying something else as a planet. Linear is also better in this case as it is a simpler model to train and therefore trains itself more quickly.