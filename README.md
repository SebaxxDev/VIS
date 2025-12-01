# 📊 Análisis de Resultados SIMCE (4to Básico) 2014-2024

> **Estado:** 🚧 En Desarrollo (Work in Progress)
> **Asignatura:** Visualización de la Información - Universidad Austral de Chile (UACh)
> **Entrega Final:** 12 de Diciembre

## 📝 Descripción del Proyecto
Este repositorio contiene el código fuente y los notebooks para el proyecto final de visualización de datos. El objetivo principal es analizar la evolución, tendencias y brechas en los resultados de la prueba SIMCE de 4to básico en Chile durante la última década.

El sistema consolida automáticamente los datos históricos dispersos en múltiples hojas de cálculo para generar una base de datos unificada apta para la visualización.

## ⚙️ Funcionalidades Actuales
- **Automatización de Datos:** Script en Python que descarga automáticamente el dataset desde la nube si no existe localmente.
- **Normalización de Esquema:** Algoritmo capaz de detectar intersecciones de columnas entre años dispares (2014-2024).
- **Consolidación:** Fusión inteligente de múltiples años en un único DataFrame (`df_simce_all_years`) manejando diferencias estructurales.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.11+
* **Análisis de Datos:** Pandas, Openpyxl
* **Gestión de Archivos/Red:** OS, Requests
* **Visualización (Próximamente):** Altair / mpld3 / Matplotlib

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/SebaxxDev/VIS.git](https://github.com/SebaxxDev/VIS.git)
   cd VIS