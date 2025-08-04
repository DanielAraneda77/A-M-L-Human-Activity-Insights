# 🧠 HumanActivityInsights

---

## Objetivo 

Desarrollar un pipeline reproducible para el reconocimiento e interpretación de actividad física humana a partir de datos sensoriales multivariados, utilizando técnicas de aprendizaje automático supervisado y no supervisado.

---

## Flujo de trabajo

1. **Carga y normalización de datos**  
   Aceleración en ejes X/Y/Z, medias y desviaciones por ventana temporal.

2. **Análisis exploratorio y clustering**  
   Identificación de patrones latentes y segmentación no supervisada.

3. **Entrenamiento de modelo MLP**  
   Reconocimiento supervisado multiclase, benchmark y evaluación con métricas.

4. **Predicción interpretativa**  
   Justificación visual de cada ejemplo mediante gráficos tipo radar.

---

## Métricas de evaluación

- Accuracy y f1-score por clase
- Matriz de confusión visual
- Ajuste entre clustering

---

## Discusión y Análisis

### Análisis no supervisado

La integración de PCA y KMeans permitió explorar la estructura latente del dataset sensorial. Los componentes principales revelaron agrupamientos coherentes entre patrones de aceleración y desviación en ejes X/Y/Z, reflejando comportamientos físicos diferenciados. El clustering evidenció la posibilidad de segmentar actividades sin etiquetas explícitas, lo cual aporta valor en contextos donde la supervisión no es viable.

### Modelo MLP

El modelo de perceptrón multicapa mostró una alta capacidad para reconocer actividades físicas con datos normalizados multivariados. Su desempeño fue consistente en clases como *STANDING*, *WALKING* y *SITTING*, respaldado por métricas robustas y una matriz de confusión clara. Además, su integración con visualizaciones interpretativas por ejemplo individual (radar charts) facilitó una comprensión profunda del vínculo entre datos sensoriales y movimiento físico real.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.



