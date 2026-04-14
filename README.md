# 📊 Andes Retail: Performance & Diagnostics Dashboard (2024-2025)

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Tools](https://img.shields.io/badge/Tools-Power%20BI%20%7C%20DAX%20%7C%20Python%20%7C%20Excel-orange)
![Category](https://img.shields.io/badge/Category-Business%20Intelligence-green)

## 📌 Contexto del Proyecto

Este repositorio contiene el desarrollo integral de un Dashboard de Inteligencia de Negocios para **Andes Retail Group**, centrado en el análisis de desempeño comercial de 5,000 registros transaccionales en Latinoamérica.

---

## 🧠 Metodología Analítica: Modelo SCQA (Versión Ejecutiva Final)

### 📱 Vista Overview (Salud Global)

- **S (Situación):** Andes Retail Group ha consolidado **$5.53 millones** en ingresos con un margen robusto del **35.10%** y una ganancia total de **$1.94M**. Perú lidera con el 39% de participación.
- **C (Complicación):** Se identifica una volatilidad estacional crítica. Deportes ($1.44M) concentra picos, pero en Invierno la calidad del ticket colapsa un **68%** ($549 vs. $1,721 en Verano).
- **A (Respuesta):** Se rediseñó la visualización eliminando gráficos de anillos (Donuts) por **Barras Apiladas Horizontales** (Sprint 10 standard). Se recomienda implementar **Bundling estratégico** (Electrónica + Ropa) para restaurar el ticket a $1,100+.

### 🔍 Vista Detalle y Análisis de Segmentación

- **S (Situación):** El Verano es el motor premium, consolidando **$2.24M** con tickets promedio de **$1,721**. El segmento "Premium" concentra el 47% de los ingresos anuales.
- **C (Complicación):** Invierno sufre una contracción severa del **-71%** en ingresos. El **70.68%** de los pedidos invernales son de "Venta Baja", saturando la logística con pedidos de poco valor.
- **Q (Pregunta):** ¿La caída refleja estacionalidad inevitable o una falla en el mix de productos de temporada?
- **A (Respuesta):** Se requiere una reestructuración del inventario invernal mediante **Barras 100% Apiladas** (Mejorando la jerarquía visual vs. anillos antiguos) para monitorear la mejora en el mix de ticket alto.

---

## 📈 Visualizaciones Reales

### 1. Overview Ejecutivo
![Overview Dashboard](docs/images/dashboard_overview.png)

### 2. Vista Detalle y Análisis Estacional
![Detalle Dashboard](docs/images/dashboard_detail.png)

---

## 🛠️ Stack Tecnológico
- **Power BI Desktop:** Modelado y visualización.
- **DAX:** Inteligencia de tiempo y medidas de rentabilidad.
- **Python:** Auditoría de integridad de datos (Sprint 10).

---

## 👨‍💻 Autor

**David Ramos**  
*Business Intelligence Analyst*  
[LinkedIn](https://www.linkedin.com/in/david-g-ramos/) | [Portfolio](https://dataanalist-davidgramos.github.io/mi-sitio-web/)
