# 📊 Análisis Bancario Ejecutivo (Synthetic Banking Relational Analytics)

---

## 🎯 Objetivo del Proyecto

Diseñar e implementar un proyecto analítico completo de extremo a extremo utilizando una base de datos bancaria sintética, abarcando la ingeniería de datos en SQL para la integración de múltiples tablas relacionales (`customers`, `accounts`, `loans` y `cards`), la limpieza y transformación visual de datos en Power Query (concatenación de campos y gestión de nulos), y la creación de un panel visual ejecutivo interactivo en Power BI Desktop optimizado para la toma de decisiones a nivel macro.

---

## 🖼 Visualización del Dashboard
![Dashboard Screenshot](./Synthetic_Banking_Dataset_Screenshot.png)

---

## 🛠 Herramientas Utilizadas

* **SQL (SQLite / DBeaver):** Gestión y estructuración de la base de datos relacional mediante consultas `LEFT JOIN` para la integración de entidades y exportación de datos planos.
* **Power BI Desktop (Power Query & DAX):** Importación del archivo estructurado, limpieza de datos, unificación de nombres (`Full_Name`), creación de medidas agregadas en DAX (`DISTINCTCOUNT`, `COUNTA`, `SUM`) y diseño de interfaz ejecutiva (UI/UX) limpia enfocada en métricas macro.
* **Git & GitHub:** Control de versiones y documentación técnica para el portafolio profesional.

---

## 💡 Principales Insights

* **Métricas Financieras Generales:** Balance total consolidado (Total Balance USD) de **$5.98bn** distribuido en una base activa de **14K clientes únicos**, registrando un volumen total de **60K cuentas** y **60K contratos de préstamos**.
* **Distribución por Tipo de Cuenta:** Equilibrio casi perfecto en la captación de saldos entre cuentas *Business* (33.2%), *Checking* (34.11%) y *Savings* (32.7%).
* **Estructura de Tarjetas y Crédito:** Distribución simétrica del parque de tarjetas entre la modalidad de *Credit* (49.91%) y *Debit* (50.09%), acompañada de un análisis de *Credit Score* promedio uniforme en las distintas líneas de producto.
* **Colocación de Créditos (Loans):** Volumen de préstamos (*Total Loan Amount*) distribuido de manera homogénea entre los distintos segmentos de cuentas, alcanzando picos superiores a los $10M por categoría.

---

## 📁 Archivos del Repositorio

El archivo del informe (`.pbix`), la base de datos SQLite (`.db`), el archivo CSV limpio y los scripts de consultas SQL están disponibles en este repositorio para su consulta y revisión técnica.
