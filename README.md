Análisis de Reseñas de Yelp con NLP
Descripción
Proyecto que analiza reseñas de Yelp con NLP para clasificar sentimientos, extraer palabras clave, identificar negocios destacados y explorar tópicos y entidades.

Métodos
Preprocesamiento: Limpieza de datos, conversión de strings a listas, manejo de fechas.

Sentimientos: Clasificación con TARGET (POS/NEG), extracción de adjetivos (POS tagging), nubes de palabras.

Negocios: Conteo de reseñas por business_id y TARGET, análisis de reseñas antiguas con date.

Palabras clave: Extracción con KeyBERT (comida, servicio).

NER: Extracción de entidades con spaCy.

Tópicos: LDA con gensim (parcial).

Programas y Librerías
Python 3.8

Visual Studio Code, Git, GitHub

Librerías:
Pandas: Manejo de datos.

spaCy: POS tagging, NER (en_core_web_sm).

KeyBERT: Palabras clave.

WordCloud, Matplotlib: Visualización.

gensim: LDA.

NumPy, SciPy: Cálculos.

ast, re: Procesamiento de texto.

