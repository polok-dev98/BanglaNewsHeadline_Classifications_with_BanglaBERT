# Fine tune the Bangla-bert model for Bangla news headline classifications.

0. Perform text pre-processing such as cleaning, stop words remove, stemming and visualize the data for analysis.

1. Used Bangla-BERT-Base version of BERT Tokenizer to tokenize ,build the sequence of intergers of these tokens and others pre-processing steps which is required by BERT model to feed input for training purposes.

2. Used Bangla-BERT-Base version of BERT pretrained model to make context ( pooled output) from the tokenized headline.

3. Used a Dense layer to generate the predictions score of each classes for each headline.

4. Build a architecture to adding BERT models and Dense layer to train the model using DataModeule and Dataloader from pytorch.

5. Used the tranied model to make prediction from new data input (headline).
