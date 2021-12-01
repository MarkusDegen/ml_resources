# Feature Engineering
A selection of feature engineering resources

## Categorical Data

### Libraries

|Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [sklearn.preprocessing.OneHotDecoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)                                                | TBD |
| [sklearn.preprocessing.LabelEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)                                                | TBD |
| [tf.keras.utils.to_categorical](https://www.tensorflow.org/api_docs/python/tf/keras/utils/to_categorical)                                                | TBD |

+ Questions
    + How to add a default to the one hot encoding (not known), as it could appear in test data only and not be in train data?
        + An easy solution would be to fill empty data with an "UNKNOWN" category, then OneHotEncoder would just add it
        + But what if train data does not have category "A" and test data does => check what the encoders would do in that scenario


