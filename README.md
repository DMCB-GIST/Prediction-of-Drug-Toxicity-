# Prediction-of-Drug-Toxicity

You can download the dataset in https://cactus.nci.nih.gov/download/acute-toxicity-db/  
You can download the pretrained mol2vec model in https://github.com/samoturk/mol2vec/tree/master/mol2vec  

If you have unseen drug data, see Toxicity_prediction with unseen data.ipynb  

The trained model used https://cactus.nci.nih.gov/download/acute-toxicity-db/ data  

The model was conducted through multi-task learning on 59 end points using Avalon fingerprint and mol2vec embedding data as input  

## Generating_Avalon_fp.ipynb
SMILES to Avalon fingerprint

## Generating_Mol2vec_embedding_vectors.ipynb
SMILES to mol2vec embedding vector  
You should download the pretrained mol2vec model

## LD50 prediction of DeepAffinity data.ipynb
Prediction of toxicity for DeepAffinity drug data with pretrained model

## LD50 prediction of FDA dataset.ipynb
Prediction of toxicity for FDA drug data with pretrained model

## Toxicity_prediction with unseen data.ipynb
If you have unseen drug data, you can predict with this code.
