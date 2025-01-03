# NER and Classification with LLMs

A pretrained large language model (LLM) of the BERT architecture is finetuned to do named entity recognition in the notebook 
```
    NER.ipynb    
```
and for sentence classification, i.e., determining the topic of a sequence, in the notebook 
```
    Classification.ipynb
```
using the huggingface package in both cases.

Finally, a single model is finetuned to do both tasks simulateously with a single forward pass in the notebook
```
    Multitask.ipynb
```
where the training loop is written in PyTorch. 

For more details and a discussion of the results, view the `LLM_report.pdf`.
