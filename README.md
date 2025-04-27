# Projetos  
## Titanic
Este banco de dados faz parte de uma [competição no Kaggle](https://www.kaggle.com/competitions/titanic). Este banco de dados é referente ao acidente do Titanic, cada linha representa um passageiro e contém algumas informações sobre ele. O banco de dados contém 1309 linhas e 11 colunas. As colunas são:
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

Python

[Random Forest](projects/titanic%20RF%20Python.pdf)\
[Regressão Logística](projects/titanic%20LR%20Python.pdf)


R 

[Random Forest](projects/titanic%20RF%20R.pdf)\
[Regressão Logística](projects/titanic%20LR%20R.pdf)

## Vendas
Este banco de dados foi retirado do [Kaggle](https://www.kaggle.com/datasets/podsyp/time-series-starter-dataset). É um banco de dados fictício que contém uma série temporal sobre vendas. Cada linha representa um mês do ano, de Janeiro de 2015 a Dezembro de 2022. O banco contém 96 linhas e 5 colunas. As colunas são:
- Period: índice referente a cada mês;
- Revenue: receita referente ao mês;
- Sales_quantity: quantidade de vendas;
- Average_cost: custo médio mensal;
- The_average_annual_payroll_of_the_region: média da folha de pagamento em cada mês.

O objetivo é criar um modelo preditivo da receita para os próximos anos.

[Python](projects/TS%20Python.pdf)
