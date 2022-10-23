# Улучшение процесса обогащения золота

[Файл ipynb](https://github.com/oleggrigoryev/public_projects/blob/main/industry_gold_recovery/notebook_prom_oleggrigorev_public.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**mean_absolute_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- **matplotlib**

## 

## Общий вывод

Я провел обучение выбранных моделей для стадий грубой и тонкой очистки, затем сделал проверку выбранных обученных моделей на тестовом наборе и выбрал одну для запуска в производство.
