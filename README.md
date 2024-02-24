# Colorización de Videos utilizando OpenVINO y OpenCV

En este proyecto de colorización de videos, se utilizó una combinación de herramientas de procesamiento de imágenes y aprendizaje profundo para agregar color a videos en blanco y negro. A continuación, se detallan los pasos realizados en el proyecto:

# 1. Recopilación y Preparación de Datos:
     Se seleccionaron dos videos para la colorización: un partido de fútbol entre Chile y Yugoslavia del Mundial de 1962 (baja calidad) y la película chilena muda "El Húsar de la Muerte" de 1925 (mediana calidad). Ambos videos estaban en blanco y negro. Se utilizó OpenCV para leer y procesar los videos.

# 2. Procesamiento de Video:
     Se implementaron mejoras en la calidad visual de los videos mediante diferentes técnicas:

     Aplicación de superresolución al frame.
     Corrección de contraste.
     Reducción de ruido.
     Colorización de Videos:
     Se utilizaron modelos pre-entrenados de OpenVINO para la colorización de los videos, específicamente los modelos colorization-v2 y colorization-siggraph. Se realizó una comparación entre ambos modelos para evaluar su rendimiento y calidad de colorización.

# 3. Aplicación de Modelos de Colorización:
     Se aplicaron los modelos pre-entrenados de OpenVINO a cada frame de los videos seleccionados, generando así los videos colorizados finales.

# 4. Evaluación y Comparación de Resultados:
     Se evaluaron visualmente los videos colorizados para verificar la calidad de la colorización y comparar los resultados obtenidos con cada modelo.

# 5. Visualización y Análisis de los Resultados:
     Se crearon visualizaciones detalladas para presentar los videos colorizados junto con los videos originales en blanco y negro. Se destacaron las diferencias en la calidad de colorización entre los modelos utilizados.
[Video 1: Partido Chile vs Yugoslavia (1962)](videos_chile_62.mp4)

[Video 2: El húsar de la muerte (1925)](videos_husar_de_la_muerte.mp4)

Este proyecto representa un avance significativo en la aplicación de técnicas de procesamiento de imágenes y aprendizaje profundo para la colorización de videos en blanco y negro, proporcionando nuevas perspectivas y posibilidades en la restauración y preservación de contenido audiovisual histórico.
