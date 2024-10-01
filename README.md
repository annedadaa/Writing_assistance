# Evaluation of the existing spell-checking tools (for English)

Repository for evaluation of different open-source spell checkers. 


### Scripts

All the code scripts are accompanied with a step-by-step description and my comments on it. The summary is provided in the end of the evaluation script (see point 2 below).

1. Dataset collection
   
The code for the test dataset collection is in _Collect_dataset.ipynb_ notebook. You can just run it, and a file with data (_SpellGram_dataset_2k.csv_) will be generated and saved in your working directory. The dataset file is also stored in the _data/_ folder of this repository.

2. Evaluation

The code to evaluate 4 different approach is in _Evaluate_spell_checkers.ipynb_ notebook. This notebook contains evaluation metrics description, code for the chosen metrics, a short review on different open-source spell-checkers as well as implementation of some of them. 
