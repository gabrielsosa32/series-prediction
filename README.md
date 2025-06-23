Proyecto: Predicción de Series Temporales con LSTM
Descripción
Este proyecto muestra un ejemplo básico de predicción de series temporales utilizando una red neuronal LSTM (Long Short-Term Memory).
Se genera una serie artificial (senoidal con ruido), se prepara para el modelo LSTM, se entrena y se visualizan las predicciones.

Contenido
serie_temporal_lstm.ipynb: Notebook con el código completo para generar datos, entrenar el modelo LSTM y visualizar resultados.

Cómo usar
Clonar el repositorio.

Crear un entorno virtual e instalar las dependencias necesarias con:

nginx
Copiar
Editar
pip install -r requirements.txt
Ejecutar el notebook serie_temporal_lstm.ipynb en Jupyter o VS Code para ver el ejemplo.

Librerías principales usadas
numpy

pandas

matplotlib

tensorflow (keras)

scikit-learn

Detalles técnicos
Se genera una serie temporal sintética (seno con ruido).

Se normalizan los datos con MinMaxScaler.

Se crean secuencias con ventana deslizante para alimentar el LSTM.

Se entrena un modelo LSTM simple con 50 neuronas y función de activación ReLU.

Se evalúa el modelo y se visualizan predicciones vs valores reales.

