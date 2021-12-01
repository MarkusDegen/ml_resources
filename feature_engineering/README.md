# Feature Engineering
A selection of feature engineering resources

## Categorical Data

sklearn.preprocessing.OneHotDecoder
sklearn.preprocessing.LabelEncoder
keras.utils.to_categorical

+ Questions
    + How to add a default to the one hot encoding (not known), as it could appear in test data only and not be in train data?
        + An easy solution would be to fill empty data with an "UNKNOWN" category, then OneHotEncoder would just add it
        + But what if train data does not have category "A" and test data does => check what the encoders would do in that scenario


