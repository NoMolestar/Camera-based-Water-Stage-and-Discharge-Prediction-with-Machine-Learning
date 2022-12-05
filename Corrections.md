
# Correcciones Generales

En este archivo describirémos las correcciones principales que implementamos al proyecto con base en los profesores de módulo.

## Correcciones Modulo PLN

El profesor Rubén nos mostró al principio cómo podríamos distinguir entre imagenes que nos funcionen y las que no. Primero la intentamos con RGB, pero el agua tenía diferentes colores. Después nos recomendó controlar la variable de la luz, pero dependíamos de utilizar OpenCV. Decidimos cambiar de opción para no complicarnos el proyecto, dado el poco tiempo que teníamos. Al final, nos recomendó desarrollar una red que clasificara entre imagenes funcionales y las que no.

Después de haber implementado la red, el profesor nos recomendó utilizar una matriz de confusión para evaluar el desempeño de la red. Esto nos sirvió para exponer nuestros resultados al socioformador.

## Correcciones Modulo Cloud

Solo fuimos a consultarlo una vez, y lo hicimos para ver la posiblidad de utilizar AWS. Esto debido a que los recursos disponibles para correr la red no eran suficientes para el entrenamiento del modelo. Al final, creamos la instancia como nos comentó que lo hicieramos, pero el almacenamiento no fue suficiente.

## Correcciones Modulo Deep Learning

Nos acercamos al profesor para revisar las opciones de redes convolucionales que podríamos considerar para implementar en nuestro proyecto. Revisamos entre varias opciones entre VGG16, VGG50, MobileNetV2 y ResNet101V2. Además, él nos ayudó a resolver problemas que estabamos teniendo con el tamaño de las imagenes y a reducir el batch size para que no se nos acabara la vram de la GPU.

## Correcciones Modulo Estadísticas

El profesor Omar nos recomendó evaluar nuestro proyecto con base en los residuos y no con base en R al cuadrado. Esto nos permitió tener mayor certeza de como estaba trabajando nuestro modelo. Además, utilizámos los codigos de referencia que nos dió para retirar los outliers y que aumentara su efectividad. En general, los códigos que realizámos como trabajo de clase fueron de mucha ayuda para el desarrollo de nuestro modelo de regresión.

## Correcciones Profesores Reto

Para la parte del reporte, nos hicieron comentarios sobre que debíamos explicar el porqué estamos haciendo cada cosa. Agregamos comentarios y descripciones de cada una de las etapas para que fuera más fácil entender el razonamiento que nos llevó a hacer cada cosa.

Otra parte importante también fueron las retro-alimentaciones que obtuvimos a lo largo del bloque. Estas nos ayudaron a no desviarnos del objetivo inicial que es el desarrollar nuestra idea de hipótesis para el reto. Los comentarios del profesor Gildardo fueron de mucha ayuda para definir un objetivo alcanzable y tangible. Además, nos permitió redireccionar a tiempo y enfocar nuestros esfuerzos en cumplir con nuestra idea principal del reto.

Para la parte final, el profesor Enrique nos ayudó también a resolver los últimos problemas de implementación que nos surgieron con el código. Entre ellos estuvo una situación relacionada al entrenamiento del modelo y con la matriz de confusión. En general, nos permitió alcanzar a terminar a tiempo el proyecto y a dejar claro los alcances que nos llevaron a finalizar con la investigación.

# LaTeX Report
[https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/documentation.tex](https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Report.tex)

# PDF Report
[https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Caudales.pdf](https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Investigation_Report.pdf)

# Main Model (Regressor)
[https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Code/Prediction_Regressor_BMT.ipynb](https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Code/Prediction_Regressor_BMT.ipynb)

# Clasification Model
[https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Code/Clasification_Model_BMT.ipynb](https://github.com/NoMolestar/Camera-based-Water-Stage-and-Discharge-Prediction-with-Machine-Learning/blob/main/Code/Clasification_Model_BMT.ipynb)
