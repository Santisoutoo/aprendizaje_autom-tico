# Proyecto de Análisis y Modelado de Datos

Este proyecto incluye varios notebooks y archivos para realizar análisis exploratorio de datos, modelado de regresión y análisis de clusterización. También contiene carpetas organizadas para la persistencia de modelos y datos relevantes.

## Estructura del Proyecto

```
├── EDA
│   ├── datos_clasificacion.csv
│   ├── df_standardized.csv
│   └── proy_escuela_dev.csv
├── Persistencia
│   ├── Regresion
│   ├── Clasificacion
│   └── Clusterizacion
├── N01_EDA.ipynb
├── N02_MODELO_NORMALIZED.ipynb
├── N02_MODELO_STANDARIZED.ipynb
├── N04_CLUSTERIZACION.ipynb
├── N04_2_CLUSTERIZACION_TEST.ipynb
├── requirements.txt
└── README.md
```


## Instalación de Dependencias

### Crear un Entorno Virtual
1. Crea un entorno virtual utilizando Python:
   ```bash
   python -m venv env

2. Activa el entorno virtual:
    ```bash
    source env/bin/activate
    ```
3. Instala las dependencias necesarias:
    ```bash
    pip install -r requirements.txt
    ```
## Análisis Exploratorio de Datos (EDA)

El notebook `N01_EDA.ipynb` contiene el análisis exploratorio de datos. Pasos para ejecutarlo:
1. Abre el notebook en Jupyter:
    ```bash
    jupyter notebook N01_EDA.ipynb
    ```
2. Ejecuta las celdas para cargar y analizar los datos.

## Modelado de Regresión

El notebook `N02_MODELO_NORMALIZED.ipynb` realiza el modelado de regresión utilizando datos normalizados. Pasos para ejecutarlo:
1. Abre el notebook en Jupyter:
    ```bash
    jupyter notebook N02_MODELO_NORMALIZED.ipynb
    ```

## Clusterización

El notebook `N04_CLUSTERIZACION.ipynb` contiene el análisis de clusterización. Pasos para ejecutarlo:
1. Abre el notebook en Jupyter:
    ```bash
    jupyter notebook N04_CLUSTERIZACION.ipynb
    ```

El notebook `N04_2_CLUSTERIZACION_TEST.ipynb` también realiza un análisis de clusterización de prueba para ver la relación entre aspectos sociales y académicos. Pasos para ejecutarlo:
1. Abre el notebook en Jupyter:
    ```bash
    jupyter notebook N04_2_CLUSTERIZACION_TEST.ipynb
    ```

## Persistencia de Modelos

Los modelos entrenados y otros objetos importantes se guardan en la carpeta `Persistencia`.
