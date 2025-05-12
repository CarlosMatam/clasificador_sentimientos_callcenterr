Este proyecto implementa un modelo de clasificación binaria de sentimientos (positivo / negativo) aplicado a reseñas de atención al cliente en call centers. El modelo fue desarrollado usando scikit-learn, empleando un pipeline de NLP que incluye limpieza de texto, vectorización TF-IDF con n-grams, y entrenamiento con Regresión Logística.
El sistema también incluye una interfaz interactiva para ingresar reseñas y obtener su clasificación en tiempo real.

El modelo puede ser alimentado por un archivo Excel (DataSet.xlsx) con reseñas reales, o generar un conjunto sintético enriquecido en caso de no disponer del archivo.


Cómo ejecutar el modelo

Requisitos
	•	Python 3.7 o superior
	•	pandas, numpy, scikit-learn, openpyxl


 Siguientes fases de mejora

🔹 1. Recolección de datos reales
	•	Integrar API de Trustpilot, Google Reviews, ReclamosCR o reseñas del call center real.
	•	Clasificar manualmente un set de entrenamiento inicial.

🔹 2. Ampliación del modelo
	•	Probar modelos más avanzados como Random Forest, XGBoost o redes neuronales con Keras.
	•	Agregar manejo de errores ortográficos o análisis de emojis.

🔹 3. Análisis de resultados
	•	Agregar una matriz de confusión y curvas ROC/AUC.
	•	Mostrar las palabras con mayor peso en la clasificación.

🔹 4. Despliegue web
	•	Crear un frontend con Flask o Streamlit para probar el modelo en una página web.
	•	Conectar con un dashboard para visualizar estadísticas en tiempo real.

🔹 5. Entrenamiento continuo
	•	Incorporar reseñas nuevas a medida que el call center las recibe.
	•	Etiquetar automáticamente si el cliente dio una calificación posterior.
