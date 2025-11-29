# Challenge Alura Store - Data Science

Este proyecto analiza los datos de cuatro tiendas de **Alura Store** con
el objetivo de ayudar al Sr. Juan a decidir qué tienda vender para
iniciar un nuevo emprendimiento.

## Objetivos del proyecto

-   Cargar y manipular datos CSV con **Pandas**.
-   Crear visualizaciones de datos con **Matplotlib**.
-   Analizar métricas clave:
    -   Ingresos
    -   Categorías más vendidas
    -   Reseñas de clientes
    -   Productos más y menos vendidos
    -   Costo de envío promedio
    -   Distribución geográfica de las ventas (extra)

## Estructura de los datos

Los datos de cada tienda se cargan en DataFrames independientes:

-   `store1`
-   `store2`
-   `store3`
-   `store4`

Cada DataFrame contiene información de pedidos, productos, precios,
reseñas y, cuando está disponible, información de envío y
geolocalización.

## Análisis realizados

1.  **Ingreso total por tienda**\
2.  **Ventas por categoría**\
3.  **Valoración media por tienda**\
4.  **Productos más y menos vendidos**\
5.  **Costo de envío promedio**\
6.  **Análisis geográfico (extra)**

## Visualizaciones

Se generan al menos 3 tipos de gráficos con **Matplotlib**: - Barras\
- Barras horizontales\
- Gráficos de dispersión\
- Otros opcionales

## Recomendación final

Se construye un **score de eficiencia** combinando ingresos, rating y
costos. La tienda con peor desempeño es recomendada para ser vendida.

## Cómo ejecutar el proyecto

1.  Clonar repositorio original\
2.  Ejecutar código base\
3.  Ejecutar este notebook

## Dependencias

    pip install pandas numpy matplotlib

Proyecto creado para el **Challenge de Data Science de Alura Latam**.
