# Исследование рынка недвижимости

[Файл ipynb](https://github.com/oleggrigoryev/public_projects/blob/main/computer_vision/notebook_CV_oleggrigoryev_public.ipynb)

## Описание проекта

Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя. Должна быть построена модель, которая по фотографии определит приблизительный возраст человека.




## Стек

- _python_
- _pandas_
- _numpy_
- _tensorflow_
- _keras_
- _matplotlib_ 📊

## Общий вывод

Проанализирован набор фотографий людей с указанием возраста при помощи компьютерного зрения с привлечением готовых нейронных сетей и библиотеки Keras.
На тестовой выборке модель распознаёт фрукты с точностью 99.99%, что очень хорошо. В процессе обучения на разных эпохах точность колебалась от 90.5% (только на 6 эпохе из 7) до 99.9%, что говорит о важность подбора правильных параметров. Для высокой точности было бы достаточно 3 эпох с таким learning_rate (0.0001), так что можно было сэкономить ресурс GPU.