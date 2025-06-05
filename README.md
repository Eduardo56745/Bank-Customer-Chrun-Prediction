# 💼 Predicción de Cancelación de Cuentas en Beta Bank

Este proyecto tiene como objetivo ayudar a **Beta Bank** a identificar a los clientes con alto riesgo de cancelar sus cuentas, permitiendo implementar estrategias proactivas de retención. A través de un modelo de clasificación supervisada, es posible anticipar comportamientos de abandono y reducir pérdidas.

---

## 🎯 Objetivos del Proyecto

- 📊 Analizar el comportamiento de los clientes y su relación con la cancelación de servicios.
- 🤖 Construir un modelo de clasificación capaz de predecir cancelaciones con alto desempeño.
- ⚖️ Aplicar técnicas para corregir el **desequilibrio de clases** y mejorar la precisión en minorías.

---

## 🛠️ Técnicas y Herramientas

- Python 🐍  
- Pandas & NumPy 📋  
- Scikit-learn 🔍  
- Imbalanced-learn ⚖️  
- Matplotlib & Seaborn 📈

---

## 🔁 Flujo de Trabajo

1. **Preprocesamiento de Datos**
   - Limpieza, transformación y codificación de variables.
   - Análisis exploratorio para entender patrones de abandono.

2. **Manejo del Desequilibrio**
   - Ajuste de pesos en el modelo.
   - Aplicación de **sobremuestreo** para mejorar la sensibilidad.

3. **Entrenamiento y Evaluación**
   - Entrenamiento de modelos con enfoque en F1-score.
   - Evaluación mediante **F1-score**, **AUC-ROC** y matriz de confusión.

---

## 📈 Resultados Clave

- 🔍 El modelo alcanzó un **F1-score superior a 0.59**, cumpliendo el umbral mínimo para producción.
- 📈 Se logró una buena **curva ROC**, indicando una separación efectiva entre clases.
- ✅ La implementación de técnicas para datos desbalanceados mejoró significativamente el rendimiento del modelo en los casos de cancelación.

---

## 🧠 Conclusiones

Este proyecto demuestra cómo el aprendizaje automático puede aportar valor real en la **gestión de clientes**, permitiendo a bancos como Beta Bank identificar de manera anticipada riesgos de abandono. La combinación de técnicas de clasificación con estrategias para datos desbalanceados resulta crucial en contextos sensibles como este.

---

📬 **¿Tienes ideas o sugerencias?** Estoy abierto a colaboraciones y mejoras para seguir optimizando este tipo de soluciones en el sector financiero.
