# A Study on Localization of Knowledge in Language Models
A Study on Localization of Knowledge in Language Models

For causal mediation analysis, see knowledge_editing/notebooks folder. For knowledge editing, see knowledge_editing/example_{}.ipynb. Knowledge editing results are available upon request (the accumulated json files are too big).

For word embedding perturbation test, please rerun the experiments in embedding-perturbation.ipynb. 

For the punctuation knowledge neurons experiments, please rerun the experiments in punctuation-knowledge-neurons.ipynb. 

For Experiments of Knowledge Neuron on GPT-2 and BERT, please rerun the experiments in kn.ipynb. Note that the duration of the whole experiment on GPT-2 exceeds the longest running time in Kaggle. We recommend you run the experiment in parts. To change the model from GPT to BERT, just modify the `model_type` in the code from gpt2 to bert.

The context-PARAREL dataset could be created in runtime easily using the function `pararel_expanded` inside the kn.ipynb file. Note the dataset has slight difference for gpt and bert. You have to choose the model_type when deploying the dataset. 

Note: To run all the ipy-notebook files, we recommend to use at least Nvidia Tesla P100 GPU. The requirements for the certain experiments are included in the files. 
      Our knowledge neuron implementations are based on the reproduction work of [EleutherAI](https://github.com/EleutherAI/knowledge-neurons) with our own modifications and improvements. 


This is the course project repository for COMP 599 (Natural Language Understanding with Deep Learning) Fall 2022 at McGill University. 

Report title: A Study on Localization of Knowledge in Language Models

Developers: Steve Wen @SedimentaryRockStar, Mark Bai @rdh1115. Mentor: Zichao Li
