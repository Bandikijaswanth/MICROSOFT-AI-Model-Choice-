# MICROSOFT-AI-Model-Choice-
AIM

To select an appropriate AI/ML model based on the availability of labeled data.

PROCEDURE
Check whether the dataset is labeled or unlabeled
If labeled data is available, choose supervised learning
Determine the task type (classification or regression)
For Iris dataset, select classification model
Display the selected model
CODE
# Input condition
labeled_data = True

# Model selection logic
if labeled_data:
    model = "Classification Model"
else:
    model = "Unsupervised Learning Model"

# Output
print("Selected Model:", model)
OUTPUT

Selected Model: Classification Model

RESULT

Since labeled data is available, a Classification Model is selected under supervised learning, suitable for tasks like the Iris dataset in Azure ML.
