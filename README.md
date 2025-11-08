Proyecto: Analisis de Ventas - Alura Store

Proposito del analisis
El objetivo de este proyecto fue analizar los datos de las cuatro tiendas de la Alura Store para determinar cual seria la mejor opcion para que el Sr. Juan venda.
Se revisaron aspectos como:
- Ingresos totales.
- Categorias de productos.
- Calificaciones promedio de los clientes.
- Productos mas y menos vendidos.
- Costos de envio promedio.
Con base en estos indicadores, se elaboro una recomendacion final sobre cual tienda destaca mas y por que.

------------------------------------------------------------

Estructura del proyecto
El proyecto esta organizado de la siguiente manera:

alura_store/
analisis_tiendas.ipynb      Notebook principal con el analisis y graficos
data/                       Carpeta con los archivos de datos (CSV)
tienda_1.csv
tienda_2.csv
tienda_3.csv
tienda_4.csv
README.md                   Documento explicativo del proyecto

------------------------------------------------------------

Ejemplos de graficos e insights

1. Ingreso total por tienda
   Grafico de barras para comparar ingresos entre tiendas.
   La Tienda 3 presenta los ingresos mas altos.

2. Distribucion de categorias
   Grafico de columnas por tienda.
   Permite ver que tipo de productos se venden mas en cada una.

3. Precio vs Costo de Envio
   Grafico de lineas que muestra como cambia el costo de envio en relacion al precio.
   En general, las tiendas con precios mayores tienden a tener envios mas caros.

Conclusion general
La Tienda 3 es la mas rentable en ingresos, aunque la Tienda 1 tiene mejor valoracion de clientes y la Tienda 2 mantiene los costos de envio mas bajos.

------------------------------------------------------------

Instrucciones para ejecutar el notebook

1. Clona este repositorio:
   git clone https://github.com/tuusuario/alura-store.git
   cd alura-store

2. Abre el archivo analisis_tiendas.ipynb en Google Colab o Jupyter Notebook.

3. Si trabajas de forma local, instala las librerias necesarias:
   pip install pandas matplotlib

4. Ejecuta las celdas del notebook en orden para generar los calculos y graficos.

------------------------------------------------------------

Proyecto desarrollado como parte del Challenge Alura ONE - Data Science.
