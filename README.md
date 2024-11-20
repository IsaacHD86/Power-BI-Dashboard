# Power-BI-Dashboard
# link para visualizar el Dashboard  https://app.powerbi.com/groups/me/reports/efd73fe7-d09b-4bfc-9e0d-e2ddfc37ff9f/2d2d540bf5c740d81300?experience=power-bi
Dashboard sobre COVID con Power BI.

### Análisis de Casos de COVID-19
Descripción General.                                                                                                                                
Fuente de Datos: Universidad Johns Hopkins (Datos globales de casos de COVID-19).                                                                                              
Objetivo: Crear un reporte interactivo en Power BI utilizando DAX para contestar preguntas clave relacionadas con los casos de COVID-19 a nivel global.                               

### mportación y Transformación de Datos
Carga de Datos:                                                                                                                    
Importa el archivo con datos de casos globales a Power BI.                                                                                                   
Realiza una limpieza básica (formato de columnas, eliminación de valores nulos, transformación de tipos de datos).                                                           

Columnas Relevantes:                                                                       
Country/Region: País o región.                                                                              
Date: Fecha de reporte.                                                                         
Confirmed: Casos confirmados.                                                                         
Deaths: Decesos.                                                                          
Recovered: Recuperados.                                                                                                              

Transformaciones Necesarias.
Creación de Métricas (Measures).

### Responder las Preguntas
Top 10 Países con Más Contagios:
Usa un gráfico de barras para mostrar los países con el total de casos confirmados utilizando la medida [Total Confirmed].

Top 10 Países con Más Decesos:
Crea un gráfico similar al anterior con la medida [Total Deaths].

Tasa de Mortalidad (Top 10 Más Alta y Más Baja):
Crea un gráfico de barras apiladas con la medida [Mortality Rate].
Filtra los valores para mostrar los 10 países con las tasas más altas y más bajas.

Índice de Recuperación:
Crea un gráfico con la medida [Recovery Rate] y aplica filtros para mostrar los países con el índice más alto.

Curva de Contagios Diarios en México:
Usa un gráfico de líneas con las columnas Date y [Daily Cases], filtrando el país a "México".

### Conclusiones del Reporte
Información obtenida:
Identificamos los países más afectados por la pandemia.                                   
Calculamos tasas de mortalidad y recuperación a nivel global.                                       
Analizamos la evolución diaria de los contagios en un país específico.                                          

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
