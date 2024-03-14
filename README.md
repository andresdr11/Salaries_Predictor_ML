# Predicción de Salario - Proyecto de Machine Learning
Este repositorio contiene un proyecto de Machine Learning para predecir el salario de una persona en función de sus características utilizando el conjunto de datos del censo adulto.

## Descripción del Problema
El objetivo es predecir si una persona tiene un salario anual de más de 50 mil dólares o no, basándose en características como la edad, educación, ocupación, etc.

## Conjunto de Datos
El conjunto de datos utilizado es el conjunto de datos del censo adulto, obtenido de la University of California Irvine (UCI). Contiene un total de 14 variables predictoras y una variable continua a predecir. El número total de muestras es de 32561 personas.

## Librerías Utilizadas
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

## Resultados
El modelo de regresión logística optimizado alcanzó un área bajo la curva ROC (AUC) de 0.86 en el conjunto de prueba, lo que indica un buen rendimiento en la clasificación de salarios.

### Notas Adicionales
* El preprocesamiento de datos incluye manejo de valores faltantes, codificación de variables categóricas, estandarización de datos, entre otros.
* Se realizaron visualizaciones como boxplots, histogramas y matrices de correlación para comprender mejor las relaciones entre las variables.
