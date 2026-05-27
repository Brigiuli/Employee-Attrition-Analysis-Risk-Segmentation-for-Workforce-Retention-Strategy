Predicción de Rotación de Empleados
## Resumen del proyecto
Este proyecto tiene como objetivo analizar datos de Recursos Humanos y desarrollar un modelo de Machine Learning capaz de predecir la rotación de empleados (attrition). A través del análisis exploratorio de datos (EDA) y modelos de clasificación, se identifican patrones asociados a la salida de empleados, permitiendo apoyar estrategias de retención y toma de decisiones en RRHH.

## Objetivos
## Objetivo General
Desarrollar un modelo predictivo que permita identificar empleados con alta probabilidad de abandonar la empresa para apoyar estrategias de retención basadas en datos.

## Objetivos Específicos
* Analizar y preparar datos de empleados para el modelado.
* Identificar variables relevantes asociadas a la rotación.
* Construir y evaluar modelos de clasificación.
* Aplicar técnicas de balanceo y ajuste de threshold.
* Generar risk scoring para segmentar empleados según nivel de riesgo.
* Generar insights para apoyar decisiones de Recursos Humanos.

## Metodología

El proyecto incluye:
* Descarga y carga del conjunto de datos desde Kaggle.
* Análisis exploratorio de datos (EDA).
* Limpieza y preparación de datos.
* Transformación y codificación de variables categóricas.
* División de datos en entrenamiento y prueba.
* Escalado de variables numéricas.
* Entrenamiento de modelos de clasificación (Regresión Logística y Random Forest).
* Manejo de desbalance de clases mediante SMOTE.
* Ajuste de threshold para mejorar la detección de empleados en riesgo.
* Evaluación mediante métricas de clasificación y matriz de confusión.
* Generación de risk scoring y segmentación de empleados según nivel de riesgo.
* Exportación de resultados para análisis de RRHH.

## Principales hallazgos
* El ingreso mensual y las horas extras (overtime) se encuentran entre las variables más asociadas a la rotación.
* Se identifican perfiles con mayor riesgo de salida relacionados con menor compensación y mayor carga laboral.
* El análisis permitió detectar patrones de rotación asociados a condiciones laborales y experiencia del empleado.
* El modelo permite estimar la probabilidad de salida de cada empleado mediante risk scoring.

## Herramientas Utilizadas
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | SMOTE | Google Colab | Kaggle

## Conjunto de datos
Fuente: Kaggle
Dataset: IBM HR Analytics Employee Attrition & Performance

Registros: 1,470 empleados\
Variables: 35 columnas\
Tipo de problema: Clasificación binaria\
Variable objetivo: Attrition\
1 = el empleado abandona la empresa\
0 = el empleado permanece en la empresa\

El dataset incluye información de empleados relacionada con ingresos, horas extras, satisfacción laboral, experiencia, desempeño y otras variables utilizadas para analizar y predecir la rotación de personal.
El dataset incluye información de empleados relacionada con ingresos, horas extras, satisfacción laboral, experiencia, desempeño y otras variables utilizadas para analizar y predecir la rotación de personal.
