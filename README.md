# 📊 Andes Retail: Performance & Diagnostics Dashboard (2024-2025)

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tools](https://img.shields.io/badge/Tools-Power%20BI%20%7C%20DAX%20%7C%20Python%20%7C%20Excel-orange)
![Category](https://img.shields.io/badge/Category-Business%20Intelligence-green)

## 📌 Contexto del Proyecto

Este repositorio contiene el desarrollo integral de un Dashboard de Inteligencia de Negocios para **Andes Retail Group**, centrado en el análisis de desempeño comercial de 5,000 registros transaccionales en la región de Latinoamérica (Perú, Chile, Colombia).

El objetivo principal no fue solo visualizar datos, sino realizar un **diagnóstico estratégico** capaz de identificar la "erosión silenciosa" del margen operativo frente al crecimiento masivo de ingresos.

---

## 🧠 Metodología Analítica: Modelo SCQA

Para este proyecto se implementó la metodología **SCQA** (*Situation, Complication, Question, Answer*) para asegurar que cada visualización responda a una necesidad de negocio real:

- **S (Situación):** El grupo registra ingresos de **$5.53M** con un margen del **35.10%**. Perú lidera el volumen con un 39% de participación.
- **C (Complicación):** El crecimiento en volumen está siendo impulsado por la categoría de **Deportes**, la cual presenta los márgenes de eficiencia más bajos del mix comercial. Además, en **Invierno**, la calidad de la venta cae drásticamente (70% de ventas bajas).
- **Q (Pregunta):** ¿Cómo optimizar el mix comercial para asegurar que el volumen no sacrifique la rentabilidad operativa?
- **A (Respuesta):** Reestructurar la estrategia de precios en la categoría Deportes bajo el modelo de éxito de Electrónica e implementar estrategias de *Bundling* en temporadas bajas (Invierno) para elevar el ticket promedio.

---

## 🛠️ Stack Tecnológico

- **Power BI Desktop:** Modelado de datos y visualización.
- **DAX (Data Analysis Expressions):** Creación de medidas complejas (Margen %, Ticket Promedio, Medias Móviles).
- **Power Query:** Transformación y limpieza de datos (Mínimo de 10 pasos aplicados).
- **Python:** Validación de integridad de datos y auditoría de redondeo.
- **Modelos de IA (Claude/Gemini):** Validación de hipótesis analíticas y optimización de jerarquía visual.

---

## 📈 Visualizaciones Clave

### 1. Overview Ejecutivo (Salud Global)
Enfocado en la "Tensión Ejecutiva" entre Escala (Ingresos) y Eficiencia (Margen). Utiliza un **Combo Chart** para diagnosticar rápidamente qué categoría está por debajo del margen objetivo.

![Overview Dashboard](docs/images/dashboard_overview.png)

### 2. Vista Detalle (Diagnóstico de Causas)
Alica un enfoque de **Hipótesis Falsificables**, analizando la estacionalidad y la calidad de la venta mediante barras 100% apiladas y gráficos de doble eje.

![Detalle Dashboard](docs/images/dashboard_detail.png)

---

## 🔍 Hallazgos Principales (Insights)

1. **La Trampa del Volumen:** Se identificó que la categoría líder en ventas es la menos rentable, sugiriendo una necesidad urgente de revisión de costos operativos.
2. **Deterioro Estacional:** Existe una correlación negativa entre la temporada de Invierno y el valor del ticket promedio, lo que satura la logística con pedidos de bajo valor.
3. **Integridad de Datos:** Mediante auditoría en Python, se detectaron discrepancias de redondeo en Power BI, ajustando el reporte a 2 decimales para una toma de decisiones precisa.

---

## 🚀 Cómo utilizar este Repositorio

1. **Explorar el archivo `.pbix`:** Descarga la carpeta `/pbix` para abrir el modelo en Power BI Desktop.
2. **Revisar la Planificación:** En la carpeta `/notebooks` se encuentra el archivo `.ipynb` con el razonamiento estratégico y la documentación técnica.
3. **Consultar el Dataset:** Los datos fuente anonimizados están disponibles en `/data`.

---

## 👨‍💻 Autor
**David Ramos**  
*Business Intelligence Analyst*  
[LinkedIn](AQUÍ_VA_TU_LINKEDIN) | [Portfolio](AQUÍ_VA_TU_WEB)

---
*Este proyecto forma parte del Sprint 10 de la certificación de Data Analyst en TripleTen.*
