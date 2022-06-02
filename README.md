# ML-models-

>Compared the performance of the 5 different classifiers: 
       *Naïve Base, Decision Tree
       *Random forest
       *Linear discriminate analysis
       *Quadratic discriminate analysis

>Used 5-fold cross-validation starting from having only one feature and increasing the number of features to
2(the first two features), then three (the first three features), then four (the first four features)until all 45 features are used.

>For each set of features (from the set of only one feature to the set of all 45 features) ran the
cross-validation code 100 times and calculated the mean ± standard deviation of sensitivity,
specificity, total accuracy, precision, F1-score, and AUC over all 100 runs for each class.

>Then plotted the change in the mean value of each parameter (sensitivity, specificity, total accuracy,
precision, F1-score, and AUC) versus the number of features and report in a table the maximum
accuracy and the corresponding number of features, sensitivity, specificity, precision, F1-score,
and AUC for each classifier.

>Finally Indicated which classifier has the best performance.

>Dataset info:

*Major depressive disorder (MDD) and bipolar disorder (BD) are major mental diseases that
affect a significant number of people worldwide. Globally, MDD affects more than 300 million
people while it occurs more commonly among females (5.1%) than males (3.6%). Furthermore,
BD affects 1-2 % percent of the world’s population. MDD and a depressive episode of BD (BD-
DE) share similar symptoms and diagnostic criteria. Accordingly, distinguishing BD from MDD
poses a major clinical problem, and BD patients are often misdiagnosed with MDD. On average
it may take 6-8 years of illness before BD is recognized.

*Conventional methods for diagnosis of these disorders are mainly based on questionnaires and
psychiatric evaluations which make them prone to error due to their subjective nature and other
human factors, including the irregular patient history, the expertise of the doctor, and overstated
depressive symptoms reported by patients or the people attending them. Therefore, it would be
clinically valuable to identify biomarkers capable of discriminating BD from MDD.
Electroencephalography (EEG) signals that measure the electrical activity in different parts of
the brain can be used as a quantitative biomarker for this purpose. Then machine learning
techniques can be used to classify EEG signals of patients, into MDD and BD classes.

*In a study, we address these problems by using a larger and balanced training dataset containing
EEG signals of 71 MDD and 71 BD patients. As for the feature extraction, we employed the
symbolic transfer entropy (STE) method. STE is a robust, and computationally efficient measure
of the direction of information flow between different regions of the brain.
The first 45 most discriminating STE features between MDD and BD.
Use these features to classify BD from MDD patients.
