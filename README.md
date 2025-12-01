# Desafío Análisis de Datos – AluraStoreLatam

##  Descripción  
Este proyecto corresponde al desafío de análisis de datos de Alura — “AluraStoreLatam” — en el que se analizan datos de ventas, productos, calificaciones y costos de envío de cuatro tiendas/sucursales. El objetivo es extraer conclusiones útiles sobre qué tienda conviene conservar o vender, entender qué productos y categorías funcionan mejor, y evaluar la distribución espacial de las ventas usando coordenadas (latitud/longitud).

## Contenido del repositorio  
- `AluraStoreLatam.ipynb`: notebook de Jupyter / Colab con todo el análisis, cálculo de métricas, gráficos y conclusiones.  
- (Si lo hay) `data/`: carpeta con los archivos CSV originales de cada tienda.  
- (Si generás) mapas, gráficos exportados, imágenes para presentación, etc.

##  Qué se analiza  
- Ingresos totales por tienda.  
- Distribución de ventas por categoría de producto.  
- Calificación promedio de clientes por tienda.  
- Productos más vendidos y menos vendidos por tienda.  
- Coste promedio de envío por tienda.  
- Análisis geográfico: utilizando coordenadas (latitud/longitud) para mapear las ventas y visualizar su distribución espacial por tienda.

## Resultados principales (resumen)  
- La tienda con mayor facturación general: **Tienda 1**.  
- Las categorías con mayor volumen de ventas: **Muebles** y **Electrónicos**.  
- Mejores calificaciones promedio: **Tienda 3** y **Tienda 2**.  
- Producto más vendido con mejor desempeño: de la **Tienda 2** (mayor cantidad en un SKU).  
- Tienda con menor coste de envío promedio: **Tienda 4**.  
- Con el análisis geográfico se exploran zonas de mayor concentración de ventas, permitiendo estudiar distribución por zona/mercado.  

##  Cómo usar el proyecto  

1. Clonar o descargar el repositorio.  
2. Abrir `AluraStoreLatam.ipynb` en Jupyter/Colab.  
3. Si necesitas, asegurarte de tener instaladas las librerías:  
   ```bash
   pip install pandas matplotlib folium
