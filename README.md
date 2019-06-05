# QuoraDuplicateQuestions
The goal of this project is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.
The python notebook file was run in google colab, it expects the data being present in google drive.
You can modify the code to read from your own file system.

The training dataset can be found at below location
https://www.kaggle.com/c/quora-question-pairs/data/
