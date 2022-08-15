### onlyBERT_finetuning_file1.ipynb
This file is used to finetune the transformer-based bert model wihch is pre-trained on a large corpus of English data in a self-supervised fashion. Once we finetune the model, based on best validation macro-f1 score we save the model in "BERTBASED" folder locally which can be used further.


### BERT & CodeBERTEmbedding Generation_file2.ipynb
This file is used to process the text & code. Further, we get the text-embebbedding and code-embedding using the saved model in BERTBASED" folder and usinng code-bert model.



### BERT_and_CodeBERT_file3.ipynb

This file is used to train a fusion-based model considering the text-embebbedding and code-embedding generated in the previous step.