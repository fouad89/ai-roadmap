# NLP - Naive Bayes to Classify Spam Messages
<p style="font-size:16px">In this Notebook, We go over some of the Naive Bayes basic definitions and formulas. The workflow of the notbook is explained. Following preprocessing steps and some evaluation metrics. Two Naive Bayes Classifiers were used. The MultinomialNB classifier had the better performance.   </p>

### Achieved Accuracy: 98.8% 


## Preprocessing (aka Featurising)
<ol style="font-size:16px">
    <li>Tokenization: splitting the words </li>
    <li>Stop words removal</li>
    <li>Remove non-alphabetical charachters.</li>
    <li>Stemming: keeping the root of the word but stripping things like ing, ed etc. More for large data</li>
    <li>Lemmatization: Alternative to stemming by assinging to the same root. more taxing of resources than stemming</li>
    <li>Lowercasing: could be bad in cases where the name turns into a verb like "Mark" and "mark"</li>

</ol>

## There are 2 phases in the Classifer workflow:

<ol style="font-size:16px">
    <li>Learning phase: splitting the data into training and testing data</li>
    <li>Evaluation phase: testing the classifier performance using key metrics.
        Given that TP/FP is True/False Positive, TN/FN True/False Negative:
        <ol> 
            <li>Accuracy: ratio of correctly predicted observation to the total observations
            </li>
            <li>Precision: is the ratio of correctly predicted positive observations to the total predicted positive observations:
            </li>
            <li>Recall or Sensitivity: the ratio of correctly predicted positive observations to the all observations in actual class</li>
        </ol>
    </li>
</ol>

