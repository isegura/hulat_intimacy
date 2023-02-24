# hulat_intimacy
This repository contains all the code of our participation (HULAT) at emEval-2023 Task 9: Data augmentation for pre-trained transformers applied to Multilingual Tweet Intimacy Analysis (https://codalab.lisn.upsaclay.fr/competitions/7096)

- 1_dataset_MINT.ipynb: in this notebook, you can find code to study the dataset of the task. For example, you will find some plots about the distribution of the intimacy scores, languages and text length. 
- 2_system.ipynb: this notebook allows you to reproduce all our experiments by using the training and test dataset provided by the organizers of the task. To obtain the files train-full.csv and test_labeled.csv, you must contact with the organizers.
- how_split_MINT.ipynb: in this notebook, you can find the code to split the original training dataset into the three splits that we used during the development phase. 
- DA4intimacy.ipynb: this notebook includes the data augmentation techniques that we used to increase the training dataset for this task. 

A detailed description of our system is described in: 

@InProceedings{segura2023hulatintimacy,

  title={HULAT at SemEval-2023 Task 9: Data augmentation for pre-trained transformers applied to Multilingual Tweet Intimacy Analysis},
  
  author={Segura-Bedmar, Isabel},
  
  booktitle = {17th International Workshop on Semantic Evaluation (SemEval-2023)},
  
  year = {2023}
  
}
