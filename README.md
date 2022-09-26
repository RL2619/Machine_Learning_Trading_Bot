# Machine_Learning_Trading_Bot
CH14

In recent years, many firms are heavily profited by using computer algorithms that can buy and sell faster than human traders. The speed of these transactions creates competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. 

In this python program, I am planning to improve an existing algorithmic trading systems by enhancing the existing trading signals with machine learning algorithms that can adapt to new data.

### Step 1: Tune the Baseline Trading Algorithm

1. Tune, or adjust, the model’s 'DateOffset' from 3 to 6 months. The Logistic Regression strategy return increase and the precision of classification report also increased

2. Decreasing the SMA windows for the algorithm lower the returns for both strategies. Increase the SMA windows lowers the returns even more. So the best windows are the existing one, which is 8 for short window and 100 for long window.

3. Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.

#### Evaluate a New Machine Learning Classifier

In this section, you’ll use the original parameters that the starter code provided. But, you’ll apply them to the performance of a second machine learning model. To do so, complete the following steps:

1. Import a new classifier, such as `AdaBoost`, `DecisionTreeClassifier`, or `LogisticRegression`. (For the full list of classifiers, refer to the [Supervised learning page](https://scikit-learn.org/stable/supervised_learning.html) in the scikit-learn documentation.)

2. Using the original training data as the baseline model, fit another model with the new classifier.

3. Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file. Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

#### Create an Evaluation Report

In the previous sections, you updated your `README.md` file with your conclusions. To accomplish this section, you need to add a summary evaluation report at the end of the `README.md` file. For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.


