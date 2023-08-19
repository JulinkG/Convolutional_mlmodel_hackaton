# PicData Modelo de redes convolucionales para verificación

Este código está escrito para el hackaton #Hackcorruption y se divide en dos partes fundamentales. La primera está destinada a el entrenamiento de un modelo de indentificación de imágenes sobre el cuál se trabajará la propuesta de solución a nuestro problema de estudio y la segunda parte está destinada a un despliegue del modelo en un servidor local utilizable en dispositivos móviles.

## Propuesta de entrenamiento

Los modelos utilizados se dividen en momentos, en un primer momento son identificación de imágenes por redes convolucionales y no convolucionales, en un segundo momento se utilizarán los mismos modelos pero con una base de datos aumentada. De esta manera podemos descartar y mejorar el rendimiento de los modelos identificados.

Por los resultados obtenidos, el modelo convolucional aumentado es el elegido para el despliegue de este escenario. (Verificar tablas con tensorboard dentro del scrip)

Dentro de la primera parte titulada *Entrenamiento* se puede encontrar paso a paso el seguimiento de las necesidades del entrenamiento y la explicación de la base de datos utilizada dentro del mismo. En el segundo apartado se puede encontrar el diseño web de la cámara asociada al modelo, la cuál se desplegará de momento por un servidor local expandido por NGROK.
