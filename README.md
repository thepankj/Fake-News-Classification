# Fake-News-Classification
The Internet has not only made information accessible to the masses but also has become a hotspot of misinformation and fake news. Fake news can lead to more harm if not correctly identified and tagged. The severity of of the effects of misinformation can be judged from the fact that there have been riots and killings attributed to fake news.

Fake news can even sway people's opinions and affiliations - a fact that political parties have used (and still use) to make people vote in their favour.

As such, it has become necessary to segregate the real from the fake news. But this is not feasible manually thanks to the huge amount of information that is churned out every minute on the internet.

In this project, I tried to classify Fake News using two algorithms, namely Naive Bayes Classifier and PassiveAggressive Classifier. 

## Dataset
The dataset can be downloaded from [here](https://www.kaggle.com/pnkjgpt/fake-news-dataset).

The features in the dataset are:

![Features](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Features.jpg)

## Methodology
The first method was to apply the models to just the titles. It gave fairly good results with the Naive Bayes accuracy at 92.9% and PassiveAggressive Classfier's accuracy at 91.2%.

Naive Bayes![Naive Bayes](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_title_NB.jpg?raw=true "Title")    PassiveAggressive![PassiveAggressive](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_title_PA.jpg)

Then I applied the models to text only. The results improved a lot, and PassiveAggressive classifier preformed better.

Naive Bayes![Naive Bayes](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_text_NB.jpg) PassiveAggressive![PassiveAggressive](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_text_PA.jpg)

Finally I applied the models to title+text. The results improved didn't improve much from the previous try, but there was an improvement.

Naive Bayes![Naive Bayes](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_title_text_NB.jpg) PassiveAggressive![PassiveAggressive](https://github.com/thepankj/Fake-News-Classification/blob/main/images/Accuracy_title_text_PA.jpg)
