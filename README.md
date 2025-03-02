# Explora-Visual_Data_KC
Entrega de práctica Exploración &amp; Visualización Dato DAVID SOTELO SEGUÍN
# README - Práctica de Exploración y Visualización de Datos

## Presentación de la Práctica: Visualización de Datos

Para el desarrollo de esta práctica, se sugirió la posibilidad de utilizar el dataset de Airbnb proporcionado o emplear otras bases de datos. Opté por esta última opción con el objetivo de desarrollar un modelo entidad-relación y un informe compuesto por diversos dashboards que permitan resolver problemas para una organización.

### Problema de Negocio

El problema de negocio abordado en esta práctica consiste en mejorar la rentabilidad de los proyectos que la empresa desarrolla para diferentes clientes. La organización presta servicios a terceros, y más del 75% de su margen de beneficio proviene de la comercialización de las horas de trabajo de sus equipos de desarrollo. Para optimizar la rentabilidad, se propone una herramienta que proporcione información sobre la actividad productiva.

### Estructura del Informe

1. **Análisis del Desempeño en 2024**: Se presenta un análisis global sobre la distribución de las horas de trabajo por cliente en el ejercicio anterior (2024). Se permite la interacción con los datos y la obtención de insights desde diversas dimensiones, centándose principalmente en cliente, tiempo y empleados.

2. **Seguimiento del Desempeño en 2025**: Se proporciona información sobre la evolución del desempeño en el año en curso (2025). Se incluye un panel que permite visualizar la desviación de las horas asignadas a cada cliente mes a mes. Esto facilita que el responsable de rentabilidad evalúe el tiempo pendiente por cliente, analice desviaciones en comparación con otros desempeños y estudie en detalle quiénes están operando para cada cliente y cuántas horas han imputado.

### Datos Utilizados

Todas las bases de datos y la información utilizadas en este desarrollo han sido anonimizadas para garantizar la privacidad y confidencialidad de los datos.

Para el desarrollo de esta práctica, se utilizó un dataset compuesto por diferentes fuentes y archivos:

- **Tiempos\_Exp\_Holded**: Archivo importado del programa utilizado por la organización para realizar el seguimiento de los tiempos de trabajo de los empleados.
- **Tiempos\_Api\_Holded**: Archivo CSV obtenido mediante una ETL conectada al programa de gestión empresarial Holded.
- **Costes**: Archivo exportado de Holded y transformado para resolver problemas de asignación de costes. Dado que la exportación original no individualiza los costes por proyecto, se realizó una imputación basada en el número de proyectos asociados a cada entrada de factura.
- **Ing\_Def2**: Similar al caso anterior, se aplicó una transformación mediante Python para procesar los datos.
- **Proyecto&Cliente**: Tabla generada mediante un script en M para establecer relaciones entre las entidades y la dimensión cliente.
- **Presupuestos\_Clientes270225**: Tabla generada manualmente por la dirección de la empresa, donde se asignan las horas previstas para cada cliente en 2025.
- **Presupuestos\_Proyectos270251**: Similar a la anterior, pero asociando tiempos a proyectos. No se llegó a emplear debido a limitaciones de tiempo en el desarrollo. En un escenario ideal, se podría evaluar y dar seguimiento tanto por proyecto como por cliente.
- **Costes RRHH**: Tablas con los costes por empleado en 2024, permitiendo calcular el coste individualizado por hora y empleado. Esto facilita el seguimiento de la rentabilidad no solo en función de las horas trabajadas, sino también considerando los costes imputables al proyecto y los ingresos generados.

Este informe y la herramienta desarrollada proporcionan una base para la toma de decisiones orientadas a mejorar la rentabilidad de los proyectos y optimizar la asignación de recursos en la organización.

 

