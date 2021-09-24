# Predicting_defaults_on_loan_obligations
This repo is a part of my portfolio of data science projects completed by me for academic, self learning, and hobby purposes.
____
# Задача

**На основании имеющихся данных о клиентах банка, построить модель, используя датасет для обучения, для прогнозирования невыполнения долговых обязательств по текущему кредиту. Выполнить прогноз для примеров из тестового датасета.**

**Наименование файлов с данными**

course_project_train.csv - датасет для обучения<br>
course_project_test.csv - тестовый датасет<br>
course_project_answers.csv - датасет с ответами

**Целевая переменная**

Credit Default - факт невыполнения кредитных обязательств

**Метрика качества**

F1-score (sklearn.metrics.f1_score)

**Требования к решению**

*Целевая метрика*
* F1 > 0.5, Precision > 0.5, recall > 0.5
* Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)
____
## Описание датасета

* **Home Ownership** - домовладение
* **Annual Income** - годовой доход
* **Years in current job** - количество лет на текущем месте работы
* **Tax Liens** - налоговые льготы
* **Number of Open Accounts** - количество открытых счетов
* **Years of Credit History** - количество лет кредитной истории
* **Maximum Open Credit** - наибольший открытый кредит
* **Number of Credit Problems** - количество проблем с кредитом
* **Months since last delinquent** - количество месяцев с последней просрочки платежа
* **Bankruptcies** - банкротства
* **Purpose** - цель кредита
* **Term** - срок кредита
* **Current Loan Amount** - текущая сумма кредита
* **Current Credit Balance** - текущий кредитный баланс
* **Monthly Debt** - ежемесячный долг
* **Credit Score** - оценка благонадежности клиента (скоринговый балл, полученный из другого источника)
* **Credit Default** - факт невыполнения кредитных обязательств (0 - погашен вовремя, 1 - просрочка)