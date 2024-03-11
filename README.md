# Valores-faltantes-KNNImputer
En este proyecto, utilicé el KNN Imputer de la biblioteca scikit-learn para imputar valores faltantes en un conjunto de datos. El objetivo era abordar la falta de valores en algunas características de los datos.

Exploración de los datos:

Se cargó un conjunto de datos que contenía valores faltantes en varias características.
Las características relevantes se seleccionaron para el proceso de imputación.

Imputación de valores faltantes:

Se importó la clase KNNImputer de la biblioteca sklearn.impute.
Se crearon dos instancias de KNNImputer con diferentes configuraciones: una con weights='uniform' y otra con weights='distance'.
Se ajustaron los imputadores a los datos utilizando el método fit_transform.
Se generaron dos conjuntos de datos imputados, uno para cada configuración de pesos.

Gráficos de dispersión comparativos:

Se generan dos gráficos de dispersión lado a lado para comparar los datos originales con los datos después de la imputación.
Cada gráfico muestra la relación entre dos variables: "Area" en el eje x y "Valor" en el eje y.
Identificación de datos imputados:


