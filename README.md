# meta-babi-bot
###Build a Question and Answer ChatBot Capable of Lateral Thinking

![image](https://user-images.githubusercontent.com/59450769/184835274-ba3b539c-ded1-4533-a6ce-1eb0e883aea9.png)
![image](https://user-images.githubusercontent.com/59450769/184835366-ad44ddd3-3acf-4fe1-8f5b-1628684632ae.png)

LSTM Architecture:

![image](https://user-images.githubusercontent.com/59450769/184835598-dbf2c662-dda5-452f-9253-715ebf38b434.png)


![image](https://user-images.githubusercontent.com/59450769/184809393-694bb2dd-72e4-4fb6-bb4c-a7227f23b89e.png)

### Model Metrics: 

![image](https://user-images.githubusercontent.com/59450769/184835866-a15ffba9-c84b-4ace-836e-dbcd97ce42db.png)

### Imports:
*   numpy
*   pickle
*   from keras.preprocessing.sequence import pad_sequences 
*   from keras.preprocessing.text import Tokenizer
*   from keras.models import Sequential, Model 
*   from keras.layers.embeddings import Embedding
*   from keras.layers import Input, Activation, Dense, Permute, Dropout 
*   from keras.layers import add, dot, concatenate 
*   from keras.layers import LSTM
*   import matplotlib.pyplot as plt
*   %matplotlib inline (for jupyter notebooks)

### Data used in project is located in TextFiles folder:
*   test_qa.txt
*   train_qa.txt

### Resources:

*   [End-to-End Memory Networks](https://arxiv.org/pdf/1503.08895.pdf)
