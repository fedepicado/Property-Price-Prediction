# Análisis de Transformación de Datos para la Predicción de Precios en CABA

## Descripción del Proyecto
En el marco de la materia Data Mining, se desarrolló un trabajo práctico cuyo objetivo es realizar un análisis de transformación de datos para predecir los precios de cocheras, departamentos y casas en la Ciudad Autónoma de Buenos Aires (CABA), Argentina, utilizando Random Forest. La idea principal de este ejercicio es enfocarse en la preparación y transformación de los datos sin modificar demasiado los parametros del modelo, y observar como el efecto de los mismos puede mejorar o empeorar nuestro score. Como metodo de evaluacion se creó una competencia en Kaggle (https://www.kaggle.com/competitions/fcen-dm-2024-prediccin-precio-de-propiedades) donde fuimos subiendo nuestros resultados. En dicha competencia podran encontrar los datos que se usaron para entrenar y predecir el modelo.

## Metodología

### 1. Análisis Exploratorio de Datos
- **Visualización de Datos**: Uso de gráficos para entender mejor la distribución de los datos y la relación entre las variables.
- **Detección de Outliers**: Identificación y tratamiento de valores atípicos que puedan distorsionar el modelo.

### 2. Limpieza de Datos

- **Tratamiento de Valores Faltantes**: Imputación de valores faltantes mediante técnicas como la media, mediana, MICE e imputación basada en KNN.
- **Eliminación de Duplicados**: Garantizar que no haya registros duplicados en el dataset.
- **Corrección de Errores**: Revisión y corrección de posibles errores tipográficos o valores fuera de rango.

### 3. Ingeniería de Características
- **Creación de Nuevas Variables**:: Generación de nuevas variables a partir de las existentes que puedan tener una relación significativa con el precio.
- **Codificación de Variables Categóricas**: Transformación de variables categóricas en variables dummy.
- **Transformaciones Logarítmicas**: Aplicación de transformaciones logarítmicas a variables con distribuciones sesgadas.

## Resultados y Conclusiones.
Los resultados y las mejoras obtenidas a través de las distintas transformaciones de datos se fue documentando a medida que avance en la competencia. Este enfoque me permitio observar de manera clara cómo la calidad y preparación de los datos pueden influir significativamente en el rendimiento de los modelos predictivos.
