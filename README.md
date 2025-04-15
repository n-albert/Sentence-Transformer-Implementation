# Status
At the moment, this repository is being updated. The Exploratory Data Analysis notebook is the only one that has reliable content.
I am currently working on updating the notebook that actually runs the code for classification, named entity recognition and other concepts this repository hopes to explore.
I also am working making these notebooks able to run on computers without Graphics Cards (GPUs), since there are library import issues with torch, transformers, and some other libraries that need access to CUDA related libraries.

The "Transformers and Multi-task Learning Notebook" currently runs when imported on Google Colab, even though the notebook needs to be updated. When the notebook is run on a computer without GPU availability, you may run into import issues with the transformers and sentence_transformers library:
![image](https://github.com/user-attachments/assets/55e16fd6-80d2-4371-9e60-e78f1ebde230)

This will be a work in progress item. Thank you.

# To Do Items:
- Implement confusion matrix metrics for the "Finetuning_a_Sentence_Transformer_model_for_Text_Classification" notebook.
- Implement another version for the "Finetuning_a_Sentence_Transformer_model_for_Text_Classification" notebook, where some layers of the model are frozen, but the others are not and able to be finetuned.

# Sentence-Transformer-Implementation
A Sentence Transformer implementation using sBERT's sentence_transformers and Huggingface's transformers library

This repository contains one notebook that could be run from start to finish, without issue. 

I included a training loop for "sentiment analysis/sentence classification", which will require the use of a GPU on a Google Colab notebook environment.

No training loop was developed or provided for the "named entity recognition" task due to time constraints. A pretrained model, however, was successfully loaded and was able to do a forward pass with satisfactory results.

To show how a GPU may be selected, I've included the below two screenshots.


![sentence-transformer-exercise-change-runtype-type](https://github.com/user-attachments/assets/1e734c07-95b4-45b8-a25d-3834a15c8904)

![sentence-transformer-exercise-change-runtype-type-selection-popup-window-overlay](https://github.com/user-attachments/assets/a5e2076e-3cb9-4b13-9823-ceccdb6753db)
