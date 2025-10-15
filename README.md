# NBA Datos

Este repositorio contiene un análisis exploratorio de datos (EDA) sobre estadísticas de la NBA utilizando notebooks de Jupyter. La reorganización de carpetas facilita la colaboración y el mantenimiento del proyecto.

## Estructura del proyecto

```
.
├── data/
│   └── raw/              # Archivos CSV originales descargados de Kaggle
├── notebooks/
│   └── nba_datos.ipynb   # Notebook principal con el análisis
├── requirements.txt      # Dependencias necesarias para ejecutar el notebook
└── README.md             # Información general del proyecto
```

## Requisitos

Utiliza un entorno virtual y ejecuta el siguiente comando para instalar las dependencias:

```bash
pip install -r requirements.txt
```

## Uso

1. Clona el repositorio y navega a la carpeta del proyecto.
2. Instala las dependencias indicadas anteriormente.
3. Abre el notebook `notebooks/nba_datos.ipynb` en Jupyter Lab o Jupyter Notebook para explorar el análisis.

## Datos

Los archivos CSV en `data/raw/` se mantuvieron sin modificaciones y corresponden a datasets públicos de la NBA. Si necesitas actualizar los datos, reemplaza los archivos existentes conservando la misma estructura de carpetas.
