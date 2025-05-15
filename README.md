Alura Store - Análisis de Ventas y Desempeño por Tienda


![image](https://github.com/user-attachments/assets/5685417b-da95-4775-b056-35c2aae4fcfa)


# Índice

Descripción del Proyecto
Estructura del Proyecto
Gráficos e Insights
Ejecución del Notebook
Tecnologías Utilizadas
Autor
Licencia
Conclusión

## Descripción del Proyecto

Este proyecto consiste en un análisis exploratorio de datos de la tienda "Alura Store", que agrupa información de cuatro tiendas distintas. A través de herramientas de visualización y estadísticas, se busca identificar:

La tienda con mejor y peor desempeño financiero.

Comportamiento por categoría de productos.

Calificaciones promedio de los clientes.

Impacto de los costos de envío.

Productos más y menos vendidos.

El análisis concluye con una recomendación basada en datos sobre cuál tienda debería venderse para optimizar la operación.

## Estructura del Proyecto

AluraStore/
├── AluraStore_Analisis.ipynb     # Notebook principal con todos los análisis y visualizaciones
├── data/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
├── README.md                     # Documentación del proyecto
└── outputs/
    ├── graficos/                 # Carpeta de imágenes generadas
    └── mapa_interactivo.html     # Mapa generado con Folium

Gráficos e Insights

Análisis Financiero

Ingresos brutos y netos por tienda.

Costo total de envío y su proporción.

Comparación por Categoría

Ventas por volumen y por ingreso.

Productos con mejor rotación y mayor facturación.

Satisfacción del Cliente

Calificaciones promedio por tienda.

Geolocalización de Ventas

Mapa de calor y clusterización de puntos de venta en Colombia.

Recomendación Final

Se recomienda vender la Tienda 4 por tener el menor ingreso neto, baja participación en las categorías más rentables y sin ventaja competitiva significativa.

🚀 Ejecución del Notebook

Clona el repositorio:

git clone https://github.com/AlechM-Dev/Reto-1-Alura-Store.git

Instala las dependencias:

pip install -r requirements.txt

Ejecuta el notebook:

jupyter notebook AluraStore_Analisis.ipynb

💻 Tecnologías Utilizadas

Python 3

Pandas para manipulación de datos

Numpy para la creación de dataframes

Seaborn / Matplotlib para visualizaciones

Folium para mapas interactivos

Jupyter Notebook como entorno de trabajo

👨‍💼 Autor

Alejandro Chaurra Morales

📈 Conclusión

Este análisis permite tomar decisiones basadas en datos sobre la operación de una red de tiendas. El uso de visualizaciones, métricas financieras y segmentación por productos y ubicación geográfica proporciona una visión integral y accionable sobre el rendimiento comercial de Alura Store.

