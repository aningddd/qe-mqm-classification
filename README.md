# qe-mqm-classification

Research project on developing a multi-label classification Machine Translation Quality Estimation model, based on MQM annotations.

In the folder "data":
1. mqm_generalMT2022_ende.tsv: Raw En-De dataset from https://github.com/google/wmt-mqm-human-evaluation
2. mqm_generalMT2022_zhen.tsv: Raw Zh-En dataset from same source as above
3. train_df.csv: Pre-processed training data (En-De: 0-16367, Zh-En: 16378-27880)
4. validation_df.csv: Pre-processed validation data (En-De: 0-5457, Zh-En: 5458-9293)
5. test_df.csv: Pre-processed test data (En-De: 0-5457, Zh-En: 5458-9293)
6. Files named "multi-[reg/classification]-[language pair]-pred" are the respective trained models' predictions on the test set