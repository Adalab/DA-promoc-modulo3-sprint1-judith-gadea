

----------------------------
## Machine Learning
--------------------------------------------------


*[Regresión lineal](#Regresión-lineal)

*[Regresión logistica](#Regresión-logistica)

*[Decisión Tree y Ramdon Forest](#Decisión-Tree-y-Ramdon-Forest)

*[Librerías](#Librerías)


---------------------------
### Regresión lineal
 ---------------------------
 
   *  [Carpeta Regresion lineal](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RL)

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
  
  *  [Carpeta Regresion logistica](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RLog)

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
    
    numpy as np
    pandas as pd
    tqdm import tqdm

    
    Representación de Gráficos:
    
    matplotlib.pyplot as plt
    seaborn as sns
    statsmodels.api as sm
    plt.rcParams["figure.figsize"] = (15,15)
    

    Test estadisticos:
    
    researchpy 
    scipy import stats
    statsmodels.api as sm
    scipy.stats import kstest
    scipy.stats import levene
    scipy.stats import skew
    scipy.stats import kurtosistest
    statsmodels.formula.api import ols
    sklearn.preprocessing import StandardScaler
    
    Transformación, modelado y evaluación de los datos:
    
    sklearn.preprocessing import MinMaxScaler
    sklearn.preprocessing import StandardScaler
    sklearn.model_selection import train_test_split
    sklearn.tree import DecisionTreeRegressor
    sklearn.ensemble import RandomForestRegressor
    sklearn import tree
    math
    sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error
    sklearn.model_selection import GridSearchCV
    sklearn.model_selection import cross_val_score
    sklearn.model_selection import cross_validate
    sklearn import metrics

    Encoding:
    
    sklearn.preprocessing import LabelEncoder 
    sklearn.preprocessing import OneHotEncoder  
    
    Gestión datos desbalanceados:
    
    imblearn.under_sampling import RandomUnderSampler
    imblearn.over_sampling import RandomOverSampler
    imblearn.combine import SMOTETomek

    Configuración warnings:
    
    warnings
    warnings.filterwarnings('once')
 
 
    
Integrantes
----------------


[Judith Blanco](https://github.com/Jumblan)

[Gadea Autric](https://github.com/gadeatric/gadeatric)







