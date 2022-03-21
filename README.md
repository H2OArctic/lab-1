# Лабораторная работа № 1
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1ld7j6JTviIq1-76ua8pv3vf7e5hn5F9C?usp=sharing

### 1. Сколько всего административных округов в Сан-Франциско?

Всего их 10. Это Bayview, Central, Ingleside, Mission, Northern, Park, Richmond, Southern, Taraval и Tenderloin.

### 2. В каких административных округах наибольшая преступность?

Ниже представлены три лидирующих округа с наибольшим количеством преступлений.
1. SOUTHERN: **6185**
2. MISSION: **4011**
3. CENTRAL: **3867**

### 3. Какие виды преступлений совершаются чаще всего?

Ниже представлены три лидирующих типов преступлений.
1. LARCENY/THEFT: **8205**
2. OTHER OFFENSES: **4004**
3. NON-CRIMINAL: **3653**

### 4. Каково назначение функции Лямбда в Python?

Позволяет реализовать анонимную функцию, которая не требует названия и def для объявления.

### 5. Какие виды преступлений регистрируются в Сан-Франциско?

1. LARCENY/THEFT
2. DRUG/NARCOTIC
3. WARRANTS
4. VEHICLE THEFT
5. ROBBERY
6. NON-CRIMINAL
7. TRESPASS
8. VANDALISM
9. ASSAULT
10. FRAUD
11. OTHER OFFENSES
12. FORGERY/COUNTERFEITING
13. DRUNKENNESS
14. ARSON
15. DRIVING UNDER THE INFLUENCE
16. PROSTITUTION
17. KIDNAPPING
18. WEAPON LAWS
19. SUSPICIOUS OCC
20. MISSING PERSON
21. BURGLARY
22. DISORDERLY CONDUCT
23. LIQUOR LAWS
24. FAMILY OFFENSES
25. LOITERING
26. SEX OFFENSES, FORCIBLE
27. SUICIDE
28. EMBEZZLEMENT
29. SEX OFFENSES, NON FORCIBLE
30. STOLEN PROPERTY
31. RUNAWAY
32. GAMBLING
33. EXTORTION
34. PORNOGRAPHY/OBSCENE MAT
35. BRIBERY
36. BAD CHECKS

# Лабораторная работа № 2
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1nmqY-PME7c74otIix9nDrjzbYKB6I-6k?usp=sharing

### 1. Что такое анонимная функция Python, как она работает?

Анонимная функция - это функция, которая не имеет своего названия и при использование не требуется указывать def. Преимущественно такие функции используются при написание лямбда выражений.

### 2. Что возвращает функция speedtest ()? Какой код используется для просмотра результатов функции speedtest ()?

Функция возвращает массив в котором находится тест скорости и временная метка. Для отображения результата функции speedtest, необходимо использовать функцию print.

### 3. Каким образом выполняется переименование столбцов датафрейма?

Переименование происходит через функцию rename, в которую надо передать объект где ключ это текущие название столбца, а ключ это новое название столбца.

### 4. Для чего в лабораторной работе импортируется библиотека NumPy?

Данная библиотека используется для обработки больших многомерных массивов. В данном случае она никак не используется, в связи с чем нет необходимости в импортирование.

### 5. Как выглядит код удаления столбца Datetime?

Для удаления столбца Datetime из DataFrame можно использовать команду del. Ниже представлен пример кода для DataFrame df_compact.

del df_compact['Datetime']

# Лабораторная работа № 3
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1nzGhsP1nTBnlCrvoLDDXsXE4EhvSQbSv?usp=sharing

### 1. Что такое csvsql, как она работает?

Позволяет на основе CSV файла создадавать таблицы и производить вставку данных в базу данных.

### 2. Можно ли объединить таблицы в базе данных, как это сделать?

Объядинить таблицы в БД можно, для этого надо использовать SELECT и JOIN, через общий ключ, который есть в обоих таблицах. 

### 3. Какой метод Pandas позволяет добавлять информацию в базу данных?

Через метод append.

### 4. Что делает метод fetchall()?

Метод извлекает все строки результата запроса.

### 5. Почему для обработки данных используется библиотека Pandas, можно ли выполнить такую же обработку другим способом?

Данная библиотека упрощает работу с DataFrame. Выполнить можно, но это будет более затратно в плане выполнения кода т.к. библиотека Pandas ориентирована на работу с DataFrame.

# Лабораторная работа № 4
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1LWVg1mjG5ic0M-nvTvOmO-nstvSzVgxF?usp=sharing

### 1. Какие статистические значения для даты фрейма позволяет получить метод describe()?

Получить можно следующие значения: count, mean, std, min, 25%, 50%, 75%, max

### 2. Как добавить в дата фрейм новый столбец с данными?

Для добавления нового столбца необходимо указать название столбца и присвоить значение. Например в переменной data хранится фрейм, чтобы добавить в него столбец с названием second, необходимо написать следующую конструкцию data["second"]

### 3. Что такое частотное распределение данных?

Частотное распределение данных это выделение уникальных значений с подсчетом их вхождений с последующей сортировкой от наибольшего к меньшему.

### 4. Что делает функция to_frame(), почему необходимо преобразовать серию данных в дата фрейм?

Преобразует некоторую серию данных в фрейм. Данное преобразование необходимо для последующей обработки данных.

### 5. Как при выводе значения переменной в текстовой строке оставить только 2 цифры после десятичной точки, если исходное значение содержит больше цифр?

Использовать :.2f в конструкции подстановки либо вызвать метод round(2)

# Лабораторная работа № 5
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1id2kZs54T227yiSqt7TYOnQ1qvWA3vWW?usp=sharing

### 1. Обратите внимание на диагональ слева направо в таблице корреляции. Почему диагональ заполнена единицами, это совпадение?

Нет, это не совпадение. Корреляционная матрица обладает свойством, где на главной диагонали находятся коэффициенты корреляции, которые в свою очередь равные единице.

### 2. Можно видеть, также что значения в таблице являются зеркальными, значения ниже единичной диагонали имеют зеркальный аналог выше этой диагонали. Почему?

Это одно из свойств корреляционной матрицы, которое гласит, что матрица симметрична относительно главной диагонали.

### 3. Многие переменные пары представляют корреляцию, близкую к нулю. Что это обозначает?

Это коэффициент корреляции означает слабую взаимосвязь между этой парой.

### 4. Зачем было разделять данные по полу?

Для объективности исследования и выделение некоторых закономерностей, которые могут выражаться у конкретного пола.

### 5. Какие переменные имеют более сильную корреляцию с размером мозга (MRI_Count)? Это ожидаемо?

Рассмотрим следующие варианты: общее, мужчины и женщины.

Общее: Weight и Height

Мужчины: PIQ

Женщины: -

Из проведенной корреляции, можно сделать следующие выводы:
 
**Женщины** - все корреляционные связи являются слабыми.
 
**Мужчины** - есть связь с PIQ и составляет 0.56 и относится к типу средней связности, но по сути можно отнести к слабой т.к. находится недалеко от границы со слабой связью.
 
**Общее** - есть связь с Weight и Height, и соответственно составляет 0.51 и 0.60, но по сути можно отнести к слабой т.к. находится недалеко от границы со слабой связью.

Подводя итог, можно сказать, что сильной связи нет ни в одном из фреймов и данный результат был ожидаем т.к. некоторые данные являются субъективными.
