# Алгоритмы и структуры данных
В данном репозитории собраны некоторые задачи по алгоритмам.


## Оглавление
- [Ближайший ноль](#Ближайший_ноль)
- [Ловкость рук](#Ловкость_рук)





### Ближайший_ноль [nearest_zero.py](https://github.com/Skrapivn/Algoritms/blob/main/nearest_zero "nearest_zero.py")
Тимофей ищет место, чтобы построить себе дом. Улица, на которой он хочет жить, имеет длину n, то есть состоит из n одинаковых идущих подряд участков. Каждый участок либо пустой, либо на нём уже построен дом.

Общительный Тимофей не хочет жить далеко от других людей на этой улице. Поэтому ему важно для каждого участка знать расстояние до ближайшего пустого участка. Если участок пустой, эта величина будет равна нулю — расстояние до самого себя.
Помогите Тимофею посчитать искомые расстояния. Для этого у вас есть карта улицы. Дома в городе Тимофея нумеровались в том порядке, в котором строились, поэтому их номера на карте никак не упорядочены. Пустые участки обозначены нулями.

Формат ввода
В первой строке дана длина улицы —– n (1 ≤ n ≤ 10^6). В следующей строке записаны n целых неотрицательных чисел — номера домов и обозначения пустых участков на карте (нули). Гарантируется, что в последовательности есть хотя бы один ноль. Номера домов (положительные числа) уникальны и не превосходят 10^9.

Формат вывода
Для каждого из участков выведите расстояние до ближайшего нуля. Числа выводите в одну строку, разделяя их пробелами.

###### Пример 1
Ввод: ``5`` ``0 1 4 9 0``

Вывод:
``0 1 2 1 0``

###### Пример 2
Ввод: ``6`` ``0 7 9 4 8 20``

Вывод:
``0 1 2 3 4 5``

[⬆️Оглавление](#оглавление)

### Ловкость_рук [hand_agility.py](https://github.com/Skrapivn/Algoritms/blob/main/hand_agility "hand_agility.py")
Игра «Тренажёр для скоростной печати» представляет собой поле из клавиш 4x4. В нём на каждом раунде появляется конфигурация цифр и точек. На клавише написана либо точка, либо цифра от 1 до 9.

В момент времени t игрок должен одновременно нажать на все клавиши, на которых написана цифра t. Гоша и Тимофей могут нажать в один момент времени на k клавиш каждый. Если в момент времени t нажаты все нужные клавиши, то игроки получают 1 балл.
Найдите число баллов, которое смогут заработать Гоша и Тимофей, если будут нажимать на клавиши вдвоём.
![image](https://user-images.githubusercontent.com/33264331/184338358-a30c92d1-2736-41fc-b177-52fda8c94b8d.png)

Формат ввода
В первой строке дано целое число k (1 ≤ k ≤ 5).
В четырёх следующих строках задан вид тренажёра –— по 4 символа в каждой строке. Каждый символ —– либо точка, либо цифра от 1 до 9. Символы одной строки идут подряд и не разделены пробелами.

Формат вывода
Выведите единственное число –— максимальное количество баллов, которое смогут набрать Гоша и Тимофей.
``

###### Пример 1
Ввод: ``3`` ``1231`` ``2..2`` ``2..2`` ``2..2``

Вывод:
``2``
###### Пример 2
Ввод: ``4`` ``1111`` ``9999`` ``1111`` ``9911``

Вывод:
``1``

###### Пример 3
Ввод: ``4`` ``1111`` ``1111`` ``1111`` ``1111``

Вывод:
``0``

[⬆️Оглавление](#оглавление)

Автор: [Sergey K.](https://github.com/Skrapivn "Sergey K.")
