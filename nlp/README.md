# Анализ текстов

[Файл ipynb](https://github.com/oleggrigoryev/public_projects/blob/main/nlp/notebook_MLTexts_oleg_grigoryev_public.ipynb)

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**



## Вывод

Я провёл исследовательскую работу по обработке текстов и обучению, выбрал модель для определения токсичных комментариев по методу TF-IDF — это оказалась **линейная регрессия**. Наметил шаги по дальнейшей настройке модели.

## Дальнейшие шаги

1. Нужно настроить модель точнее.
2. Обучить модель для работы с русскоязычными комментариями.
