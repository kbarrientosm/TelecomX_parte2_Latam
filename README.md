# TelecomX_parte2_Latam
Challenge 3 Alura Latam
Descripción
Este repositorio contiene el análisis y los modelos predictivos desarrollados para identificar y predecir la evasión de clientes (Churn) en TelecomX. Se realizó un análisis exploratorio de datos (EDA) para comprender los factores influyentes y se construyeron modelos de clasificación para prever la probabilidad de que un cliente cancele su servicio.

Contenido del Repositorio
nombre_del_notebook.ipynb: El notebook de Jupyter que contiene todo el código del análisis, incluyendo la extracción de datos, limpieza, transformación, análisis exploratorio, modelado predictivo, evaluación y el informe final.
TelecomX_Data.json: El archivo de datos original (o una referencia a la fuente de datos si se carga directamente de una URL).
TelecomX_diccionario.md: El diccionario de datos que describe cada una de las columnas del dataset.
README.md: Este archivo que proporciona una descripción general del proyecto.
Requisitos
Para ejecutar este notebook, necesitarás tener instaladas las siguientes bibliotecas de Python:

pandas
requests
matplotlib
seaborn
sklearn
imblearn
Puedes instalarlas usando pip:

pip install pandas requests matplotlib seaborn scikit-learn imbalanced-learn
keyboard_arrow_down
Uso
Clona este repositorio:
git clone https://github.com/tu_usuario/tu_repositorio.git
Navega al directorio del repositorio:
cd tu_repositorio
Abre el notebook en Jupyter (o Google Colab):
jupyter notebook nombre_del_notebook.ipynb
spark
Gemini
Ejecuta las celdas del notebook secuencialmente para replicar el análisis y los resultados.
Estructura del Análisis
El análisis sigue los siguientes pasos principales:

Extracción de Datos: Carga de los datos desde la fuente original.
Limpieza y Transformación de Datos: Manejo de inconsistencias, aplanamiento de estructuras anidadas, creación de nuevas características y estandarización/normalización.
Análisis Exploratorio de Datos (EDA): Visualización y resumen de las características de los datos y su relación con la variable objetivo (Churn).
Preparación de Datos para Modelado: Codificación de variables categóricas, balanceo de clases y división en conjuntos de entrenamiento y prueba.
Modelado Predictivo: Entrenamiento de modelos de clasificación para predecir Churn.
Evaluación del Modelo: Medición del rendimiento de los modelos utilizando métricas de clasificación.
Interpretación de Resultados: Análisis de la importancia de las variables y los hallazgos clave.
Conclusiones y Recomendaciones: Resumen de los insights obtenidos y propuestas de estrategias de retención.
Conclusiones Clave
📊 Hallazgos del Análisis Exploratorio (EDA)
Clientes con contrato mes a mes presentan una tasa de Churn significativamente mayor en comparación con contratos anuales.

Facturación electrónica está asociada a un mayor abandono, posiblemente por falta de engagement.

Clientes con mayores cargos mensuales tienden a cancelar más frecuentemente.

🤖 Resultados de los Modelos Predictivos
Random Forest obtuvo el mejor desempeño:

Precisión: XX%

Recall (Churn): (crítico para identificar clientes en riesgo).

AUC-ROC:  (buena capacidad de discriminación).

Variables más importantes:

Duración del contrato (contratos cortos = mayor riesgo).

Cargos mensuales (clientes con facturas altas más propensos a irse).

Servicios adicionales (clientes con más servicios tienen menor Churn).

Recomendaciones Estratégicas
✅ Incentivar contratos a largo plazo: Descuentos o beneficios para clientes que cambien a planes anuales.
✅ Programas de fidelización: Ofertas personalizadas para clientes con facturación electrónica.
✅ Alertas tempranas: Monitorear clientes con cargos altos y ofrecer soporte proactivo.
✅ Mejorar engagement: Campañas de retención para usuarios con pocos servicios adicionales.
Autor
Keyla Barrientos
[Enlace a tu perfil de GitHub u otro contacto]
Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.


