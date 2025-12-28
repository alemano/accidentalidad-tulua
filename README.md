# 📊 Análisis y Predicción Exploratoria de Accidentalidad – Tuluá

## 📌 Descripción del proyecto
Este proyecto realiza un análisis exploratorio de datos de accidentalidad vial del municipio de Tuluá, integrando procesos de limpieza, transformación, visualización y una predicción exploratoria basada en series temporales.

El objetivo principal es identificar patrones temporales, zonas críticas y comportamientos recurrentes que sirvan como insumo para la toma de decisiones y la planificación preventiva.

---

## 📁 Estructura del proyecto


---

## ⚙️ Proceso ETL (Extract, Transform, Load)

El procesamiento de datos se realizó en Python utilizando Pandas, siguiendo las siguientes etapas:

- Carga de datos desde GitHub (raw)
- Normalización de columnas
- Conversión de variables temporales
- Creación de variables derivadas:
  - Año
  - Mes
  - Día de la semana
  - Franja horaria
- Tratamiento de valores faltantes
- Exportación del dataset final para visualización

---

## 📈 Análisis exploratorio

Se analizaron las siguientes dimensiones:

- Accidentes por día de la semana
- Accidentes por hora y franja horaria
- Distribución por área (urbana / rural)
- Barrios con mayor accidentalidad
- Tipo de vehículo involucrado

Los resultados muestran una mayor concentración de accidentes durante los fines de semana y en horas de la tarde y noche, principalmente en zonas urbanas.

---

## 🔮 Predicción exploratoria

### Enfoque utilizado
Se realizó una **predicción exploratoria de la accidentalidad mensual** utilizando una serie temporal agregada por mes.

El método empleado fue:

- Media móvil de 3 meses (rolling mean)

Este enfoque permite suavizar la variabilidad mensual y estimar una tendencia general a corto plazo.

### Importante
⚠️ Esta predicción **no busca anticipar accidentes individuales**, sino:

- Identificar tendencias
- Estimar valores promedio esperados
- Apoyar análisis preventivos

### Interpretación
El valor proyectado representa una estimación del número promedio de accidentes mensuales, bajo el supuesto de que las condiciones recientes se mantienen constantes.

---

## 🛠️ Herramientas utilizadas

- Python (Pandas, Matplotlib)
- Google Colab
- GitHub
- Power BI

---

## 📌 Nota ética
Los resultados de este análisis deben interpretarse con responsabilidad. Las predicciones presentadas son exploratorias y no reemplazan estudios técnicos oficiales ni modelos predictivos avanzados.

---

## 👤 Autor
Proyecto desarrollado con fines educativos y de portafolio en analítica de datos.
