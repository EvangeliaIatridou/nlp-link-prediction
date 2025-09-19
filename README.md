# nlp-link-prediction

This program predicts whether or not a research paper cites another based on a network of several thousand papers. Each paper has its correspondent abstract, list of authors and information about which papers it currently cites.
By splitting our data in existent and non existent edges, several features are extracted for each edge category. 
The collective of this data is then split into train and test datasets, trained by various models and then evaluated by several metrics in search of the model with the most accurate predictions.


abstracts.txt was not included due to its large size (over 25mb).
