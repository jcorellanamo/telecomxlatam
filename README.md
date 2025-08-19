# 📊 TelecomX Churn Analysis

Este proyecto corresponde a un **análisis completo de evasión de clientes (Churn)** para la empresa **TelecomX LATAM**, desarrollado como parte de un desafío de Data Science.

El objetivo es **entender los factores que influyen en la cancelación del servicio**, generar insights accionables y proponer recomendaciones estratégicas para **reducir la evasión**.

---

## 📂 Contenido del Repositorio

- `TelecomX_LATAM.ipynb` → Notebook con todo el flujo de trabajo y el informe final.
- `informe_figs/` → Carpeta con las imágenes utilizadas en el informe.
- `TelecomX_Entregable.zip` → Paquete comprimido con el notebook y las figuras (entregable final).
- `TelecomX_Data.json` → Dataset original en formato JSON.
- `TelecomX_Data_Estandarizado.csv` → Dataset limpio y estandarizado para el análisis.
- `README.md` → Este archivo de documentación.

---

## 🚀 Flujo de Trabajo

1. **Carga de Datos**
   - Se importaron los registros de clientes desde un archivo JSON (API simulada).
   - Conversión a un `DataFrame` de pandas.

2. **Limpieza y Tratamiento**
   - Normalización de cadenas de texto.
   - Estandarización de variables binarias (`Yes/No → 1/0`).
   - Traducción de columnas al español.
   - Creación de la columna `CargosDiarios`.

3. **Análisis Exploratorio (EDA)**
   - Estadísticas descriptivas (media, mediana, desviación estándar).
   - Distribución de evasión (`Evasion`).
   - Comparaciones por variables categóricas (género, contrato, método de pago).
   - Comparaciones por variables numéricas (tenure, cargos mensuales/totales).
   - Correlación de variables numéricas con evasión.

4. **Informe Final**
   - Incluido dentro del notebook.
   - Contiene:
     - Introducción
     - Limpieza y tratamiento de datos
     - Análisis exploratorio con gráficos
     - Conclusiones e insights
     - Recomendaciones estratégicas

---

## 📊 Principales Insights

- Los clientes con **contratos mensuales** muestran una tasa de evasión significativamente mayor.
- La **antigüedad baja** (primeros meses) está asociada a mayor cancelación.
- Servicios adicionales como **Seguridad Online** y **Soporte Técnico** reducen la probabilidad de evasión.
- Los clientes con **cargos mensuales altos** presentan mayor riesgo de baja.

---

## 🧭 Recomendaciones

- Incentivar contratos **anuales/bianuales** mediante descuentos o beneficios.
- Programas de **onboarding y retención temprana** (primeros 3–6 meses).
- Promoción de servicios adicionales de **seguridad y soporte técnico**.
- **Alertas y retención proactiva** para clientes con cargos elevados.
- Optimización de **métodos de pago y facturación electrónica**.

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.10+**
- **Pandas** → Manipulación y análisis de datos
- **Matplotlib** → Visualización de datos
- **NumPy** → Cálculos numéricos
- **Jupyter Notebook** → Desarrollo interactivo

---

## 📌 Cómo Usar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jcorellanamo/TelecomX_Churn.git
   cd TelecomX_Churn
