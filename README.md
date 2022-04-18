# NLP-Dissertation

## Detecting idiomatic language usage through Natural Language Inference NLP approach.

The objective of the project was to leverage advances in neural network models to represent languages and investigate the Natural Language Inference (NLI) approach for idiomatic classification. 

The main outcomes achieved were, understood the key problems in the detection of idiomatic usage and identified a few promising solutions that are being implemented, collected multi-word/idiomatic expression data from open-source text corpora and other sources through web scraping and created datasets of idiomatic inferences for NLI model evaluation, and finally trained different context-based neural models such as BERT, LSTM, and zero-shot RoBERTa for NLI task to assess their performance against other baseline approaches and concluded that this approach can potentially be adapted for the classification of an idiomatic compound used in a literal sense or idiomatic sense.


## Instructions

1. The Noun compound datasets and the manual generated inference datasets are present in the 'Datasets' folder/rar.

2. The custom DataProcessor and the PVP objects are added within the pet-master directory and the train-unlabelled datasets used for the experiment can be found inside the 'PET' folder.

3. The instruction-templates created are present in the 'DINO/task_specs' folder. All the auto generated datasets from DINO are stored in the 'DINO/output' folder.

4. All the notebooks of BERT model trained on DINO datasets are present in 'BERT_NLI_Data_Selection' folder.

5. The datsets used for BERT NLI modelling are present inside 'BERT' folder.

