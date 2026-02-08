Task:
Select an appropriate evaluation metric for a classification problem with imbalanced classes.

Plan:
1. Examine the class distribution in the dataset
2. Understand how common metrics behave under imbalance
3. Choose a metric that reflects true model performance

Actions:
- Analyse the dataset and observe that one class appears much more frequently than the other
- Consider how accuracy can be misleading when most samples belong to one class
- Compare alternative metrics such as precision, recall, and F1-score

Tool Use:
Tool: Dataset inspection
Input:
A binary classification dataset with a dominant majority class

Observed Issues:
- High accuracy achieved by predicting only the majority class
- Poor detection of the minority class

Final Answer:
Accuracy is not suitable for imbalanced datasets because it can produce high scores even when the model fails to detect the minority class. Metrics such as precision, recall, or F1-score provide a more balanced evaluation by accounting for both false positives and false negatives.

Reflection:
Choosing an inappropriate metric can hide model weaknesses. Metric selection should always consider the underlying data distribution and the real-world cost of errors.
