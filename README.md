# Brain-Tumor-Classification

Este proyecto es una réplica de un canal en YouTube (ver [enlace](https://www.youtube.com/watch?v=-zmBMxpNDqQ&t=7483s)) para entrenar mis conocimientos en la clasificación de imágenes utilizando redes neuronales profundas. El objetivo es clasificar imágenes de tumores cerebrales y no tumores utilizando un modelo de red neuronal convolucional (CNN) basado en VGG19.

## Estructura del Proyecto

El proyecto contiene los siguientes archivos y carpetas:

- `Brain_Tumor_Classification.ipynb`: Notebook de Jupyter que contiene el código para la clasificación de tumores cerebrales.
- `model.keras`: Archivo del modelo Keras guardado en formato `.keras`.
- `training_frozencnn.jpeg`: Imagen utilizada para la formación o referencia.
- `model_weights/`: Se puede descargar los weights de aqui:
  - https://drive.google.com/drive/folders/1NRUbyFtGFtVBXen4beog_zjSY5mljDed
- `tumorous_and_nontumorous/`: Carpeta que contiene datos procesados con imágenes de tumores y no tumores organizadas en subcarpetas de entrenamiento, prueba y validación.
  - `train/`: Contiene imágenes de entrenamiento clasificadas en `yes` y `no`.
  - `test/`: Contiene imágenes de prueba clasificadas en `yes` y `no`.
  - `valid/`: Contiene imágenes de validación clasificadas en `yes` y `no`.
- `augmented_data/`: Dataset aumentado que incluye imágenes de tumores y no tumores.
- `brain_tumor_dataset/`: Dataset inicial sin procesar con imágenes de tumores y no tumores.
- `.ipynb_checkpoints/`: Carpeta que contiene los checkpoints del notebook Jupyter.

## Requisitos

Para ejecutar el código y reproducir los resultados, asegúrate de tener instalados los siguientes paquetes en tu entorno de Python:

- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- imutils

Puedes instalar estos paquetes utilizando pip:

```bash
pip install tensorflow keras opencv-python-headless numpy matplotlib imutils
