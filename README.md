# Análisis de Churn en Telecomunicaciones - TelecomX LATAM

Este libro explora el análisis de cancelación de clientes (churn) en una empresa de telecomunicaciones de LATAM, utilizando Python y herramientas de ciencia de datos. El objetivo es identificar los factores que influyen en la pérdida de clientes y proponer estrategias para mejorar la retención.

## Contenido

- **Extracción y transformación de datos:**  
  Se parte de un archivo JSON con información de clientes, servicios y cuentas. Los datos se normalizan y limpian para facilitar el análisis.

- **Análisis exploratorio:**  
  Se utilizan visualizaciones (gráficos de pastel, barras, boxplots, etc.) para entender la distribución de churn y sus relaciones con variables como género, edad, estado civil, dependientes, tipo de contrato, servicios de internet y método de pago.

- **Hallazgos clave:**  
  - Mayor churn en clientes jóvenes, solteros y sin dependientes.
  - Contratos de corto plazo y métodos de pago como cheque electrónico presentan mayor tasa de cancelación.
  - Muchos clientes con fibra óptica no contratan servicios complementarios.

- **Recomendaciones estratégicas:**  
  - Incentivar contratos a largo plazo.
  - Ofrecer paquetes combinados de servicios.
  - Promover métodos de pago automáticos.
  - Campañas específicas para jóvenes y solteros.

## Uso

1. Asegúrate de tener Python 3 y las siguientes librerías instaladas:
   - pandas
   - matplotlib
   - seaborn

2. Coloca el archivo `TelecomX_Data.json` en el mismo directorio que el notebook.

3. Abre y ejecuta el notebook `TelecomX_LATAM entregable.ipynb` para reproducir el análisis y las visualizaciones.

## Estructura del proyecto

- `TelecomX_LATAM entregable.ipynb`: Notebook principal con todo el análisis.
- `TelecomX_Data.json`: Fuente de datos.
- Gráficos y resultados generados en el notebook.

## Autoría

Proyecto realizado como parte de un challenge de análisis de datos para Alura LATAM.

---

¡Explora el notebook para más detalles y visualizaciones!