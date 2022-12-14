# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток.

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений.

**Что практикуем**     
Учимся писать хороший код на Python.


### Краткая информация о данных
Файл game.py содержит в себе собственно код моего решения и код
самой игры (тестирования эффективности решения на выборке из
тысячи(1000) случайных загаданных компьютером чисел).
Файл ноутбука game.ipynb содержит в себе демонстрацию
тестирования эффективности моего решения.
Код в файле game.py использует фиксированный сид и поэтому должен
быть воспроизводим при условии наличия в среде исполнения
библиотеки numpy.
Проект был выполнен в среде Python 3.9.11 64-bit.
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
По результатам испытания, представленный мною алгоритм угадывает
загаданное число в среднеи за пять(5) попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Двоичный поиск - возможно, самый примитивный и очевидный метод для решения 
подобных задач, поэтому на оригинальность решения не претендую вовсе.
Но, хотя бы у меня хватило самодисциплины закончить этот проект.

:arrow_up:[к оглавлению](.README.md#Оглавление)


Пожалуйста, не бейте по голове за то, что такая легкотня заняла у меня 
столько времени.