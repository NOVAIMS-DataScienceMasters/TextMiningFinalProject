# TextMiningFinalProject

To discuss:
- Most .txt files start with general information about the text like title, author, year of publication, summary and so on. Should we delete this information one by one directly on the .txt files? 

- What will constitute as baseline?

- Evaluation metrics to be used.

- ...

Notes:

- Decided on Cross-validation as the dataset splitting method 

- For Saramago, prof recommends removing punctuation from the stop set

- On Baselines: The baseline represents the starting point of your system: a specific configuration with which results are known. Then, you will make your experiments (add other corpus, change some parameters/algorithms, etc.) and compare the attained results with the baseline, in order to check if you are improving them.

From <https://ricardorei.github.io/chapters/chap_2.html> 

- Seperate contemporary authors from "old" authors as it's likely they will have differences in vocabulary

To test, to clean metada>
- https://github.com/textpipe/textpipe
