# prediccion-demanda-arboles-decision
Proyecto creado en lenguaje python, machine learning, para poder analizar datos para tomar buenas decisiones en base a este modelo de árboles de decisiones. 

# Decripcion del proyecto:

Este proyecto consiste en el desarrollo de un modelo de Machine Learning orientado a la predicción de la demanda, utilizando técnicas de análisis de datos y modelamiento predictivo.

Se trabajó con un conjunto de variables relevantes del negocio, tales como precio, promociones, historial de compras, estacionalidad y canal de venta, con el objetivo de identificar patrones y generar predicciones útiles para la toma de decisiones.

___________________________________________________________________________________________________________

# Objetivo:
Desarrollar un modelo predictivo que permita estimar la demanda de productos en función de variables comerciales y de comportamiento del cliente, apoyando la optimización de estrategias de precio, promociones y planificación comercial.

____________________________________________________________________________________________________________

# Modelo usados:
-Árbol de decisión
-Random Forest

_____________________________________________________________________________________________________________

# ¿Que es un arbol de decisiones?
Un árbol de decisión es un modelo de aprendizaje automático que utiliza una estructura jerárquica de decisiones basada en condiciones sobre las variables de entrada, con el objetivo de predecir un resultado. Este modelo divide los datos en subconjuntos más pequeños mediante reglas simples, permitiendo interpretar fácilmente cómo se llega a una predicción.

Un árbol de decisión es un modelo de Machine Learning que toma decisiones usando reglas simples tipo:

“Si pasa esto → entonces ocurre esto otro”

Es como un diagrama de flujo que divide los datos en pasos hasta llegar a una predicción.

# Estructura de un arbol de decisiones:
El arbol se compone por tres partes:

-Nodo raíz (inicio): Es la primera decisión importante.
-Ramas (decisiones): Son los caminos según la respuesta.
-Hojas (Resultado final): Aquí esta predicción.

# Para que sirve:
-Predecir valores (regresión).
-Clasificar (sí/no, tipo clientes, etc).
-Entender decisiones.

____________________________________________________________________________________________________________

# ¿Que es Randon Forest?
Random Forest es un modelo de aprendizaje automático que construye múltiples árboles de decisión y combina sus resultados para mejorar la precisión de las predicciones, ya sea mediante votación en problemas de clasificación o promediando resultados en problemas de regresión.

_____________________________________________________________________________________________________________

# Tecnologías:
-Python 
-Pandas 
-Scikit-learn 
-Matplotlib (visualización de resultados)

____________________________________________________________________________________________________________

# Interpretacion del Arbol de decisiones:
-El modelo parte dividiendo los datos segun el precio del producto.
-Esta es la variable mas predominante para reducir la variabilidad en la demanda.
-Si el precio es bajo (≤ 57,917), se va por la rama izquierda.
-Si el precio es alto (> 57,917), se va por la rama derecha.
-La demanda promedio para todos los datos (sin ninguna división) hasta este punto es 88,698 unidades.

__________________________________________________________________________________________________________

# Influencia de las Variables:

# Precio:

El precio presenta una relación inversa con la demanda. A medida que el precio aumenta, el árbol dirige las predicciones hacia valores menores de demanda, lo que confirma un comportamiento típico de sensibilidad al precio.

# Promociones:

Las promociones generan un impacto positivo en la demanda. El árbol muestra que, ante la presencia de promociones, las predicciones tienden a aumentar, evidenciando la efectividad de estrategias comerciales basadas en descuentos o incentivos.

#Historial de compras:

El historial de compras influye directamente en la demanda, donde clientes con mayor nivel de compras previas tienden a generar mayores niveles de consumo futuro.

# Estacionalidad:

Se identifica un aumento en la demanda durante periodos de alta estacionalidad, lo que indica que el modelo logra capturar patrones temporales relevantes.

# Canal de venta:

El canal también afecta la predicción, mostrando diferencias en la demanda dependiendo si la venta se realiza en tienda física u online.

___________________________________________________________________________________________________________

# Conclusiones:
El modelo del árbol de decisión desarrollado permite predecir la demanda a partir de variables relevantes como el precio, las promociones, el historial de compras, la estacionalidad y el canal de venta.

A partir de la estructura del árbol, se observa que la variable precio actúa como el principal punto de división en los primeros niveles, lo que indica que es el factor más determinante en la predicción. Esto sugiere que pequeñas variaciones en el precio pueden generar cambios significativos en la demanda.

__________________________________________________________________________________________________________

**AUTOR**
MACARENA ACEVEDO ROJAS 
ROL: ANALISTA DE DATOS EN FORMACIÓN


