# Pre-entrega: Adquisición y Normalización con Pandas

## Descripción
En este proyecto trabajé con datos ficticios de ventas de una perfumería. 
El objetivo fue integrar información de dos archivos diferentes, limpiar los datos y generar un dataset final.

## Archivos
- ventas.csv: registro de transacciones.
- productos.xlsx: catálogo de productos.
- preentrega_pandas_ventas.ipynb: código del proyecto.
- ventas_normalizadas.parquet: dataset final.
- requirements.txt: librerías utilizadas.

## Proceso realizado
1. Carga de archivos CSV y Excel con Pandas.
2. Conversión de fechas y valores numéricos.
3. Eliminación de registros con datos críticos faltantes.
4. Unión de ambas fuentes mediante id_producto.
5. Cálculo de total_venta.
6. Exportación del resultado a Parquet.

## Cómo ejecutar
1. Abrir el notebook en Google Colab.
2. Instalar las librerías de requirements.txt si hace falta.
3. Ejecutar las celdas en orden.

## Librerías
- pandas
- openpyxl
- pyarrow
