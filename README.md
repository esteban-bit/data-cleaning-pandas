 [![LinkedIn][linkedin-shield]][linkedin-url]
<!-- PROJECT LOGO -->

<div align="center">
  <a href="https://www.kaggle.com/datasets/teajay/global-shark-attacks/">
    <img src="imagenes/Data-Cleansing-Strategies.png" alt="Logo" width="1000" height="150">
  </a>

  <h3 align="center" style="font-size: 25px">Limpieza y procesamiento de datos con Python</h3>
    <br />
  <p align="center">
    Se analiza el siguiente archivo de Kaggle:
    
 ``Global Shark Attacks``
    <br />
    <br />
      <a href="https://www.kaggle.com/datasets/teajay/global-shark-attacks/">
        <img src="imagenes/kaggle.png" alt="Logo" width="80" height="80">
    </a>
    <br />
    <a href="https://www.kaggle.com/datasets/teajay/global-shark-attacks/">Kaggle</a>
    
  </p>
</div> 

## Objetivo

Identificar los patrones y tendencias en los ataques de tiburones a lo largo del tiempo y en diferentes países.

¿Ha habido un aumento o disminución en los ataques de tiburones a lo largo de los años?

¿Existen ciertos meses o estaciones del año en los que se producen más ataques de tiburones?

¿Cuáles son los países con mayor incidencia de ataques de tiburones?

¿Cuál es el tipo de ataque más común (provocado o no provocado)?

¿Existe alguna relación entre las actividades humanas y los ataques de tiburones? 

## Proceso

Se realiza el proceso a traves de Python.

Instalamos las librerias :
```
%pip install ipython
%pip install seaborn
```
Importamos las librerias :
```
import pandas as pd
import numpy as np

# para pintar
import pylab as plt    
import seaborn as sns

# para que salga el grafico

%matplotlib inline
```
Cargamos los datos
``````
tiburon= pd.read_csv('/Users/esteban/Phyton/w2_project_pandas/data/attacks.csv', encoding= 'latin-1')
``````
Se realiza la limpieza de los datos nulos:

```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 25723 entries, 0 to 25722
Data columns (total 24 columns):
 #   Column                  Non-Null Count  Dtype  
---  ------                  --------------  -----  
 0   Case Number             8702 non-null   object 
 1   Date                    6302 non-null   object 
 2   Year                    6300 non-null   float64
 3   Type                    6298 non-null   object 
 4   Country                 6252 non-null   object 
 5   Area                    5847 non-null   object 
 6   Location                5762 non-null   object 
 7   Activity                5758 non-null   object 
 8   Name                    6092 non-null   object 
 9   Sex                     5737 non-null   object 
 10  Age                     3471 non-null   object 
 11  Injury                  6274 non-null   object 
 12  Fatal (Y/N)             5763 non-null   object 
 13  Time                    2948 non-null   object 
 14  Species                 3464 non-null   object 
 15  Investigator or Source  6285 non-null   object 
 16  pdf                     6302 non-null   object 
 17  href formula            6301 non-null   object 
 18  href                    6302 non-null   object 
 19  Case Number.1           6302 non-null   object 
 20  Case Number.2           6302 non-null   object 
 21  original order          6309 non-null   float64
 22  Unnamed: 22             1 non-null      object 
 23  Unnamed: 23             2 non-null      object 
dtypes: float64(2), object(22)
memory usage: 4.7+ MB 
```


## Recursos

[Data Cleaning Tutorial](https://www.tutorialspoint.com/python/python_data_cleansing.html)

[Data Cleaning with Numpy and Pandas](https://realpython.com/python-data-cleaning-numpy-pandas/#python-data-cleaning-recap-and-resources)

[Data Cleaning Video](https://www.youtube.com/watch?v=ZOX18HfLHGQ)

[Data Preparation](https://www.kdnuggets.com/2017/06/7-steps-mastering-data-preparation-python.html)

[Google Search](https://www.google.es/search?q=how+to+clean+data+with+python)
  


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/esteban-cardona-60163685/