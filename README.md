# Trabajo de Big Data
Este trabajo se basa en el analisis de sentimiento de procesamiento del lenguaje natural donde el análisis de sentimientos se realiza clasificando los tweets positivos de los tweets negativos mediante modelos de aprendizaje automático para clasificación, minería de texto, análisis de texto, análisis de datos y visualización de datos.

## Obtención de datos 
Los datos fueron facilitados gracias a Twitter API, en donde a través de una petición, se nos proporcionó una cuenta personal para la obtención de tweets. 

## Herramientas utilizadas
Para la elaboración de este trabajo las herramientas utilizadas fueron:
* Google Colab
* Jupyter Notebook

## Lenguaje de Programación
Python

## Librerias Utilidas
```
import tweepy
from textblob import TextBlob
from wordcloud import WordCloud, STOPWORDS
import pandas as pd
import numpy as np
import re
import matplotlib.pyplot as plt
from nltk.stem import SnowballStemmer
import datetime
import string
import nltk
```

