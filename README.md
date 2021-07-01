# Análisis de sentimiento financiero
Objetivo: Desarrollar un modelo predictivo de análisis de sentimiento en el contexto financiero

# Modelos:

FinBERT es un modelo de PNL previamente entrenado para analizar el sentimiento del texto financiero. Se construye mediante la entrenamiento adicional del modelo de lenguaje BERT en el dominio de las finanzas, utilizando un gran corpus financiero y, por lo tanto, ajustándolo para la clasificación del sentimiento financiero. Para obtener más información, consulte FinBERT: Análisis de sentimiento financiero con modelos lingüísticos previamente entrenados.

Nota importante: la implementación de FinBERT se basa en la biblioteca pytorch_pretrained_bert de Hugging Face y su implementación de BERT para tareas de clasificación. pytorch_pretrained_bert es una versión anterior de la biblioteca de transformers.

# Datasets:

Hay dos conjuntos de datos utilizados para FinBERT:

El entrenamiento de modelamiento de lenguaje se realiza en un subconjunto del conjunto de datos Reuters TRC2. Este conjunto de datos no es público, pero los investigadores pueden solicitar acceso aquí.

Para el análisis de sentimiento, se utiliza el Financial PhraseBank de Malo et al. (2014). Este conjunto de datos se puede descargar desde este enlace. Si desea entrenar el modelo en el mismo conjunto de datos, después de descargarlo, se debe crear tres archivos en la carpeta data/sentiment_data como train.csv, validation.csv, test.csv

## Artículo de Referencia:
- Repositorio GitHub clonado para el proyecto: https://github.com/nelsimelgarejo/DL

- Repositorio GitHub original del artículo de referencia: https://github.com/ProsusAI/finBERT

## Enlaces del artículo de referencia:

- https://paperswithcode.com/paper/finbert-financial-sentiment-analysis-with-pre

- https://arxiv.org/pdf/1908.10063v1.pdf
