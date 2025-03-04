# Neural Machine Translation Models
Neural machine translation models based on Long Short Term Memory RNNs (LSTMs) and Attention Mechanism, followed by the Transformer based model, incorporating an Encoder Decoder model architecture, is used to translate sentences (Natural Language) from German/Hindi to English. These models gave decent translations for short to moderate length sentences, with the Attention Mechanism being beneficial for moderate length sentence translations. Below is the loss curve of the model with Attention Mechanism, with the initial teacher forcer-ratio set to 0.3, and a scheduled sampling at a decay rate of 0.01. This repo consists of three different machine translation models, right from the basic Seq2Seq model up to the Transformer based model. The Transformer-based models outperform the previous 2 models for short to moderate length sentences, and also gives a decent translation for long sentences (above 30 words). 
  
![image](https://github.com/user-attachments/assets/d15c9444-5560-40f2-b28d-6f56eddd0ca3)


