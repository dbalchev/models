# good-pmi.json
## About

The PMI-cool model used in [Semeval 2016 Task 3 Subtask A](http://alt.qcri.org/semeval2016/task3/index.php?id=description-of-tasks). More information about PMI-cool can be found in the [related paper](https://aclweb.org/anthology/S/S16/S16-1130.pdf). This is the bootstrapped model. It is trained on the data for [Semeval 2016 Task 3](http://alt.qcri.org/semeval2016/task3/index.php?id=description-of-tasks). 

## Format

The model is a basic `json` file containing a single JSON object with string keys and number values. Each key/value pair is a mapping from the lower-case word `w` to `PMI(w, good) - PMI(w, bad)`, where `good` and `bad` are the answer classes in the dataset.
