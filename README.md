# Cardiac_Disease_Evaluator

<h1> Dataset </h1>
<p>This data set was taken from UCI :https://archive.ics.uci.edu/ml/datasets/heart+disease.
It  contains a number of features which are exclusively picked by domain experts through which one can predict whether a person has a cardiac disease or not.</p>

<h2>EDA</h2>
<p>You can check cardiac disease analysis notebook for eda.</p>

<h3> Model Training </h3>
<p>When we deal with a model which would we used for health care purpose we generally accept more False positive rather than False negative.
With this in mind I trained different classification models and checked performace through classification matrix,recall,precision and accuracy.
I also hand picked different thresold levels and tested to avoid false negative. You can check my work in Heart disease prediction notebook.</p>

<p>Through out my training  some models like Dicision tree,Random forest were able to give 100% accuracy.
So I picked Random forest and tested it on validation set for verification </p>

<h3> Flask API </h3>
<p> Api is deployed in heroku cloud Which you can check here : </p>

![Interface](https://user-images.githubusercontent.com/40850370/128129482-0848a108-e73e-4e8a-a545-f09fca4fe080.png)