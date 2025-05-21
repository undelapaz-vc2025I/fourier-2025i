# Procesamiento de Imágenes con Transformada de Fourier

### Descripción
Este repositorio contiene un notebook de Jupyter que demuestra la aplicación de la Transformada de Fourier para el procesamiento de imágenes, específicamente implementando un filtro paso bajo en el dominio de la frecuencia. El ejemplo utiliza la imagen clásica "cameraman" para mostrar cómo la Transformada de Fourier puede ser utilizada para el filtrado de imágenes.

### Características
- Implementación de la Transformada de Fourier 2D usando NumPy
- Filtrado paso bajo en el dominio de la frecuencia
- Visualización de la imagen original, espectro de frecuencia y resultado filtrado
- Notebook de Jupyter interactivo con explicaciones paso a paso

### Requisitos
- Python 3.9+
- NumPy
- OpenCV (cv2)
- Matplotlib
- Jupyter Notebook

### Instalación
1. Clonar este repositorio:
```bash
git clone https://github.com/yourusername/fourier-2025i.git
cd fourier-2025i
```

2. Instalar los paquetes requeridos:
```bash
pip install numpy opencv-python matplotlib jupyter
```

### Uso
1. Abrir el notebook de Jupyter:
```bash
jupyter notebook Transformada_Fourier_Imagenes.ipynb
```

2. Ejecutar las celdas secuencialmente para ver el proceso de la Transformada de Fourier y sus efectos en la imagen.

### Resultados
El notebook demuestra:
- Imagen original en escala de grises
- Visualización del espectro de frecuencia
- Imagen filtrada después de aplicar un filtro paso bajo