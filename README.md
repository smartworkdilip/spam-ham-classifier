# spam-ham-classifier

In this project i am building spam/ham(non-spam) classifier using naive bayes classifier i have actually show two ways of doing 
this the first one is TF-IDF(TF-term frequency and IDF-inverse document frequency) and the other one is pipeline method.
and i am using the dataset smsSmapCollection you can know more about dataset in readme section of this repository

now i like to define what is TF and IDF.

**TF: Term Frequency**, which measures how frequently a term occurs in a document. Since every document is different in length, it is possible that a term would appear much more times in long documents than shorter ones. Thus, the term frequency is often divided by the document length (aka. the total number of terms in the document) as a way of normalization: 


**IDF: Inverse Document Frequency**, which measures how important a term is. While computing TF, all terms are considered equally important. However it is known that certain terms, such as "is", "of", and "that", may appear a lot of times but have little importance. Thus we need to weigh down the frequent terms while scale up the rare ones, by computing the following: 


 All the required code is provided in spam_ham_classifier_using_naive_bayes_classifier.py 
 
 Thank You
