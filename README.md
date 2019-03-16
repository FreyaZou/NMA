# Part of NMA (network meta-analysis) project

* Goal: Built a  classifier to filter out irrelevant papers that do not contain the outcome of interest so that I do not need to read every (in total 384 papers) to extract data for my project.
* Steps: 
  1. Convert text to word representation with tf_idf
  2. Meta-feature engineering
  3. Normalize features
  4. Check variable importance
  5. Over-sampling the minority class
  6. Train a model
  7. Use precision and recall to evaluate the model performance (high recall and low precision is acceptable)
* Results:
  testing accuracy: 90%
  recall: 100%
  precision: 78%

