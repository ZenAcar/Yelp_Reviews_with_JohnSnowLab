## Classifying Yelp Reviews



*. Created a column that adds the length of the review as a feature.

*. Created a list of transformations to be applied in the pipeline:

   - Changed positive and negative to an index.

   - Tokenized the review.

   - Filtered out stop words.

   - Calculated term frequency using `HashingTF`.

   - Calculated TF–IDF.

*. Created a feature vector containing the output from the IDFModel (the last stage in the pipeline) and the length.

   - Seted up the pipeline and and fited it to the data.

   - Created training and testing data.

   - Created and fitted the Naive Bayes model to the training data.

   - Predicted outcomes using the testing set.

   - Used `MulticlassClassificationEvaluator` to evaluate the model on the testing set.
