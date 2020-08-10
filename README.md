# Subgroup-classification-model-identifying-the-most-influential-factors-in-the-mortality-of-a-patients-with-COVID19-using-data-analysis

Una libreta de Jupyter donde se estudia lo que más afecta la mortalidad de un enfermo con COVID-19.
La libreta usa un total de 3 datasets los cuales permiten separar los grupos de estudio.

## Requerimientos 

* Python 2.7
* Los datasets den este repositorio
* Jupyter Notebook

## Dependencias

* pandas (0.18.1)
* matplotlib (1.5.2)
* numpy (1.11.1) 
* statistics
* sklearn

## Explicacion de los Documentos
- 3.COVID19_analytics_clinical_data.csv
- csvDatasetGrupos.csv
- csvDatasetProvincias.csv
Todos estos son datasets utilizados para el estudio, Son indispensables para que el documento de Jupyter funcione ya que estos son los que contienen toda la información acerca de los enfermos con COVID-19 y fallecidos
- Analisis Covid.ipynb
Es la libreta de Jupyter que procesa los datos, este archivo ejecuta los códigos necesarios para llevar el estudio a cabo.
## Procesos 
Primero se empieza con la limpieza de los datos, lo cual nos ayudara a que este sea más liviano y mejorar su procesamiento, además de que gracias a este se podrán evitar problemas debido a datos nulos o con valores extraños, para conseguir los datos necesarios para este estudio se eliminó toda la información sobre las publicaciones incluidas en el dataset para que no interfieran con el tema de estudio principal. 

Una vez terminada la limpieza se separaron los datos del dataset en ordinales y nominales.
A los datos categorizados como ordinales le aplicamos el método de preprocesamiento StandardScaler() y a los categorizados como nominales se les aplico el OneHotEncoder().

