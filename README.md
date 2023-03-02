# Clasificación de imágenes perros y gatos

El proyecto es basado en crear y entrenar un modelo de inteligencia artificial con Python y Tensorflow, el cual ha sido exportado a los archivos "json" y "bin". Se puede utilizar en el celular, con solo apuntar la cámara al perro o gato que quieres clasificar (puede ser una imagen de la computadora, una foto, o uno de verdad), lo hace todo en el explorador utilizando Tensorflow.js.

## Cómo utilizarlo

### Utilizarlo en un celular

Si quieres abrirlo en tu celular,puedes ingresar al link de la página, la cual, ya aloja el modelo predictivo.
- Se puede entrar desde cualquier navegador, habilitando el uso de la cámara, para el proceso de entrada de imágenes y obtener la salida(perro o gato).
- Desde cualquier red.
- Se puede abrir un explorador en tu celular e ingresar a la url.

### Uso
Una vez en la página, puedes dar clic en el botón de "Cambiar camara" para utilizar la cámara delantera o trasera del celular. Solo apunta la cámara a un perro o gato, y abajo te aparecerá la predicción. No se puede considerar este clasificador como el mejor, ya que si no logra clasificar de manera precisa, aún tiene margen de mejora.

## Dato
- Para la clasificación del modelo, se utilizaron tres modelos de Keras: Uno de densal y dos convolucionales(uno añadiendo u dropout). luego del análisis de los tres modelos, se experimentó con datos aumentados a los tres modelos, para lo cual, se consideró el modelo convolucional sin dropout (CNN_AD).
