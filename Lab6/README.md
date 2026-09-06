# Laboratorio 6 – Análisis de comentarios de YouTube

Análisis de sentimiento y de redes (dataset bipartito autor–video) a partir de comentarios de videos de YouTube en español.

## Instalación

```bash
pip install pandas numpy matplotlib seaborn networkx scipy \
    nltk spacy emoji pysentimiento wordcloud
python -m spacy download es_core_news_sm
```

Los stopwords de NLTK y `pysentimiento` se descargan automáticamente al ejecutar el notebook.

## Ejecución

Abre y ejecuta el notebook en orden:

```bash
jupyter notebook Laboratorio6.ipynb
```

Cada celda descarga sus datos (CSVs) en `data/` y genera las figuras de salida; no se requiere configuración previa.