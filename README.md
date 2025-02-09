A fake news detection system was built with a transfomer architecture and Deep Learning models.This models were trained with a large social meda dataset with over 186000 tweets called CIC Truthseeker 2023 and futher fine-tuned with IOST dataset that contains multiple category news articles(12600 articles).Tensorflow framework is widely used for the models and also hugging face repository is used to import Tokenizer and transformer model.

Workflow:

Cleaning Textual data ---> Transformer(Bert/distillBert) ---> RNN(GRU/LSTM) ---> DNN Dense Layer (ReLU) ---> Dense Layer (Sigmoid) ---> Final Classification (True/Fake)



Following links for the dataset,
CIC Truthseeker 2023:https://www.unb.ca/cic/datasets/truthseeker-2023.html

ISOT:https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets
