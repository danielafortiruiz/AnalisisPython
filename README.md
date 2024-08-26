# 📊 **Desarrollo del Proyecto** 🚀

## **Metodología de Recopilación y Selección de Datos** 🧩

Para llevar a cabo este proyecto, utilizamos una metodología de recopilación y selección de datos exhaustiva y precisa. Inicialmente, recibimos una base de datos extensa que contenía más de 12 millones de filas de datos relacionados con la pandemia de COVID-19 en varios países. 

**Pasos clave:**

1. **Filtrado inicial**: Utilizamos Python para reducir el conjunto de datos a solo los países latinoamericanos de interés para el laboratorio: **Argentina, Perú, Brasil, Colombia, Chile y México**.
2. **Filtro por fechas**: Seleccionamos datos desde el 1 de enero de 2021 en adelante.
3. **Transformaciones de datos**: Mejoramos la calidad del conjunto de datos convirtiendo formatos de fecha a datetime y cambiando valores de objeto a numéricos para cálculos precisos.

**Librerías utilizadas:**

- **Pandas**: Para manejar y analizar datos en formato tabular.
- **NumPy**: Para cálculos matemáticos rápidos.
- **Seaborn**: Para gráficos estadísticos atractivos.
- **Matplotlib**: Para diseñar y personalizar gráficos.

Estas herramientas nos permiten analizar datos y visualizar la información de manera efectiva.

---

## **Transformaciones y Limpieza de Datos** 🧹

Las técnicas de limpieza y filtrado aplicadas en Python han permitido reducir considerablemente el volumen de datos a analizar. 

<p align="center">
  <img src="https://github.com/danielafortiruiz/AnalisisPython/blob/main/img%20python%20.png?raw=true" alt="Imagen Python" />
</p>


**Técnicas implementadas:**

- **Eliminación de valores nulos**: Se eliminaron o imputaron valores faltantes.
- **Normalización de datos**: Ajuste de escalas y unidades para comparabilidad.
- **Creación de columnas calculadas**: Tasas de incidencia, tasas de vacunación, etc.

La metodología utilizada ha proporcionado una base sólida para el análisis, permitiendo generar información clave para Biogénesis en su estrategia de expansión.

---

## **Análisis Exploratorio de Datos (EDA) y Principales Insights** 🔍

**Evolución de la Pandemia:**

- **Nuevos Casos Mensuales por País**: Tendencia descendente en la mayoría de los países latinoamericanos. **Brasil** muestra un incremento reciente en los casos.
- **Casos Activos vs. Casos Recuperados**: Disminución de casos activos y aumento de casos recuperados.

**Vacunación:**

- **Número Máximo de Dosis Administradas por País**: **Brasil** lidera en la administración de dosis, seguido por **Argentina** y **México**. **Chile** reporta el menor número.
- **Tendencia de Dosis Administradas por Mes**: Aumento significativo en la administración de dosis.

**Mortalidad:**

- **Tasas de Mortalidad por Género y Edad**: Las tasas son más altas en hombres y las tasas de mortalidad infantil son relativamente bajas en la mayoría de los países, salvo en **Brasil**.

---

## **Aspectos a Considerar** ⚠️

- **Variantes del Virus**: Datos actuales no incluyen variantes del SARS-CoV-2. Es crucial considerar su impacto en la pandemia y la demanda de vacunas.
- **Tasas de Vacunación**: No se detallan las tasas de vacunación por país o grupo etario. Analizar estas tasas es fundamental.
- **Efectividad de las Vacunas**: La información sobre la efectividad frente a variantes del virus no está reflejada. Monitorear estudios recientes es esencial.

---

## **Consecuencias y Recomendaciones Estratégicas** 🛠️

**Vacunación:**

- **Desigualdad en el Acceso**: Disparidad notable en la distribución de vacunas. Implementar estrategias para ampliar el acceso.
- **Desafíos Logísticos**: Crear estrategias logísticas robustas para asegurar una distribución equitativa.
- **Aceptación de las Vacunas**: Llevar a cabo campañas de comunicación para promover la aceptación de vacunas.

**Mortalidad:**

- **Identificación de Factores de Riesgo**: Investigar factores que influyen en la mortalidad por COVID-19.
- **Impacto en los Sistemas de Salud**: Colaborar con gobiernos locales para fortalecer infraestructuras de salud.

**Evolución de la Pandemia:**

- **Variantes del Virus**: Considerar la aparición de variantes más contagiosas.
- **Tasas de Vacunación**: Realizar un análisis más profundo para identificar áreas con menor cobertura.
- **Efectividad de las Vacunas**: Monitorizar la eficacia de las vacunas para ajustar estrategias de vacunación.



