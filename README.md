# Bengali-AI

Currently, natural language processing (NLP) research is developing rapidly due to the rise of artificial intelligence (AI). One of the key topics of NLP is optical character recognition (OCR). To build an OCR in Bengali language, digit classification provides a convenient starting point. We have accumulated a large dataset (85,000+) of Bengali digits (NumtaDB) which can be used by researchers for benchmarking their algorithm.

Dataset - https://www.kaggle.com/BengaliAI/numta/

Here, my goal is to correctly identify digits from NumtaDB and I have tried to do so with a LeNet like Convolutional Neural Network Architecture and Adam Optimizer. Training time took 2 hours on CPU. Devset accuracy of around 98%. 

I have included the pretrained weights and the model architecture in model_filter.h5 file. The model pipeline can be visualized using Model Pipeline.png image. Also, there's a demo of the model in use at notebook Production.ipynb
