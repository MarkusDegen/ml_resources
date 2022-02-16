# Feature Engineering
A selection of feature engineering resources

## Categorical Data

### Libraries

|Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [sklearn.preprocessing.OneHotEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)                                                | TBD |
| [sklearn.preprocessing.LabelEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)                                                | TBD |
| [tf.keras.utils.to_categorical](https://www.tensorflow.org/api_docs/python/tf/keras/utils/to_categorical)                                                | TBD |
| [pandas.get_dummies](https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html)            | TBD |
| [category encoders](https://pypi.org/project/category-encoders/) | TBD |
| [Youtube: How do I encode categorical features using scikit-learn? (Data School)](https://www.youtube.com/watch?v=irHhDMbw3xo)             | TBD|
| [Blog: Here’s All you Need to Know About Encoding Categorical Data (with Python code)](https://www.analyticsvidhya.com/blog/2020/08/types-of-categorical-data-encoding/) | TBD |
| [Blog: Choosing the right Encoding method-Label vs OneHot Encoder](https://towardsdatascience.com/choosing-the-right-encoding-method-label-vs-onehot-encoder-a4434493149b) | TBD |
| [Blog: Label Encoder vs. One Hot Encoder in Machine Learning](https://contactsunny.medium.com/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621) | TBD |



### Learning

|Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Colab: Categorical Encodings](https://colab.research.google.com/drive/1eP85Lm5DzvZe3X57k_p33xac61jY941Y?usp=sharing)                                                | TBD |



+ Questions
    + How to add a default to the one hot encoding (not known), as it could appear in test data only and not be in train data?
        + An easy solution would be to fill empty data with an "UNKNOWN" category, then OneHotEncoder would just add it
        + But what if train data does not have category "A" and test data does => check what the encoders would do in that scenario


