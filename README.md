# Закончит или нет?

## Условие задачи

Нужно предсказать, сможет ли пользователь успешно закончить онлайн курс "Анализ данных в R.". Считать, что пользователь успешно закончил курс, если он правильно решил больше 40 практических заданий.

В данных:

* submission_data_test.csv
* events_data_test.csv

хранится информация о решениях и действиях для 6184 студентов за первые два дня прохождения курса. Это 6184 студентов, которые проходили курс в период с мая 2018 по январь 2019. 

Используя данные о первых двух днях активности на курсе вам нужно предсказать, наберет ли пользователь более 40 баллов на курсе или нет.

## Структура проекта

### В папке datasets хранятся данные:

* submissions_data_train.csv
* events_data_train.csv

Это исходные данные о прохождении курса пользователями за предыдущие годы, предназначенные для тренировки модели.

* submission_data_test.csv
* event_data_test.csv

Это тестовые данные, на основе которых нужно предсказать, пройдет пользователь курс или нет.

* ML_Contest_train.csv

Это обработанные исходные данные, на которых будет обучаться модель. Получены в процессе работы над проектом.

### В корневом каталоге есть файлы:

* predictions.csv

Результат работы программы, который отправляется на проверку.

* result.png

Скриншот результата.

* Stepik_ML_Contest.ipynb

Jupyter Notebook, в котором хранится программа и подробные объяснения к ней. Самое время его открыть! :)

*P.S. Несмотря на то, что эта задача была дана в рамках обучающего курса, её нужно было решить полностью самостоятельно*
