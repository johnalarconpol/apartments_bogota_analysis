Apartamentos disponibles Bogotá
Descripción
Este proyecto tiene como objetivo analizar y explorar datos de apartamentos en Bogotá mediante un Dashboard en PowerBI, con el fin de identificar patrones de precios, ubicación, características del inmueble y posibles insights útiles para análisis inmobiliario y toma de decisiones.

La información obtenida permitira filtrar un inmueble con sus características.

🧱 Estructura del proyecto
📁 proyect_apartments_Bogotá
│
├── 📁 data
│   ├── processed_v2.0.0_august_2_2024.json/    # Datos crudos obtenidos de la fuente
│   └── mi_base_de_datos_limpia.csv/            # Datos limpios y transformados
├── 📁 src
│   └──📄 requirements.txt
├── 📁 notebooks
│   ├── 01_EDA.ipynb                        # Análisis de datos exploratorios
│   ├── README.ipynb                        # Resúmen del proyecto
│   └── dashboard_apartments.pbix           # Tablero de gráficas
└── 📄 .gitignore
Análisis del proyecto
Mediante el EDA se transformaron y agruparon características para poseteriormente crear vistas que permita ver la información de manera organizada y resumida, todo en un dashboard en Power BI.

🛠️ Tecnologías utilizadas
Python 🐍
Pandas / Numpy
Power BI
Jupyter Notebook
Agradecimiento a la fuente de los datos proviene del proyecto de "https://erik172.notion.site/Bogota-Apartments-1c697c876c344f0d9047830ef2254ba4" de la actualización del 2 de agosto del 2024.

Habilidades
limpieza de datos
Visualización de datos
Generación de variables de interés
Resultados
Se realizó un dashboard interactivo dónde se puede observar datos relevantes, a la vez que se puede filtrar sectores específicos para detectar patrones o incluso consultar un inmueble para ver sus características

image.png

🚀 Cómo ejecutar el proyecto
Descargar el dashboard_apartments y abrir en Power BI

Para ejecutar la limpieza
Clonar el repositorio:

git clone https://github.com/johnalarconpol/project_apartments.git

Crear entorno virtual e instalar dependencias:

pip install -r requirements.txt

Ejecutar los scripts de scraping:

python src/scraping/main.py

Ejecutar notebooks de limpieza y análisis.

Recomendaciones
Ejecutar en jupyter notebook y usar power BI directamente

image.png image-2.png

Esté proyecto se realizó exclusivamente con fines didácticos
