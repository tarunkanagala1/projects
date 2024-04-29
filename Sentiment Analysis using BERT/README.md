
# Sentiment Analysis using BERT

This project makes use of Bi-directional Encoder Representations from Transformers for Sentiment Analysis. BERT is a powerful pre-trained Language model which is good at understanding context and meaning of the words.

We take the reviews of the restaurant and feed it a model and make the Sentiment of the reviews of the particular restaurant.With the help of fine tuning the base model we can get more  accurate results.
I had taken my favourite restaurantnamed "UKI" based in Los Angeles but we can select any other as well.


# Generating a Hugging Face Token

1) Log in to your Hugging Face profile and under the profile and select access tokens.

2) Create a new access token with a name "HF_TOKEN" as copy it to your python notebook.

3) Create a secret in the Google Colab folder with same name as HF_TOKEN and paste access key to value field.




## Installation



```bash
from transformers import AutoTokenizer, AutoModelForSequenceClassification
import torch
import requests
from sklearn.metrics import *
from bs4 import BeautifulSoup
import re
```
    