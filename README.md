# Projetos
<details>
<summary> Python </summary>
  
## Titanic
Este banco de dados faz parte de uma [competição no Kaggle](https://www.kaggle.com/competitions/titanic). Este banco de dados é referente ao acidente do Titanic, cada linha representa um passageiro e contém algumas informações sobre ele. O banco de dados contém 1309 linhas e 11 colunas:
- PassengerId: índice de cada observação;
- Survived: valor que indica se a pessoa sobreviveu ao acidente ou não (0 = não sobreviveu, 1 = sobreviveu);
- Pclass: valor que indica a qual classe o ticket pertence (1 = 1ª classe, 2 = 2ª classe, 3 = 3ª classe);
- Sex: valor que indica qual o gênero da pessoa (male = masculino, female = feminino);
- Age: valor que indica a idade da pessoa;
- SibSp: número de filhos e cônjuges à bordo;
- Parch: número de pais e filhos à bordo;
- Ticket: número do ticket;
- Fare: quantia da tarifa paga pela pessoa;
- Cabin: número da cabine;
- Embarked: local de embarque (C = Cherbourg, Q = Queenstown, S = Southampton);
- Name: nome da pessoa.

O objetivo é criar um modelo preditivo para prever se uma pessoa vai ou não morrer baseado nas variáveis fornecidas.

<details>
<summary> Machine Learning </summary>
  
```
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
import scipy as sp
import sklearn as skl
import statsmodels.formula.api as smf
from statsmodels.tools import add_constant
from sklearn.experimental import enable_iterative_imputer
from sklearn.impute import IterativeImputer
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, confusion_matrix, precision_score, recall_score, ConfusionMatrixDisplay, roc_curve, roc_auc_score, root_mean_squared_error, precision_recall_curve
from sklearn.model_selection import RandomizedSearchCV, train_test_split, cross_val_score, StratifiedKFold, cross_val_predict
from scipy.stats import randint
```
<!-- SAIDA-EXECUCAO -->
<!-- SAIDA-EXECUCAO -->
```bash

```
<!-- FIM-SAIDA-EXECUCAO -->
<!-- FIM-SAIDA-EXECUCAO -->
</details>
</details>
