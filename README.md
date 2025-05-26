# Taller_trabajo_grupal
Instrucciones trabajo grupal SICSS Bogota 2025
Elaborado por Oscar Javier Maldonado

## 📋 Objetivos generales

1. **Dominar pipelines de PLN** en Python (spaCy, NLTK, Hugging Face Transformers) y R (tidytext, quanteda).  
2. **Comparar** resultados de análisis de sentimientos, modelado de tópicos y extracción de entidades entre ambos lenguajes.  
3. **Interpretar** patrones discursivos y dinámicas sociales digitales aplicando marcos sociológicos (polarización, representaciones sociales, dinámicas de red).  
4. **Comunicar** hallazgos en un informe escrito y en una presentación breve.

## 🔢 Distribución de grupos y temas

| Grupo | Tema / Dataset |
|:-----:|:--------------|
| **1** | **Planes de desarrollo Antioquia 2020–2023** Textos oficiales (resúmenes ejecutivos, pronunciamientos municipales). |
| **2** | **Brutalidad policial en Colombia**  Tweets recolectados durante el estallido social (nov 2019–jun 2020). |
| **3** | **Vacuna COVID**  Publicaciones de Facebook/Instagram extraídas con Crowdtangle (ene–dic 2021). |
| **4** | **Rappi y el Día de la Madre**  Tweets 1–15 may 2020: colapsos de entregas y percepciones ciudadanas. |

## 🛠 Herramientas y librerías

- **Python**  
  - Preprocesamiento: `spaCy`, `NLTK`  
  - Sentimientos: Transformers (`nlptown/bert-base-multilingual-uncased-sentiment`), `TextBlob`  
  - Tópicos: `Gensim` (LDA), `BERTopic`  
  - Embeddings y clustering: `Sentence-BERT`, `UMAP` + `HDBSCAN`  
  - NER: `spaCy`, `Stanza`  
  - Visualización: `Matplotlib`, `Plotly`, `PyLDAvis`  

- **R / RStudio**  
  - Preprocesamiento: `tidytext`, `textclean`  
  - Sentimientos: `syuzhet`, `sentimentr`  
  - Tópicos: `topicmodels` (LDA), `stm` (Structural Topic Models)  
  - Embeddings: `text2vec` + `uwot` + `dbscan`  
  - NER: `cleanNLP` (spaCy backend)  
  - Visualización: `ggplot2`, `LDAvis`, `igraph` / `ggraph`  

## 🗓 Cronograma (3–6 de junio de 2025)

| Día | Fecha | Actividad |
|:---:|:------:|:-----------|
| **Martes 3** | 3 de junio de 2025 | • Configuración de entornos (conda/RStudio).<br>• Introducción a cada dataset y exploración inicial. |
| **Miércoles 4** | 4 de junio de 2025 | • Preprocesamiento de texto:<br>  – Python: tokenización, lematización.<br>  – R: `unnest_tokens()`, limpieza. |
| **Jueves 5** | 5 de junio de 2025 | • Análisis de sentimientos y extracción de entidades:<br>  – Ejecutar en paralelo en Python y en R.<br>  – Comparar resultados. |
| **Viernes 6** | 6 de junio de 2025 | • Modelado de tópicos y embeddings:<br>  – Ajustar LDA en Python y STM en R.<br>  – Visualizaciones interactivas.<br>• Preparación de entregables. |

## 🎯 Entregables

1. **Informe (PDF/Markdown, 3–4 páginas)**  
   - Descripción breve del dataset y de los pasos en Python y R.  
   - Hallazgos clave: tópicos, sentimientos, entidades, patrones de polarización y representaciones sociales.  
   - Gráficos comparativos (Python vs. R).  
   - Reflexión metodológica: ventajas, limitaciones y validación cruzada.  

2. **Presentación** (5 diapositivas máx., 5 min)  
   - Contexto y pregunta sociodigital.  
   - Resultados principales (una diapositiva por técnica).  
   - Implicaciones sociológicas.  
   - Conclusiones y preguntas abiertas.  

3. **Código fuente**  
   - Carpeta con notebooks (`.ipynb`) y scripts R (`.R`) documentados.  
   - `requirements.txt` y `sessionInfo()` de R para reproducibilidad.  

## 💡 Preguntas de reflexión

1. **Dinámica temporal**  
   - ¿Cómo evolucionan los tópicos y el sentimiento a lo largo del periodo de análisis?  
2. **Comparación Python vs. R**  
   - ¿Qué diferencias prácticas observas en la limpieza, modelado y visualización?  
3. **Limitaciones y validación**  
   - ¿Cómo validarías tus hallazgos con muestreo manual o técnicas mixtas?  

### Preguntas sociológicas

- **Polarización**  
  - ¿Qué indicadores lingüísticos o de red muestran segmentos claramente enfrentados?  
- **Representaciones sociales**  
  - ¿Qué narrativas hegemónicas emergen y cómo varían por región o demografía?  
- **Dinámicas digitales**  
  - ¿Cómo influyen algoritmos de plataforma y formatos de publicación en la viralización y en la construcción de sentido?  
- **Actores y redes**  
  - ¿Qué rol juegan influenciadores, medios tradicionales o cuentas institucionales en la difusión de discursos clave?  

