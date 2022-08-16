# Architecture

### Верхнеуровняя архитектура аналитического решения
* Source Layer
* Storage Layer
* Business Layer

![архитектура решения](https://github.com/facessere/Architecture/blob/main/%D1%81%D0%BB%D0%BE%D0%B8.png)

Сделано в drow.io

---

### Простое решение по обработке данных:
* Сбор информации по веб ресурсам(веб парсинг)
* Структурирование файлов в  (json,xls,txt,scv)
* Загрузка в тестову базу данных
* Обработка данных с Apache Airflow,Spark
* Выгрузка в DWH
* Анализ готовых данных


![архитектура решения](https://github.com/facessere/Architecture/blob/main/%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B5_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0.png)

Сделано в drow.io
