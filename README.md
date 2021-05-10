# Desafío 4: Clasificador de ropa

Juan está interesado en el mercado de la venta de ropa en línea. Su revolucionaria idea implica usar una inteligencia artificial que recomiende ropa que se parezca. 
Para poder realizar esto, Juan deberá primero clasificar los tipos de ropa. Para ello, se les ha pedido a los alumnos que implementen una inteligencia artificial que haga el trabajo.

En el repositorio se encuentra un Dataset (formato .csv) con imágenes en escala de grises que representan distintos tipos de ropas, junto con su etiqueta correspondiente. Para este trabajo se deberá:

- Leer el Dataset.
- Implementar (sin uso de librerías que lo hagan) y entrenar un perceptrón multicapa para la tarea de clasificación. Para esto se debe dividir los datos en entrenamiento y pruebas (70/30 sugerido).
- Con los datos de prueba, calcule la precisión (accuracy) de la predicción.


## Datos Adicionales

**"label"** : etiqueta de la imagen. tiene 10 clases:

        0 - Polera
        1 - Pantalón
        2 - sweater
        3 - Vestido
        4 - Saco
        5 - Sandalia
        6 - Camisa
        7 - Zapatilla
        8 - Bolso/cartera
        9 - Bota

**"pixel[1...784]"**: Pixel n de la imagen, el valor es entre 0 y 1, siendo 0 completamente negro y 1 completamente blanco. Cada imagen es de 28x28, por lo que se tiene un vector de 784 pixeles.
