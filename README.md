# connectatel-customer-analysis
# 📊 ConnectaTel - Análisis y Segmentación de Clientes

## 📌 Descripción del proyecto

Este proyecto analiza datos de clientes y uso de servicios de ConnectaTel con el objetivo de identificar problemas de calidad de datos, estudiar patrones de comportamiento y crear segmentos de clientes que puedan apoyar la toma de decisiones comerciales.

## 🎯 Objetivos

- Explorar y limpiar los datasets.
- Identificar valores faltantes, sentinels y fechas inválidas.
- Analizar el comportamiento de llamadas y mensajes.
- Detectar valores atípicos mediante IQR.
- Segmentar clientes según edad y nivel de uso.
- Generar recomendaciones comerciales basadas en los resultados.

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔎 Proceso de análisis

1. Carga y exploración de datos.
2. Identificación de problemas de calidad.
3. Limpieza y transformación.
4. Agregación de métricas por usuario.
5. Análisis exploratorio y visualización.
6. Detección de outliers.
7. Segmentación de clientes.
8. Generación de insights para el negocio.

## 📊 Segmentación

Los clientes fueron clasificados según dos dimensiones:

### Nivel de uso
- Bajo uso
- Uso medio
- Alto uso

### Edad
- Joven
- Adulto
- Adulto Mayor

## 💡 Principales hallazgos

Se identificaron valores faltantes, sentinels y fechas fuera del periodo válido que requirieron limpieza antes del análisis.

También se detectaron usuarios con niveles de consumo superiores al comportamiento habitual. Estos valores se conservaron al considerarse comportamientos posibles y potencialmente relevantes para el negocio.

La segmentación permitió identificar diferentes perfiles de clientes según su edad y nivel de utilización de los servicios.

## 🚀 Recomendaciones

- Desarrollar ofertas específicas para clientes de alto uso.
- Crear estrategias de upselling para usuarios de uso medio.
- Analizar estrategias de retención para clientes de bajo uso.
- Incorporar variables como churn, plan y comportamiento de uso en futuros análisis.

## 📁 Archivos

- `ConnectaTel_Analisis_Clientes.ipynb`: análisis completo del proyecto.

## 👤 Autor

Sebastian Sotomayor
