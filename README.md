# 🎵 Music Behavior Analysis by City: Springfield vs. Shelbyville

## 📝 Descripción del Proyecto

Este proyecto implementa un pipeline de análisis de datos para contrastar el comportamiento de consumo musical entre dos áreas metropolitanas: **Springfield** y **Shelbyville**. A través de la ingeniería de características y el procesamiento de logs transaccionales, se validan hipótesis sobre patrones de actividad temporal y preferencias de género.

**Proyecto ID**: #03

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.12
- **Librerías:** Pandas, NumPy
- **Entorno:** Jupyter Notebook / VS Code

## 🚀 Etapas del Pipeline

1. **Auditoría de Integridad:** Diagnóstico y tratamiento de valores nulos mediante imputación estratégica.
2. **Normalización y Saneamiento:** \* Remoción de duplicados explícitos e implícitos.
   - Homologación semántica del catálogo de géneros (Normalización de categorías).
3. **Análisis Estadístico:** \* Cálculo de métricas de tracción (Usuarios Únicos vs. Reproducciones Totales).
   - Segmentación temporal-geográfica mediante **Tablas Dinámicas (Pivot Tables)**.
   - Implementación de motores de consulta modulares para validación de hipótesis.

## 📊 Hallazgos Clave

- **Comportamiento Temporal:** Se identificaron picos de actividad asíncronos entre ambas ciudades, sugiriendo dinámicas de consumo diferenciadas según el día de la semana.
- **Consistencia de Datos:** La estandarización de categorías permitió una reducción significativa en la fragmentación del catálogo de géneros.

## 📁 Estructura del Repositorio

- `Music Behavior Analysis by City.ipynb`: Notebook principal con la ejecución del pipeline y comentarios técnicos.
- `README.md`: Documentación profesional del proyecto.
- `.gitignore`: Exclusión de entornos virtuales y archivos temporales de sistema.
