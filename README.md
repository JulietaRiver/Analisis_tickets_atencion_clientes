# 📊 Análisis de Atención al Cliente con Datos de Tickets

Este proyecto simula el análisis de un conjunto de tickets de atención al cliente para detectar áreas de mejora, medir la satisfacción del usuario y proponer acciones basadas en datos.

---

## 🧾 Objetivo

Analizar datos de atención al cliente para obtener insights clave que permitan:

- Identificar cuellos de botella en tiempos de resolución
- Evaluar satisfacción del cliente por canal
- Detectar canales con bajo desempeño
- Proponer recomendaciones basadas en métricas

---

## 📌 Dataset Simulado

El dataset contiene columnas como:

- `ticket_id`: ID del ticket
- `usuario_id`: ID del cliente
- `fecha_creacion`, `fecha_cierre`: fechas de atención
- `tipo_ticket`, `canal`: tipo de solicitud y medio
- `tiempo_respuesta_min`: tiempo hasta primera respuesta
- `resuelto`: si fue o no resuelto
- `csat`: puntuación de satisfacción (1 a 5)
- `comentarios_usuario`: texto libre

---

## 🔍 Análisis Realizado

- Cálculo del **tiempo promedio de resolución**
- Porcentaje de tickets **no resueltos**
- Clasificación del nivel de **satisfacción del cliente**
- Comparación de **satisfacción por canal**
- Visualización de **tiempos promedio por canal**

---

## 📊 Visualizaciones

- Gráfico de barras: Tiempo promedio de resolución por canal
- Gráfico de barras: Satisfacción promedio (`CSAT`) por canal

---

## 💡 Principales Hallazgos

- El canal **Correo** presenta el tiempo más alto de resolución y la menor satisfacción.
- El canal **Chat** es más ágil y tiene mejores calificaciones.
- Se recomienda enfocar esfuerzos de mejora en **Correo electrónico**, ya sea automatizando o capacitando.

---

## 🛠️ Herramientas utilizadas

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Git y GitHub

---

## 👩‍💻 Sobre mí

Soy Julieta Rivera, Científica de Datos en formación, en este proyecto el enfoque es en análisis de atención al cliente, experiencia de usuario y visualización de datos.  

