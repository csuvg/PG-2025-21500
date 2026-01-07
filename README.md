# Identificación de espacio sin aprovechar en imágenes aéreas de surcos de cultivos a través de algoritmos de detección de líneas.
Proyecto de Graduación 2025 - Adrián Ricardo Flores Trujillo, Carnet: 21500

Como se evidencia en el [trabajo escrito](docs/informe_final.pdf), el presente trabajo desarrolla un método automatizado para la identificación de fallos en surcos de cultivos a partir de imágenes aéreas. El objetivo principal fue obtener métricas de aprovechamiento del espacio de siembra mediante la detección de líneas y la cuantificación de espacios vacíos. Para ello, se diseñó un procedimiento que combina técnicas de procesamiento digital de imágenes y análisis geométrico, aplicando distintas transformaciones para la detección de surcos y un algoritmo de evaluación de discontinuidades a lo largo de cada línea. A partir de estas detecciones, se calcularon métricas físicas basadas en los metadatos espaciales de las imágenes, lo que permitió cuantificar con precisión la extensión de los fallos de cultivo.

## **Tecnologías Utilizadas**

- Python
- Jupyter
- cv2
- sklearn
- scipy

## **Requisitos Previos e Instalación**

Antes de ejecutar el notebook, es necesario contar con lo siguiente:

- Python 3.11 o superior
- pip
- Jupyter Notebook (Ejecutar `pip install notebook` en caso no esté instalado)

Con estos elementos, es posible proceder a la instalación de dependencias. Este proyecto utiliza varias librerías externas definidas en el archivo `requirements.txt`. Para instalarlas, seguir los pasos:

1. Clonar o descargar el repositorio del proyecto
2. Navegar a [/src](/src)
3. Ejecutar el comando `pip install -r requirements.txt`

## **Ejecución del Notebook**

Una vez instaladas las dependencias, iniciar Jupyter con `jupyter notebook`, lo cual inicia un servicio local para ejecutar el notebook. Alternativamente, es posible subir el notebook a Google Colab. El anterior es un servicio de Google para crear y ejecutar Jupyter Notebooks en línea, y ya cuenta con todas las librerias instaladas de antemano.

Posteriormente, **es necesario cambiar la fuente de las imágenes**. El notebook actual obtiene las imágenes de Google Drive del usuario, pero, de no contar con esto, se debe modificar la siguiente celda para que extraiga las imágenes de la fuente correcta. Para más detalles sobre esta celda, ver [el video demostrativo](/demo/demo.mp4).

<img width="1495" height="263" alt="image" src="https://github.com/user-attachments/assets/d1bb0448-74fe-4689-8b91-76f4f6b4dc5c" />
