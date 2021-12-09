# Hate-Speech-Detection

This research takes advantage of different embedding including Term Frequency - Inverse Document Frequency (TF-IDF), Glove (Global Vector) and transformers based embedding (eg. BERT, ELECTRA, AlBERT etc.) along with combination of CNN, Bi-LSTM and MLP to give a detailed comparison in order to find the best and efficient method to perform the hate speech detection. The research takes into account three data sets so any biasness in respect to any particular data set can be dealt with. Moreover, the study also compare the cross domain analysis by performing inter dataset experiments .In order to give out the best method we will look into the F1 score of different methods and the one with the highest score will be considered as outperforming its competition.

Dataset 1 : @inproceedings{hateoffensive,
  title = {Automated Hate Speech Detection and the Problem of Offensive Language},
  author = {Davidson, Thomas and Warmsley, Dana and Macy, Michael and Weber, Ingmar}, 
  booktitle = {Proceedings of the 11th International AAAI Conference on Web and Social Media},
  series = {ICWSM '17},
  year = {2017},
  location = {Montreal, Canada},
  pages = {512-515}
  }
  
  Dataset 2 : @inproceedings{founta2018large,
    title={Large Scale Crowdsourcing and Characterization of Twitter Abusive Behavior},
    author={Founta, Antigoni-Maria and Djouvas, Constantinos and Chatzakou, Despoina and Leontiadis, Ilias and Blackburn, Jeremy and Stringhini, Gianluca and Vakali, Athena and Sirivianos, Michael and Kourtellis, Nicolas},
    booktitle={11th International Conference on Web and Social Media, ICWSM 2018},
    year={2018},
    organization={AAAI Press}
}

Dataset 3: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/

This code is written in Python and requires the packages listed in requirements.txt
