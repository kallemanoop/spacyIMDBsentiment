# spacyIMDBsentiment
A movie review sentiment classifier is built using `spaCy`. Avoided the use of alternatives like NLTK or Transformers or Keras etc due to the simple, efficient and application based framework of spaCy whereas all the previously mentioned frameworks are great to work with but more inclined towards research.

Used `LinearSVC` to classify the sentiment with `TFIDVectorizer` as an add-on to mark the importance of certain words in a context.

`Precision : 0.895`<br>
`F1-score : 0.89`

Please refer to the `IMDBSentiment.pdf` for easier understanding of each code block and the significance of certain functions and parameters.
