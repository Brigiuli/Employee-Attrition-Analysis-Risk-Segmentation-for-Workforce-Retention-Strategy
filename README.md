## Resumen del proyecto
Proyecto de analítica de Recursos Humanos enfocado en la predicción de rotación de empleados mediante machine learning. El objetivo es identificar empleados en riesgo de salida y entender los factores asociados a la rotación para apoyar decisiones de retención de talento.

## Objetivo general
Desarrollar un modelo predictivo que permita identificar empleados con alta probabilidad de abandonar la empresa (attrition) y apoyar estrategias de retención basadas en datos.

## Objetivos específicos
* Analizar y preparar datos de empleados para el modelado.
* Identificar variables relevantes asociadas a la rotación.
* Construir modelos de clasificación para predecir attrition.
* Evaluar el desempeño del modelo mediante métricas de clasificación.
* Aplicar técnicas para mejorar el desempeño del modelo (balanceo y ajuste de umbral).
* Generar insights para la toma de decisiones en RRHH.

## Metodología
El proyecto sigue un flujo completo de analítica de datos:

* Carga del dataset de empleados desde Kaggle
* Análisis exploratorio de datos (EDA)
* Limpieza y tratamiento de variables irrelevantes
* Codificación de variables categóricas
* División de datos en entrenamiento y prueba
* Escalado de variables
* Entrenamiento de modelos de clasificación (Regresión Logística y Random Forest)
* Manejo de desbalance de clases con SMOTE
* Ajuste de threshold para optimizar recall
* Evaluación del modelo con métricas de clasificación

## Principales insights
* Los empleados con menor ingreso mensual presentan mayor probabilidad de rotación.
* El uso de horas extra (overtime) está asociado a mayor riesgo de salida.
* El ingreso mensual es una de las variables más influyentes en el modelo.
* El overtime tiene un impacto parcial en la rotación, pero no es el único factor determinante.
* Se identifican patrones que permiten segmentar empleados en riesgo de rotación.

## Valor para el negocio
* Permite identificar empleados en riesgo de salida de forma anticipada.
* Apoya estrategias de retención de talento basadas en datos.
* Ayuda a priorizar acciones sobre empleados con mayor riesgo.
* Contribuye a reducir costos asociados a rotación y reemplazo de personal.

## Herramientas utilizadas
Python | Pandas | NumPy | Scikit-learn | Seaborn | Matplotlib | SMOTE | Google Colab

## Conclusión
El modelo permite predecir la rotación de empleados y entender los factores asociados a la salida, facilitando la toma de decisiones en Recursos Humanos orientadas a la retención de talento mediante análisis de datos.

## Conjunto de datos
El dataset utilizado proviene de Kaggle y corresponde a un caso clásico de HR Analytics – Employee Attrition, ampliamente usado para análisis de rotación de empleados.

Fuente: Kaggle – IBM HR Analytics Employee Attrition & Performance Dataset
Observaciones (filas): 1,470 empleados
Variables (columnas): 35 variables
Variable objetivo (target): Attrition
Valores:
1 = El empleado abandonó la empresa
0 = El empleado permanece en la empresa
