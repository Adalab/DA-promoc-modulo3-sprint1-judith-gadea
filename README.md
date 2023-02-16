# DA-promoc-modulo3-sprint1-judith-gadea

***Repositorio con los trabajos de Judith Blanco y Gadea Autric***


----------------------------
## Modulo 3: Machine Learning
--------------------------------------------------


*[Regresión lineal](#Regresión-lineal)

*[Regresión logistica](#Regresión-logistica)

*[Decisión Tree y Ramdon Forest](#Decisión-Tree-y-Ramdon-Forest)

*[Librerías](#Librerías)


---------------------------
### Regresión lineal
 ---------------------------
 
   *  [Carpeta RL](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RL)

 Contiene todos los ficheros utilizados en el desarrollo del estudio, análisis y preparación de nuestro modelo de Regresión lineal mediante el cual queremos predecir los quilates de un conjunto de diamantes.
 

***La creación de nuestro modelo de regresión lineal se ha estructurado de la siguienta manera:***

    1 EDA (Exploración y limpieza de los datos)
    1 Test Estadísticos
    2 Correlación y Covarianza
    3 Asunciones
    4 Normalización
    5 Estandardizacion
    6 Anova
    7 Encoding
    8 Regresion lineal
    9 Regresion lineal Métricas
    10 Decision tree
    11 Random Forest

 
 
   *  [Carpeta Datos](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RL/datos)
     
   Se encuentran los archivos generados.
 
 
 

   
   
   
 
 
---------------------------
### Regresión logística
---------------------------
  
  *  [Carpeta RLog](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RLog)

 Contiene todos los ficheros utilizados en el desarrollo del estudio, análisis y preparación de nuestro modelo de Regresión logística mediante el cual queremos predecir, el porcentaje de  personas que hiceron click en un anuncio o no.


***La creación de nuestro modelo de regresión logística se ha estructurado de la siguienta manera:***

    1 EDA (Exploración y limpieza de los datos)
    2 Preparación de Datos
    3 Ajuste
    4 Métricas
    5 Decisión Tree
    6 Random Forest 
    
    
    
   *  [Carpeta Datos](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RLog/datos)
      
   Se encuentran los archivos generados.



  
 
 


-----------------------------
### Decisión Tree y Ramdon Forest
--------------------------------


   *  [Carpeta RL Decision Tree](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RL/RL-11-DecisionTree.ipynb)
   
   *  [Carpeta RL Ramdon Forest](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RL/RL-12-RandomForest_tree.ipynb)

   *  [Carpeta RLog Decision Tree](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RLog/RLo-5-DecTree.ipynb)

   *  [Carpeta RLog Ramdon Forest](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RLog/RLo-6-Ran-Forest.ipynb)




-----------------------------
### Librerías
--------------------------------

    Tratamiento de datos:
    
    import numpy as np
    import pandas as pd
    from tqdm import tqdm

    
    Representación de Gráficos:
    
    import matplotlib.pyplot as plt
    import seaborn as sns
    import statsmodels.api as sm
    plt.rcParams["figure.figsize"] = (15,15)
    

    Test estadisticos:
    
    researchpy 
    scipy import stats
    statsmodels.api as sm
    from scipy.stats import kstest
    from scipy.stats import levene
    from scipy.stats import skew
    from scipy.stats import kurtosistest
    from statsmodels.formula.api import ols
    from sklearn.preprocessing import StandardScaler
    
    Transformación, modelado y evaluación de los datos:
    
    from sklearn.preprocessing import MinMaxScaler
    from sklearn.preprocessing import StandardScaler
    from sklearn.model_selection import train_test_split
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.ensemble import RandomForestRegressor
    from sklearn import tree
    import math
    from sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error
    from sklearn.model_selection import GridSearchCV
    from sklearn.model_selection import cross_val_score
    from sklearn.model_selection import cross_validate
    from sklearn import metrics

    Encoding:
    
    from sklearn.preprocessing import LabelEncoder 
    from sklearn.preprocessing import OneHotEncoder  
    
    Gestión datos desbalanceados:
    
    from imblearn.under_sampling import RandomUnderSampler
    from imblearn.over_sampling import RandomOverSampler
    from imblearn.combine import SMOTETomek

    Configuración warnings:
    
    import warnings
    warnings.filterwarnings('once')
 
 
    
Integrantes
----------------


[Judith Blanco](https://github.com/Jumblan)

[Gadea Autric](https://github.com/gadeatric/gadeatric)







