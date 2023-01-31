# DA-promoc-modulo3-sprint1-judith-gadea
Repositorio con los trabajos de Gadea Autric y Judith Blanco.


### **Modulo 3: Machine Learning** 

*[Regresión lineal](#Regresión-lineal)

  *[Regresión lineal librería](#Regresión-lineal-libreria)
  
*[Regresión logistica](#Regresión-logistica)

  *[Regresión logistica librería](#Regresión-logistica-libreria)
  
*[Decisión Tree y Ramdon Forest](#Decisión-Tree-y-Ramdon-Forest)

  *[Decisión Tree y Ramdon Forest librería](#Decisión-Tree-y-Ramdon-Forest-librería)


--------------------------
 #### **Regresión lineal**  
 ---------------------------
Es un tipo de aprendizaje automático supervisado. 
Se realiza el análisis de los datos donde se predice el valor de datos de variables continuas, mediante el estudio del 
comportamiento de la misma a través de las variables independientes. 

 - Intro a maching learning
 - Test estadísticos
 - Covarianza y correlación
 - Asunciones regresión lineal
 - Normalización
 - Estandarización
 - Anova
 - Encoding
 - Regresión Lineal Métricas
 - Decision Tree
 - Random Forest

--------------------------
 #### **Regresión lineal librerias **  
 ---------------------------
 
# Tratamiento de datos

** import numpy as np
** import pandas as pd

# Test estadisticos
import researchpy as rp
from scipy import stats
from scipy.stats import kstest
from scipy.stats import levene
from scipy.stats import skew
from scipy.stats import kurtosistest
import statsmodels.api as sm
from statsmodels.formula.api import ols
from statsmodels.multivariate.manova import MANOVA
from sklearn.preprocessing import StandardScaler

# Gráficos
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm

# Transformación de los datos / modelado / evaluación / cross evaluacion
import math 
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor
from sklearn import tree
from sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error
from sklearn.model_selection import GridSearchCV
from tqdm import tqdm
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import cross_validate
from sklearn import metrics

# Codificación de las variables numéricas
from sklearn.preprocessing import LabelEncoder # para realizar el Label Encoding 
from sklearn.preprocessing import OneHotEncoder  # para realizar el One-Hot Encoding

# Configuración warnings
import warnings
warnings.filterwarnings('once')
 
 ----------------------------
 #### **Regresión logistica**
----------------------------
Es un tipo de aprendizaje automático supervisado. 
Se realiza el análisis de los datos donde se predice el valor de datos de variables discretas dicotómicas, mediante el estudio del 
comportamiento de la misma a través de las variables independientes. 

 - EDA
 - Preparacion_Datos
 - Ajuste
 - Metricas
 - Decision_Tree
 - Random_Forest

------------------------------
 #### **Decisión Tree y Ramdon Forest**
--------------------------------




