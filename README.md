# eec-assignment-3--description-continuous-evaluation-with-kafka-solved
**TO GET THIS SOLUTION VISIT:** [EEC Assignment 3- Description Continuous Evaluation with Kafka Solved](https://www.ankitcodinghub.com/product/eec-assignment-3-description-continuous-evaluation-with-kafka-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101432&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEC Assignment 3- Description Continuous Evaluation with Kafka Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment 3 Description Continuous Evaluation with Kafka

Part I (Static Model): 1. Data Analysis:

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
First five rows of the static dataset. The dataset has 268074 rows and 16 columns.

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
The Distribution of the dataset

➔ The image shows the Count, mean, standard deviation, min value, 25%, 50%(median), 70% quartiles, and max value of the dataset.

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
The number of values in each class to see if the data is balanced or imbalanced:

</div>
</div>
<div class="layoutArea">
<div class="column">
We can see that the dataset is balanced as the number of values in each class is not too different than the other, 55% of the data is class 1 and 45% of the data is class 0, which is 10% difference only.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Each feature distribution, and data skewed pattern:

We can see that data features have different skewed patterns.

For example:

labels_average column is right skewed.

The skew of every feature:

Some of features are right skewed and others are left skewed.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.

•

•

</div>
<div class="column">
Feature engineering and data cleaning:

Check for Null values:

There are 8 missing values in longest_word,

this is a very small number so I will remove them.

Check for missing values and categorical:

Timestamp, longest_word, sld columns is categorical values and we will need to encode it to feed it to the model.

Encoding categorical Features:

I used label encoding to encode the categorical values to numerical values.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
3. Feature Filtering/Selection: The dataset has 16 features, we want to reduce these features to make the model more general, faster, and eliminate the redundant values.

Select independent features with:

<ul>
<li>High correlation with the target variable,</li>
<li>Higher information gain or mutual information of the independent variable,</li>
<li>Anova f-test.

Finding correlation with target variable of independent

predictors:

➔I used this approach to filter the feature that has small relation with the target column and put a threshold for the correlation as I only keep the feature if its correlation with the target is greater than 0.2

➔The features I decided to keep from this approach are:

FQDN_count, subdomain_length, lower, numeric, special, labels, longest_word, sld, subdomain.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
➔ Mutual Information or Information Gain: → ANOVA f-test Feature Selection

This approach agrees to remove upper, timestamp By plotting the score of each feature, I am confident to

remove the “entropy”, “labels_max”, “labels_average”, “upper”, “labels_average”, ‘len’,”timestamp” columns.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4.

</div>
<div class="column">
Model Training:

I have already split the data before feature selection, but I need to split it again after it.

I used two learning algorithms and examen their performance before and after data normalization.

80.30

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
I split the dataset into the target and the features, then I used train_test_split from sklearn to split data to train and test with 25% of the data for testing and the rest for training and satisfied it.

I Normalize the training then the testing dataset using Normalizer from sklearn.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
LR without Normalization

</div>
</div>
<div class="layoutArea">
<div class="column">
LR with Norm

</div>
</div>
<div class="layoutArea">
<div class="column">
Naïve Bayes without Norm

</div>
</div>
<div class="layoutArea">
<div class="column">
Naïve Bayes with Norm

</div>
</div>
<div class="layoutArea">
<div class="column">
Accuracy

</div>
</div>
<div class="layoutArea">
<div class="column">
82.44

</div>
</div>
<div class="layoutArea">
<div class="column">
81.56

</div>
</div>
<div class="layoutArea">
<div class="column">
80.30

</div>
</div>
<div class="layoutArea">
<div class="column">
F1-score

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 86 0: 76

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 85 0: 75

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 84 0: 74

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 84 0: 74

</div>
</div>
<div class="layoutArea">
<div class="column">
Precision

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 76 0: 99

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 76 0: 95

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 76 0: 90

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 76 0: 90

</div>
</div>
<div class="layoutArea">
<div class="column">
Recall

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 100 0: 62

Micro avg: 81

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 97

0: 63 Micro avg: 80

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 94

0: 64 Micro avg: 79

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 94

0: 64 Micro avg: 79

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The model with best accuracy is Logistic regression before normalization, but the accuracy is not the best metric to use to evaluate our models, even if our data is balanced, it just gives as an intuition about how both positive and negative were correctly classified, but here in this problem I want to make sure that there is less attacks were classified as normal action PS: recall, but I don’t want all the action be classified as attacks, so I also care about precision, F1 score is a good metric to balance precision and recall, and the Logistic regression model without normalized data is the winner here.

</div>
</div>
<div class="layoutArea">
<div class="column">
5.

</div>
<div class="column">
Model evaluation:

</div>
</div>
<div class="layoutArea">
<div class="column">
•

• •

</div>
<div class="column">
–

– –

</div>
<div class="column">
AUC-ROC:

Is the measure of the ability of a classifier to distinguish between classes.

The ROC is 0.81 which is a good score for our problem.

The higher value of y-axis indicates that the TP is higher than FN.

Precision Recall Curve:

A good classifier will maintain both a high precision and high recall, which we can see in the PR graph.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
• Confusion matrix: It shows combinations of predicted and actual values.

We can see that our model didn’t misclassify the class as class 0, it only misclassified 139 points, and 11623 classified as 1 and it was 0.

➔ At the end, I saved the LR model to use it in dynamic part.

Part II (Dynamic Model):

<ol>
<li>I loaded the model from the static part and then preprocessed the “Kafka_dataset.csv” as previous.</li>
<li>I Run the consumer’s code and validate you are receiving the data stream.</li>
<li>I appended 1,000 observations of data streaming as a window.</li>
<li>Create a function to preprocess the streaming data like the static data before.</li>
<li>Create a pipeline with the same architecture model as static part.</li>
<li>The dynamic part will have 250 windows, as the data streamed, it will calculate its Accuracy, F1 score, compare it with the threshold (F1=85%) and retrain the model if it is lower than it.</li>
<li>I evaluate the F1 score as a chosen metric from the last part for each model on each window and draw the F1 vs iteration plot.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
This is the result of the last window generated, as we care about the F1 score, we can see that it is not changing much, but these small changes can be important depending on the case and the user requirements, so saying dynamic implementation is better or not depends on the situation.

</div>
</div>
</div>
