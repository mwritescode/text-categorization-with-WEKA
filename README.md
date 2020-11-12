# Text-categorization-with-WEKA
This repository contains the data we used for the experiments conducted the paper _Text categorization with WEKA: a survey_ by Donatella Merlini and Martina Rossini.

In particular, all the multlingual recipes used for our Language Identification experiments can be found in the [Recipes](https://github.com/mwritescode/text-categorization-with-WEKA/tree/main/data/datasets/Recipes) folder. A separate test set in ARFF format can be found [here](https://github.com/mwritescode/text-categorization-with-WEKA/blob/main/data/datasets/leipzig_set.arff); it was used to get an estimate of how well our models could recognize the language of a generic piece of text, that does not have anything to do with cooking. Note that, as stated in the actuall papar these short sentences are extracted from the [Leipzig Text Corpora](https://wortschatz.uni-leipzig.de/en/download). <br/>
Moreover, the [stopword_list.txt](https://github.com/mwritescode/text-categorization-with-WEKA/blob/main/data/stopwords/stopword_list.txt) contains the list of stopwords used for all the six languages we examinated. The file contains one word per line, as is required by the _WordsFromFile_ _stopwordsHandler_ in WEKA.

Lastly, the second text categorization example shown in the paper focuses on detecting the type of dish a certain recipe is about. The dataset used for this part can be found in the [Dishes](https://github.com/mwritescode/text-categorization-with-WEKA/tree/main/data/datasets/Dishes) folder.

All our experiments were conducted using WEKA version 3.8.4.
