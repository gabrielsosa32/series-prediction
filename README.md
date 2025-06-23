Proyecto: Clasificador de Noticias Fake vs Real usando LSTM y Word Embeddings
Descripción
Este proyecto implementa un modelo de deep learning para clasificar noticias en Fake o Real. Se utiliza un modelo LSTM entrenado con embeddings preentrenados (Google News Word2Vec) para capturar el contexto y las relaciones semánticas del texto.

Contenido
clasificador_texto.ipynb: Notebook con todo el análisis, preprocesamiento, construcción y entrenamiento del modelo.

modelo_entrenado.h5: Archivo del modelo entrenado guardado.

requirements.txt: Lista de librerías necesarias para ejecutar el proyecto.

Uso
Clonar este repositorio

Crear un entorno virtual (recomendado) e instalar las dependencias:

nginx
Copiar
Editar
pip install -r requirements.txt
Ejecutar el notebook para entrenar el modelo o cargar el modelo preentrenado para hacer predicciones.

Librerías principales
TensorFlow / Keras

Gensim (para cargar Word2Vec)

Pandas y NumPy

Matplotlib (para visualizaciones)

Resultados
El modelo alcanza una precisión de aproximadamente 92% en el conjunto de validación, demostrando buena capacidad para distinguir noticias falsas de reales.

