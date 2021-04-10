# Classificador de Reviews IMDB
**FURB - Data Science**\
\
**Alunos:**\
Felipe Eduardo Gomes\
João Carlos Haag\
Marco Antonio Batista

**Resumo:**
> Faça um classificador que leia os reviews do arquivo "imdb.csv" e classifique sentenças fornecidas pelo usuário como "Positiva", "Neutra" e "Negativa". 

**Requisitos:**

1.   Ler o arquivo "imdb.csv";
2.   Limpar dados com stopwords , regex, stem ou lemma, (nltk ou spacy);
3.   Criar um classificador (não bayes);
4.   Calcular a acurácia do seu classificador com testes.
5.   Calcular a acurácia do classificador SIA (SentimentIntensityAnalyzer) conforme abaixo:
```
from nltk.sentiment import SentimentIntensityAnalyzer
sia = SentimentIntensityAnalyzer()
 sia.polarity_scores("Wow, NLTK is really powerful!")
{'neg': 0.0, 'neu': 0.295, 'pos': 0.705, 'compound': 0.8012}
```
6.   Comparar os resultados (acurácia) do SIA com os do seu classificador.\
Um notebook do jupyter postado em seu github (link na atividade do ava).

> Fonte dataset: https://raw.githubusercontent.com/gomesfg/chatbots/main/imdb_review_classification/imdb.csv

---

