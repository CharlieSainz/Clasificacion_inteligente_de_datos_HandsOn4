# Clasificacion_inteligente_de_datos_HandsOn4

Tutorial de Clasificacion con Logistic Regression
Este repositorio contiene un tutorial sencillo sobre la tecnica de clasificacion Logistic Regression usando Python y la libreria scikit-learn. El objetivo es explicar de forma clara los fundamentos, el modelo matematico, las funciones principales de la libreria y la implementacion completa dentro de un notebook de Google Colab.

1. Fundamentos de la tecnica
La Logistic Regression es un modelo que sirve para clasificar datos en dos clases. En lugar de predecir valores numericos, calcula la probabilidad de que un patron pertenezca a la clase 1. Esto lo hace utilizando la funcion sigmoide, que convierte los valores en numeros entre 0 y 1.

2. Modelo matematico
El modelo calcula la probabilidad de la clase positiva:

P(y = 1 | x) = 1 / (1 + e^-(b0 + b1x1 + ... + bnxn))

La decision final se hace asi:
Si la probabilidad es mayor a 0.5 → clase 1.
Si es menor → clase 0.

3. Libreria scikit-learn
Para este tutorial se usan las siguientes clases y funciones:
LogisticRegression: entrena el modelo de clasificacion.
train_test_split: divide el dataset en entrenamiento y prueba.
StandardScaler: normaliza los datos.
confusion_matrix: genera la matriz de confusion.
accuracy_score: calcula el accuracy del modelo.

4. Como ejecutar el notebook
Abrir Google Colab.
Copiar y pegar el codigo del archivo .ipynb o importar el notebook desde este repositorio.
Ejecutar las celdas una por una.
Ver los resultados de la clasificacion.

Referencias
Scikit-Learn. Logistic Regression. https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression
Breast Cancer Dataset. https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset
Hastie, Tibshirani y Friedman. The Elements of Statistical Learning. Springer.
