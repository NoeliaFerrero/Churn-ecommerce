# Churn-ecommerce
Trabajo Práctico Módulo 1
Exploración de Datos 
Datos de Sitio de Ecommerce


Descripción:

Los datos utilizados corresponden a un sitio de e-commerce. En el mismo podemos identificar 9 columnas. 
Se forman 3 datasets distintos:
Data-Ecomm: Es la versión completa del dataset e involucra datos completos para los meses de octubre y noviembre de 2019.
Data-10-19-sampled: Es una versión reducida, de tamaño medio, del dataset. Aún quedan bastantes registros (alrededor de 20M). Sólo para el mes de octubre.
Data-10-19-smallsampled: Es una versión más pequeña. Quedan alrededor de unos 6M registros. Sólo para el mes de octubre.


Consigna:

El objetivo del Trabajo Práctico es realizar una Exploración de Datos completa sobre todo el dataset (todas las columnas).
Esta exploración involucra:
Entender el dominio del dataset.
Para esto, hacerse algunas preguntas relevantes para el negocio, como por ejemplo, ¿puede un usuario hacer compras sin acceder a ver primero el producto, o agregarlo al carrito? ¿Hay productos que sean comprados más de una vez por el mismo usuario? ¿cuántos usuarios abandonan el carrito? y otras similares. El foco es entender lo más que se pueda el negocio.
Limpieza de datos.
Involucra realizar acciones sobre todas las columnas de:
Revisión, eliminación o imputación de datos Nulos
Análisis de Nulos “no claros” (undefined? ceros? etc)
Evaluación de datos de outliers y análisis de los mismos, para decidir qué acción tomar.
Transformación de fechas, strings a numéricos y/o categórico y otras, en caso de ser necesario.
Limpieza de datos duplicados
Eliminación de datos innecesarios.
Análisis de Distribución Univariada de las columnas. 
Análisis de correlación y distribución multi-variada.
Elaboración de un proceso de tratamiento de datasets (suponga que le llega un dataset nuevo, el proceso debería realizar el mismo procesamiento realizado por Ud para obtener un dataset limpio y prolijo) Esto puede ser en un notebook o, idealmente, en código limpio (.py).

Hasta aquí iría el TP obligatorio en relación a código.

Opcionales valorados
Construcción de nuevas columnas, vinculando otras columnas. 
Construcción de columnas de información valiosa. Se me ocurre, por ejemplo, día de la semana, tasa de vistas sobre compras para el producto adquirido, etc.
Idealmente, construir columna target suponiendo predicción de compra. Para esto, se debería tomar como compra aquel usuario que vió un producto -> lo agregó al carrito -> lo compró en un mismo tiempo dado.
En caso de construir dicha columna, evaluar el balance (proporción de 1 vs proporción de 0) de la misma, y la distribución de las otras variables contra el target.
Selección de variables relevantes para predecir la compra
