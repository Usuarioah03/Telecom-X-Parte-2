📊 Predicción de Cancelación de Clientes en Telecomunicaciones

🎯 Objetivo del Proyecto

El propósito de este proyecto es predecir la cancelación (churn) de clientes en una empresa de telecomunicaciones.

El análisis busca:

Identificar patrones de comportamiento de clientes que cancelan el servicio.

Evaluar las variables más influyentes en la predicción de cancelación.

Entrenar y comparar modelos de machine learning para determinar el más adecuado.

🛠️ Herramientas y Librerías Utilizadas

El proyecto utiliza las siguientes herramientas y librerías:

Lenguaje: Python 3

Librerías principales:

Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn
Entornos de ejecución recomendados: Google Colab o Jupyter Notebook

Asistencia en el desarrollo: ChatGPT (OpenAI), utilizado como apoyo para la estructuración, explicación y optimización del proyecto.

📂 Estructura del Proyecto

Exploración y Preparación de Datos

Preparación de los Datos.
Extracción del Archivo Tratado
Eliminación de Columnas Irrelevantes
Encoding
Verificación de la Proporción de Cancelación (Churn)
Balanceo de Datos
Normalización o Estandarización
Correlación y Selección de Variables
Análisis de Correlación
Análisis Dirigido
Modelado Predictivo
Separación de Datos
Creación de Modelos
Evaluación de Modelos
Interpretación y Conclusiones
Análisis de la Importancia de las Variables
Conclusión
📈 Resultados Principales

Ambos modelos presentaron desempeños competitivos, con un balance razonable entre precisión y recall.

Las variables relacionadas con tipo de contrato, servicios adicionales (ej. fibra óptica, streaming) y gasto total fueron las más determinantes para la predicción de cancelación.

El uso de SMOTE permitió mejorar el recall en comparación con modelos entrenados en datos desbalanceados.

🤝 Reconocimientos

Este proyecto fue desarrollado con el acompañamiento y apoyo de ChatGPT (OpenAI), que sirvió como guía para:

Explicación de conceptos técnicos.

Desarrollo de fragmentos de código.

Revisión de métricas y resultados.

🚀 Próximos Pasos

Probar métricas adicionales como ROC-AUC y PR-AUC.

Evaluar modelos adicionales basados en distancia como KNN, aplicando estandarización.

Implementar optimización de hiperparámetros con GridSearchCV o RandomizedSearchCV.

▶️ Cómo Ejecutar el Proyecto

Clona este repositorio en tu equipo local o en Google Colab:
git clone https://github.com/Usuarioah03/Telecom-X-Parte-2.git
Abre el archivo "Challenge: TELECOM_X_PART_2.ipynb" en Google Colab o Jupyter Notebook.

Sube el archivo "df_telecom.csv"
