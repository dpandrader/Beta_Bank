🏦 Proyecto – Predicción de Fuga de Clientes en Beta Bank

Objetivo del proyecto:
Desarrollar un modelo de machine learning capaz de predecir si un cliente abandonará el banco en el corto plazo. El desafío era alcanzar un valor F1 ≥ 0.59 y comparar el rendimiento con la métrica AUC-ROC, para identificar clientes en riesgo y diseñar estrategias de retención.

Procedimientos:

Descarga, exploración y preparación de los datos (demográficos, financieros y de comportamiento de clientes).
Análisis del desequilibrio de clases y entrenamiento de un modelo base sin ajustes.
Implementación de diferentes enfoques para balancear las clases (submuestreo, sobremuestreo, técnicas como SMOTE).
Entrenamiento y evaluación de varios modelos (Logistic Regression, Random Forest, Gradient Boosting).
Selección del mejor modelo en función del F1-score y AUC-ROC en validación y prueba.

Conclusiones:

Se logró superar el valor mínimo de F1 = 0.59, validando la capacidad del modelo para detectar clientes con riesgo de fuga.
El modelo entrenado proporciona una herramienta útil para que el banco priorice acciones de retención de clientes.
El proyecto se implementó con Python, pandas, scikit-learn, matplotlib y seaborn.
