# Predicción de Churn de Clientes - Machine Learning + Power BI

## ¿Qué problema resolví?
Construí un modelo de Machine Learning que predice qué clientes están en riesgo de abandonar la empresa. Esto permite tomar acciones de retención antes de perderlos.

## ¿Qué hice?
1. **Python (scikit-learn):** Entrené un modelo Random Forest para predecir churn.
2. **Feature Engineering:** Usé las métricas RFM (Recencia, Frecuencia, Monetario) como variables predictoras.
3. **Evaluación:** El modelo alcanzó un 86.43% de precisión.
4. **Power BI:** Creé un dashboard con los clientes clasificados por nivel de riesgo.

## ¿Qué encontré?
- **1802 clientes** analizados.
- **652 clientes en Alto Riesgo** (36.2%): probablemente abandonarán.
- **45 clientes en Medio Riesgo** (2.5%): requieren atención.
- **1105 clientes en Bajo Riesgo** (61.3%): clientes estables.
- **Probabilidad promedio de churn:** 19.04%

## ¿Qué recomendaría?
- **Campaña urgente de retención:** Contactar a los 652 clientes en Alto Riesgo con ofertas personalizadas.
- **Programa de fidelización:** Para los 45 clientes en Medio Riesgo.
- **Monitoreo continuo:** Actualizar el modelo mensualmente con nuevos datos.

## Modelo de Machine Learning
- **Algoritmo:** Random Forest Classifier
- **Precisión:** 86.43%
- **Features:** Recencia, Frecuencia, Monetario
- **Variable objetivo:** Churn (1 = abandonó, 0 = activo)

## Herramientas usadas
- **Python** (pandas, scikit-learn): Machine Learning.
- **Power BI:** Dashboard interactivo.

## Archivos del proyecto
- `predicciones_churn.csv`: Predicciones para los 1802 clientes.
- `prediccion_churn.ipynb`: Notebook de Python con el modelo.
- `dashboard_churn.pbix`: Archivo de Power BI.
- `dashboard_churn.png`: Captura del dashboard.
