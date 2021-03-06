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

# Лабораторная работа № 6
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/15TEaCYQ7fSZQXCkFZBxs_V9idpdnZ928?usp=sharing

### 1. Какие типы были у записей в df_compact до преобразования?

У всех был object, кроме столбца Upload (Mbit/s), у него был тип float64

### 2. В какое время наблюдалась максимальная и минимальная скорость загрузки, выгрузки данных, задержки отправки эхо-запросов командой ping?

В основном с 14-15 наблюдаются минимальные значения, а вот ближе с 17-18 наблюдаются максимальные значения.

### 3. Каким получился результат корреляционного анализа?

Взаимосвязь является слабой т.к. значения между парами меньше 0.5

### 4. Каков точный формат задания подписей к осям графика, наименования графика, добавления легенды для выводимых на график величин?

Необходимо вызвать set_xlabel, set_ylabel и set_title. По названием функций понятно, какая за что отвечает.

### 5. Какие еще библиотеки применяются для визуализации данных Python, назовите и кратко опишите пять таких библиотек.

1. **Seaborn** — это одна из Python-библиотек, которая построена на основе Matplotlib, но более высокоуровневая. В результате, все, что можно построить в Matplotlib, можно построить в Seaborn. К тому же имеет дополнительные инструменты, например, heatmap и violin plots, а также встроенные темы оформления.
2. **Pygal** - это наиболее специфичная Python-библиотека с самыми разнообразными видами графиков, которые дополняют основные Data Science исследования. Pygal возвращает XML, который можно отобразить в браузере или сохранить график в формате SVG. Также возможен экспорт в PNG, однако, здесь потребуется установить дополнительные зависимости. Ниже рисунок с так называемым графиком Radar. Также в Pygal можно работать с простенькими картами.
3. **Altair** — это простая и удобная библиотека Python для статистической визуализации, которая основана на Vega-Lite. Позволяет быстро создавать множество разных статических и интерактивных графиков за несколько строк кода. Altair можно считать промежуточным звеном между Seaborn и Plotly, поскольку она более настраиваемая, чем Seaborn, но не настолько интерактивна как Plotly.
4. **Plotly** — это библиотека для создания интерактивных визуализаций и управления ими. В этой написанной на JavaScript библиотеке есть множество встроенных приложений для машинного обучения (Machine learning) и анализа данных, что упрощает реализацию и визуализацию разных алгоритмов.
5. **Bokeh** — это библиотека на основе Javascript, которая позволяет реализовывать интерактивную визуализацию. Bokeh имеет три уровня управления для разных типов пользователей. Самый высокий уровень позволяет создавать стандартные диаграммы, такие как столбчатые, точечные и т.д. Средний уровень предлагает определенный уровень специфичности, как в Matplotlib, и позволяет контролировать основные строительные блоки каждой диаграммы. Наконец, самый низкий уровень дает вам полный контроль над каждым элементом диаграммы.

# Лабораторная работа № 7
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1TMhlGlfhHaxvHMqW0ZX0qS1j1BVrX-1a?usp=sharing

### 1. Судя по данным коэффициента корреляции, какой тип корреляции наблюдается между годовой выручкой от продаж и количеством магазинов в районе?

Наблюдается обратная корреляция.

### 2. Линейную регрессию в Python можно выполнить другими способами, назовите несколько?

Выполнить можно, для этого можно использовать другие библиотеки, например scikit-learn либо statsmodels, а также реализовать собственную функцию для выполнения данной задачи.

**Scikit-learn** это библиотека, широко используемая в машинном обучении. Она предоставляет значения для данных предварительной обработки, уменьшает размерность, реализует регрессию, классификацию, кластеризацию и т.д.

**Statsmodels** это пакет Python, который позволяет пользователям исследовать данные, оценивать статистические модели.

### 3. Как вы думаете, является ли линейная регрессия методом машинного обучения?

Да т.к. машинное обучение — это подраздел искусственного интеллекта, в котором изучаются алгоритмы, способные обучаться без прямого программирования того, что нужно изучать. На основе данного определения можно сделать вывод, что линейная регрессия является типичным представителем алгоритмов машинного обучения. 

# Лабораторная работа № 8
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1Kr3wa8DR7A9BEBW9Ky6cGLqpDlfRs0kR?usp=sharing
 
### 1. В случаях подобных катастроф команда корабля должна следовать правилу «Женщины и дети в первую очередь» как руководство для того, кому должен быть предоставлен доступ к спасательным шлюпкам. Придерживались ли этого правила в данном случае? Изучите дополнительную информацию и ответьте на вопрос.
 
Рассмотрим полученную статистику.
Всего было 1308 людей.
Погибло: 808 человек
Выжило: 500 человек

Мужской пол выжило: 161 ==> Погибло 681
Женский пол выжило: 339 ==> Погибло 127

Мужской пол возраст меньше 9.5 лет выжило: 25 ==> Погибло 18
Мужской пол возраст больше 9.5 лет выжило: 136 ==> Погибло 663

Основываясь на данной статистике, а также учитывая, что некоторая погрешность и другие факторы, то команда придерживалась данного правила и старались спасти детей и женщин.
 
### 2. Какое значение было использовано для замены отсутствующих возрастов?
 
Для указания возраста в пропущенных значениях использовался средний возврат пассажиров
 
### 3. Из вашего анализа дерева решений, что описывает группу, в которой было больше всего смертей по количеству? В какой группе осталось больше всего выживших?
 
В группе где было больше всего смертей описывает факт, что там был мужской пол, у которых возраст больше 14 лет и они купили билеты 2-3 класса. 
 
Больше всего выживших оказалось в группе с женским полом, которые купили 1-2 класс билеты, хотя если смотреть на параметр Fare, то возможно у большинства из 113 выживщих были билеты на 2 класс.
 
### 4. Какова была точность прогноза при выполнении части 2 работы?
 
Точность составила 0,76
 
### 5. Какова была точность прогноза на обучающей и тестовой выборке данных при выполнении части 3 работы?
 
Точность на обучающей выборке составила 0.82, а на тестовой точность составила 0.81
 
# Лабораторная работа № 9
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1zzBEhh5Lt2LZffYA4qoF2MtabzEniMqe?usp=sharing
 
### 1. Какое значение вы получили для коэффициента детерминации?

Коэффициент детерминации: 0.83

### 2. Какое значение среднеквадратичной ошибки было рассчитано для вашей модели?

Cреднеквадратичная ошибка: 5961.39

### 3. Какое значение средней абсолютной ошибки было получено?

Средняя абсолютная ошибка: 61.22

### 4. Как с помощью NumPy найти ковариацию двух переменных?

Для нахождения необходимо использовать функцию  cov(p1, p2), где p1- это набор значений первой переменной, а p2 является вторым набором значений переменной.
