# 📊 Power BI - Seguimiento de Folios Mensual (Dashboard Interactivo)

Este proyecto presenta un dashboard ejecutivo desarrollado en Power BI como parte de un curso intensivo personalizado. El objetivo es analizar el desempeño de ingenieros de TI mediante el seguimiento de folios (tickets) clasificados por tipo, zona y tiempo de resolución.

---

## 🎯 Objetivo

Visualizar y analizar de forma interactiva los datos de 100 ingenieros distribuidos por zonas, enfocándose en:

- Tipo de folios (Incidencia, Servicio, Reparación)
- Resolución de tickets (resueltos, no resueltos)
- Puntualidad de respuesta (en tiempo, próximo a exceder, excedido)
- Eficiencia individual y por zona

---

## 📌 Dashboards Incluidos

### 📍 Dashboard General

> **Captura:** `imgs/dashboard-general.png`

🔎 Características:

- Vista general de todos los ingenieros
- Total de folios acumulados
- Distribución por tipo de folio (gráfico de barras)
- Tabla dinámica por zona e ingeniero

🧠 Permite identificar:
- Carga de trabajo
- Zonas más activas
- Tipos de solicitudes más frecuentes


### 👤 Dashboard por Ingeniero

> **Captura:** `imgs/dashboard-ingeniero.png`

🔎 Características:

- KPIs individuales: resolución, puntualidad
- Gráficos de barra por tipo de folio
- Gráfico de dona sobre tiempo de resolución
- Filtros interactivos por ingeniero y zona

🧠 Permite identificar:
- Ingenieros más eficientes
- Folios excedidos por persona
- Tiempo de atención por tipo

---

## 🧠 Tecnología utilizada

- Power BI Desktop (DAX, Power Query)
- Python (Jupyter Notebook con imágenes embebidas)
- GitHub para publicación del proyecto

---

## ⚙️ DAX Calculados

Algunas fórmulas utilizadas incluyen:

- `% Resolución`:  
  `DIVIDE([Folios Resueltos], [Total de Folios])`

- `% Puntualidad`:  
  `DIVIDE([Folios en Tiempo], [Folios Resueltos])`

- `KPI Resolución`:  
  Se asigna puntaje con pesos distintos a cada tipo de tiempo de resolución.

🔧 El archivo PDF con todas las fórmulas DAX bien explicadas.

---

## 🌱 Posibles mejoras futuras

- Agregar tiempos promedio de resolución
- Ranking histórico por ingeniero
- Análisis de folios críticos o de alta prioridad
- Satisfacción del cliente por ticket

## 📌 Autor

**Uriel López**  
Recién egresado en Ingeniería, enfocado en análisis de datos con Python y SQL.

---

Este proyecto forma parte de mi portafolio profesional para aplicar a posiciones como **Analista de Datos** o **Analista de Métricas**.
