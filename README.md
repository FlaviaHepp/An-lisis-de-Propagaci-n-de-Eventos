# 🔄📊Análisis de Propagación de Eventos

## 📌Descripción del proyecto

Este proyecto implementa una consulta SQL para analizar la propagación de un evento, comportamiento o impacto a través de entidades relacionadas, permitiendo identificar efectos en cadena y patrones de contagio dentro de un sistema.

El análisis busca responder cómo un evento inicial se difunde en el tiempo y entre distintas unidades (clientes, cuentas, regiones, productos o nodos), aportando visibilidad sobre riesgos sistémicos y dinámicas no evidentes a simple vista.

## 🎯Objetivos del proyecto

- Analizar la propagación temporal de un evento o señal.
- Identificar entidades directa e indirectamente impactadas.
- Medir velocidad, alcance e intensidad de la propagación.
- Detectar patrones de contagio o amplificación.
- Automatizar análisis de efectos en cadena mediante SQL.

## 🏢Contexto de negocio

La propagación de eventos es crítica en múltiples dominios:
- Riesgo y fraude: contagio de comportamientos anómalos.
- Finanzas: transmisión de shocks o deterioro crediticio.
- Operaciones: fallas que se expanden entre procesos.
- BI & Analytics: adopción, churn o cambios de comportamiento.

📌 Comprender la propagación permite anticipar impactos futuros y priorizar acciones preventivas.

## 🧠Lógica del análisis

La consulta SQL:
- Identifica el evento inicial (origen).
- Define relaciones entre entidades (dependencias, vínculos o proximidad).
- Analiza la evolución temporal del impacto.

Mide:
- Número de entidades afectadas
- Tiempo de propagación
- Intensidad del efecto
- Clasifica patrones de propagación (limitada, progresiva, acelerada).

📌 El enfoque es flexible y adaptable a distintos modelos de datos.

## 📊Ejemplos de insights

- Eventos que quedan contenidos vs. eventos que se expanden rápidamente.
- Identificación de nodos críticos que amplifican el impacto.
- Diferencias de propagación entre segmentos o regiones.
- Ventanas temporales de mayor riesgo sistémico.

## 🛠️Tecnologías utilizadas

SQL

Compatible con:
- PostgreSQL
- SQL Server
- BigQuery
- Oracle
- MySQL (con ajustes menores)

## 📁Estructura del proyecto

├── analisis_propagacion.sql
└── README.md

## ▶️Cómo utilizar la consulta

Abrir el archivo analisis_propagacion.sql.

Configurar:
- Evento de origen
- Entidades y relaciones
- Ventana temporal de análisis
- Ejecutar la consulta en el motor SQL.
- Analizar los resultados o integrarlos en reportes y dashboards.

## 🚀Posibles extensiones

- Análisis de propagación por niveles (1°, 2°, 3° orden).
- Medición de impacto acumulado.
- Integración con alertas tempranas.
- Visualización tipo red o timeline.
- Combinación con modelos predictivos.

## 👤Autora

Flavia Hepp
Proyecto de SQL aplicado a análisis de propagación y efectos sistémicos.
