# Evaluation of the existing spell-checking tools (for English)

Repository for evaluation of different open-source spell checkers. 


### Scripts

All the code scripts are accompanied by a step-by-step description and my comments on it. The summary is provided at the end of the evaluation script (see point 2 below).

1. Dataset collection
   
The code for the test dataset collection is in _Collect_dataset.ipynb_ notebook. You can just run it, and a file with data (_SpellGram_dataset_2k.csv_) will be generated and saved in your working directory. The dataset file is also stored in the _data/_ folder of this repository.

2. Evaluation

The code to evaluate four different approach is in _Evaluate_spell_checkers.ipynb_ notebook. This notebook contains evaluation metrics description, code for the chosen metrics, a short review of the different open-source spell-checkers, as well as the implementation of some of them. 
You have to place the dataset file _SpellGram_dataset_2k.csv_ into the same directory as the evaluation notebook. Then, run cell by cell to get the results.
