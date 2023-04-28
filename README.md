# Fine tune Bangla-bert model for Bangla news headline classifications.

# About this phone:

1. Perform text pre-processing such as cleaning, stop_words remove, stemming and visualize the data for analysis.

2. Used Bangla-BERT-Base Tokenizer to tokenize, build the sequence of intergers of these tokens and others pre-processing steps which is required by BERT model to feed input for training purposes.

3. Used Bangla-BERT-Base pretrained model to make context (pooled output) from the tokenized headline which used to classifying the headline class.

4. Used a Dense layer to generate the predictions score of each classes for each headline.

5. Build a architecture to adding BERT models and Dense layer to train the model using DataModeule and Dataloader from pytorch.

6. Used the tranied model to make prediction from new data input (headline).
