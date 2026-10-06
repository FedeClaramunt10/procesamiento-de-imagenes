# Procesamiento de Imágenes

Ejercicios de la materia Procesamiento de Imágenes de la Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial, con OpenCV y NumPy.

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| [Ejercicio1_Segmentacion_Arroces.ipynb](notebooks/Ejercicio1_Segmentacion_Arroces.ipynb) | Introducción al procesamiento de imágenes: segmentación de granos de arroz (canales de color, binarización, operaciones morfológicas básicas). |
| [Ejercicio2_Segmentacion_Color.ipynb](notebooks/Ejercicio2_Segmentacion_Color.ipynb) | Segmentación por color: análisis de imágenes en BGR/HSV, extracción de regiones y visualización con OpenCV. |
| [IMG01_RiceSegmentation_Resuelto_Claramunt.ipynb](notebooks/IMG01_RiceSegmentation_Resuelto_Claramunt.ipynb) | IMG01 resuelto: segmentación de granos de arroz. |
| [clase3/](notebooks/clase3/) | Material de la clase 3 (fundamentos de imagen). |
| [clase4/](notebooks/clase4/) | Material de la clase 4. |
| [clase5/](notebooks/clase5/) | Material de la clase 5. |
| [clase7/](notebooks/clase7/) | Material de la clase 7. |

### `datos/`

Imágenes locales usadas por los ejercicios y las clases.

Todos los notebooks se publican ejecutados, con sus salidas y gráficos, y se pueden leer directamente en GitHub.

## Datos

Las imágenes de entrada (`onerice.bmp`, `rices.png`, `flowers.jpg`) se descargan dentro de los propios notebooks con `wget` desde repositorios públicos: no hace falta descargar nada aparte.

## Cómo ejecutarlos

Fueron creados en Google Colab (usan utilidades de `google.colab`):

```python
# Abrir en Google Colab subiendo el .ipynb, o ejecutar localmente
# instalando OpenCV y reemplazando cv2_imshow por plt.imshow
pip install opencv-python numpy matplotlib
```

## Temas cubiertos

- Lectura y representación de imágenes (OpenCV/NumPy)
- Canales de color BGR, escala de grises y espacio HSV
- Binarización y umbralización
- Operaciones morfológicas (erosión, dilatación, apertura, cierre)
- Segmentación de regiones y extracción de características

## Licencia

MIT
