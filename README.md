# TelecomX_LATAM
Has sido contratado como asistente de análisis de datos en Telecom X y formarás parte del proyecto "Churn de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.  

# Análisis de Churn de Clientes - Telecom X 📊

Este proyecto forma parte de una iniciativa de la empresa **Telecom X** para comprender y reducir la pérdida de clientes (Churn). El análisis se centra en identificar los factores clave que llevan a las cancelaciones y proponer estrategias basadas en datos para mejorar la retención.

## 📋 Descripción del Proyecto

Telecom X enfrenta una alta tasa de cancelaciones. Como asistente de análisis de datos, el objetivo es extraer, transformar y analizar los datos de los clientes para descubrir patrones de comportamiento asociados con el abandono del servicio.

## 🛠️ Estructura del Proyecto

El notebook está organizado en las siguientes etapas principales:

1. **Extracción:** Conexión a la API de GitHub para obtener el conjunto de datos `TelecomX_Data.json` en formato JSON y cargarlo en un DataFrame de Pandas.
2. **Transformación:** * Aplanado de estructuras JSON anidadas (`customer`, `phone`, `internet`, `account`) para facilitar el análisis.
* Selección de variables críticas como `tenure`, tipo de contrato y cargos mensuales.
* Limpieza y binarización de datos para preparar el análisis estadístico.


3. **Análisis:** Evaluación de servicios adicionales y tipos de contrato para determinar su impacto en la tasa de churn.

## 🔍 Hallazgos Principales

Tras el análisis, se identificaron factores determinantes para la retención:

* **Tipo de Contrato:** Los contratos mes a mes presentan la mayor tasa de abandono en comparación con los contratos de largo plazo.
* **Servicios de Internet:** Los clientes con fibra óptica muestran una tendencia de churn que requiere análisis profundo.
* **Servicios Adicionales:** La seguridad en línea, el soporte técnico y la protección de dispositivos actúan como factores de retención; los clientes que cuentan con ellos tienen menos probabilidades de cancelar.

## 🚀 Recomendaciones

* Implementar estrategias para migrar clientes de contratos mensuales a anuales o bi-anuales.
* Mejorar la experiencia y satisfacción de los usuarios de fibra óptica.
* Promocionar activamente los servicios adicionales de valor agregado (seguridad, soporte, protección) para aumentar la dependencia positiva del cliente con la marca.

## 🧰 Requisitos

Para ejecutar este notebook, se requieren las siguientes librerías de Python:

* `pandas`
* `numpy`
* `requests`
* `base64`
* `json`
