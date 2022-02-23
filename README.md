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
10. FRAUDOTHER OFFENSES
11. FORGERY/COUNTERFEITING
12. DRUNKENNESS
13. ARSON
14. DRIVING UNDER THE INFLUENCE
15. PROSTITUTION
16. KIDNAPPING
17. WEAPON LAWS
18. SUSPICIOUS OCC
19. MISSING PERSON
20. BURGLARY
21. DISORDERLY CONDUCT
22. LIQUOR LAWS
23. FAMILY OFFENSES
24. LOITERING
25. SEX OFFENSES, FORCIBLE
26. SUICIDE
27. EMBEZZLEMENT
28. SEX OFFENSES, NON FORCIBLE
29. STOLEN PROPERTY
30. RUNAWAY
31. GAMBLING
32. EXTORTION
33. PORNOGRAPHY/OBSCENE MAT
34. BRIBERY
35. BAD CHECKS

# Лабораторная работа № 2
## Ссылка на код в Google Colab: https://colab.research.google.com/drive/1nmqY-PME7c74otIix9nDrjzbYKB6I-6k?usp=sharing

### 1. Что такое анонимная функция Python, как она работает?

Анонимная функция - это функция, которая не имеет своего названия и при использование не требуется указывать def. Преимущественно такие функции используются при написание лямбда выражений.

### 2. Что возвращает функция speedtest ()? Какой код используется для просмотра результатов функции speedtest ()?

Функция возвращает массив в котором находится тест скорости и временная метка. 

### 3. Каким образом выполняется переименование столбцов датафрейма?

Переименование происходит через функцию rename, в которую надо передать объект где ключ это текущие название столбца, а ключ это новое название столбца.

### 4. Для чего в лабораторной работе импортируется библиотека NumPy?

Данная библиотека используется для обработки больших многомерных массивов. В данном случае она никак не используется, в связи с чем нет необходимости в импортирование.

### 5. Как выглядит код удаления столбца Datetime?

Для удаления столбца Datetime из DataFrame можно использовать команду del. Ниже представлен пример кода для DataFrame df_compact.

del df_compact['Datetime']
