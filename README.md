# Challenge_TelecomX_LATAM

## Descripción del Proyecto

Este proyecto analiza datos de clientes de TelecomX en LATAM con el objetivo de identificar patrones de cancelación de servicios. Utiliza técnicas de limpieza, transformación y visualización de datos para obtener insights clave sobre la evasión de clientes.


## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- Extracción: Obtención de datos desde un archivo JSON alojado en GitHub.

- Transformación: Limpieza y procesamiento de datos, incluyendo conversión de valores, tratamiento de valores nulos y mapeo de características categóricas.

- Análisis Exploratorio: Visualización de patrones en la cancelación de clientes según distintos factores.

- Resultados y Conclusiones: Interpretación de hallazgos sobre la evasión y recomendaciones basadas en los análisis.
  

## Requisitos y Dependencias

Para ejecutar este proyecto, asegúrate de contar con:

- Python 3.x

- Pandas

- NumPy

- Matplotlib

- Seaborn

Puedes instalar las dependencias con:

```
pip install pandas numpy matplotlib seaborn
```


## Uso del Proyecto

1. Clona el repositorio:
   ```
    git clone <URL-del-repositorio>
    ```
   
3. Abre el archivo TelecomX_LATAM.ipynb en Google Colab o Jupyter Notebook.
4. Ejecuta todas las celdas para obtener los análisis y visualizaciones.


## Datos Utilizados

Los datos provienen del archivo TelecomX_Data.json, que contiene información sobre clientes, planes de servicios, pagos y duración de contratos. Se han realizado transformaciones para mejorar la calidad de los datos y facilitar el análisis.

## Resultados y Conclusiones

El análisis revela que:

- Clientes con contratos mes a mes tienen mayor tasa de cancelación.

- Método de pago influye en la retención de clientes, donde los pagos electrónicos muestran mayor cancelación.

- Cantidad de servicios contratados impacta directamente en la lealtad del usuario.

Las visualizaciones generadas en el notebook permiten observar tendencias clave, facilitando la toma de decisiones estratégicas.
