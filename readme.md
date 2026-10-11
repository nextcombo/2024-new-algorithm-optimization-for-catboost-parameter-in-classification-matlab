# 2024 New Algorithm Optimization for CATBOOST Parameter in Classification, MATLAB and Python Magical Interaction

CatBoost is a machine learning library developed by Yandex, Russia, based on the GBDT (Gradient Boosting Decision Trees) machine learning framework. Since its inception, CatBoost has been favored by researchers for its fast training speed and high accuracy.
However, the developers of CatBoost have only provided Python/R language versions, and there is currently no MATLAB version available online.
Firstly, it must be said that implementing CatBoost using Python is indeed very simple, with numerous examples available online! However, for many who are not familiar with Python, the complex environment configuration can often discourage them! Moreover, MATLAB has a stronger advantage in terms of matrix and vector operations format requirements, as well as running speed. Most importantly, MATLAB does not require the same level of configuration as Python, which is very friendly for beginners.
In fact, once you master the method of calling this article, you can easily call other complex neural networks implemented in Python to avoid the hassle of configuring Python environments.
That's all for the non-intrusive introduction.
This code implements the following functionality: using MATLAB to call the Python Catboost module, and within MATLAB, implementing 10 new algorithms for 2024 and 10 classic algorithms to optimize Catboost parameters.
Let's talk about the results: The dataset used in this code is four music voice feature data, which has been frequently used in previous sessions. The highest accuracy achieved by other classifiers was around 93%, while our CATBOOST achieves an impressive 95%. It's undeniable that CATBOOST's performance is truly strong!
Although the code calls a Python module, it runs very quickly, so you can rest assured to use it!
The four important parameters of Catboost are: (iterations, learning_rate, random_strength, depth)  
'iterations', 100,\n'learning_rate', 0.01,\n'l2_leaf_reg', 3,\n'bagging_temperature', 0,\n'random_strength', 2,\n'depth', 6,\n'rsm', 1,\n'one_hot_max_size', 2,\n'leaf_estimation_method','Gradient',\n'fold_len_multiplier', 2,\n'border_count', 128,\nOptimization algorithms selected include 10 latest algorithms from 2024 and 10 classic optimization algorithms as follows:  
The reason for choosing so many is also to teach everyone how to conveniently replace the algorithm they want to replace.  
To facilitate the modification of intelligent optimization algorithms, the code has been integrated accordingly. For example, just modify the variable H1 here, you can choose different intelligent optimization algorithms, it's so thoughtful!  
Moreover, the most crucial thing is that if you want to add any algorithm, just add the code of the algorithm in the directory, and modify the algorithm name in the main script file.  
Dataset selection includes four categories of musical voice feature signals, with each category having 500 samples, totaling four categories. The first column of the data is the label column, and the remaining 24 columns are feature values. As long as your data is in this form, it's very easy to replace!  
Let's take a look at the code effect!  
Standard CATBOOST classification results:  
For example, optimize CATBOOST classification with the Sparrow Algorithm:
For the data used in this period, 95.3571% accuracy is already quite high! Previously, there were also classifications related to this data, and general classifiers would only be at 80~93%. It's rare for Catboost to directly reach over 95%, which shows its excellent classification ability!
Regarding how to call Python modules from MATLAB, the code package provides detailed explanations, ensuring that you can master it without difficulty! It's certainly not as cumbersome as configuring a Python environment! The purpose of this tweet is to make it easy for beginners to run this code!

## Images

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
