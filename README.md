# TextMiningFinalProject


## TODO LIST:
 1st. Clean metadata from .txt file
 
 2nd. Prepare dataframe: 
      . Arrange column names, id, author label and so on 
      
 3rd. Crossvalidation (don't forget to justify)
 
 4td. Baseline: statistics - frequency count analysis
 
 5th. Decide on evaluation metrics
 
 6th. Evaluate Baseline
 
 7th. Separate "new" from "old" authors


To discuss:
- Most .txt files start with general information about the text like title, author, year of publication, summary and so on. Clean all metadata from the txt files
- textpipe if possible?
- Alternatives: ...??

- What will constitute as baseline?

- Evaluation metrics to be used.

- Train the model on each author and then join them


Notes:

- Decided on Cross-validation as the dataset splitting method because the dataset is relatively small

- For Saramago, prof recommends removing punctuation from the stop set

- On Baselines: The baseline represents the starting point of your system: a specific configuration with which results are known. Then, you will make your experiments (add other corpus, change some parameters/algorithms, etc.) and compare the attained results with the baseline, in order to check if you are improving them.

From <https://ricardorei.github.io/chapters/chap_2.html> 

- Seperate contemporary authors from "old" authors as it's likely they will have differences in vocabulary
- Use lemmatization instead of Stemming 

To test, to clean metada>
- https://github.com/textpipe/textpipe

NLTK links:
http://www.nltk.org/howto/portuguese_en.html



Examples similar to our question
- https://www.kaggle.com/c/spooky-author-identification/data
