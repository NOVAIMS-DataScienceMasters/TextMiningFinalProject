# TextMiningFinalProject


## TODO LIST:
- [ ] Clean metadata from .txt file using STOP words (**Susana**)
 
- [ ] Prepare dataframe: 
      . Arrange column names, id, author label and so on 
- [x] Change .txt file names so there's no duplicates (**Lara**)
      
- [x] Lowercase, remove accents, remove punctuation function (**Inês**)
 
- [x] test a dummy classifier with two text from Saramago and two with JRS, try to distinguish the two with and without punctuation. Is it an important metric to distinguish JS or not needed? (**Lara**)
      
- [x] Word cloud (freq of words) specially between new and old authors.(**Lara**)

- [ ] Crossvalidation (don't forget to justify) to divide into training and validation set 
 
- [ ] Baseline: statistics - frequency count analysis
      - Bag of words it takes into consideration frequency but not the order of the words. It's naive but not too simplistic but it should be easy to implement
 
- [ ] Decide on evaluation metrics
 
- [ ] Evaluate Baseline
 
- [ ] Separate "new" from "old" authors
 


### Models:

1st With metadata and no metadata

2st DummyClassifier vs... 

3rd.Bag of Authors - trainar modelos autor a autor (last phase)

4th (OPTIONAL) Add Ricardo Reis and Jose Saramago, can our Model distinguish between the two 

### To discuss:

- What will constitute as baseline?

- Evaluation metrics to be used.

- Train the model on each author and then join them


### Notes:

- Decided on Cross-validation as the dataset splitting method because the dataset is relatively small

- For Saramago, prof recommends removing punctuation from the stop set

- On Baselines: The baseline represents the starting point of your system: a specific configuration with which results are known. Then, you will make your experiments (add other corpus, change some parameters/algorithms, etc.) and compare the attained results with the baseline, in order to check if you are improving them.

From <https://ricardorei.github.io/chapters/chap_2.html> 

- Separate contemporary authors from "old" authors as it's likely they will have differences in vocabulary
- Use lemmatization instead of Stemming 

To test, to clean metada>
- https://github.com/textpipe/textpipe

NLTK useful links:
http://www.nltk.org/howto/portuguese_en.html
https://realpython.com/natural-language-processing-spacy-python/
Article describing an example of Authorship Identification of texts:
https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/reports/2760185.pdf



Examples similar to our question
- https://www.kaggle.com/c/spooky-author-identification/data
