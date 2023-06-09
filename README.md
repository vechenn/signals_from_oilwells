# signals_from_oilwells
## Analyse of signals from wells. Clustering and semi-supervised learning.

Дано множество из 760 дискретных вещественнозначных сигналов, состоящих из 5000 отсчетов. Множество сигналов делится на 9 кластеров по некоторым признакам и на каждом сигнале имеется 4 характерные точки, которые определяются по некоторым правилам внутри каждого кластера.

Для 15% сигналов заданы:
Принадлежность к 1 из 9 кластеров.
Определены 4 характерные точки в каждом кластере.

Необходимо составить алгоритм и реализовать его в виде программ, который позволит для оставшихся 85 % сигналов:
Определить для каждого сигнала принадлежность к 1 из 9 кластеров (задача 1).
Определить для каждого сигнала все 4 характерные точки (задача 2).

Примечание: в исходных данных дополнительно включены координаты (X, Y), которые позволяют оценить границы полученных кластеров и исключить отсутствие отдельных удаленных сигналов.

<img width="841" alt="condition" src="https://user-images.githubusercontent.com/101724749/235716658-ede19e61-40b1-433d-9428-a6c7a1833feb.png">
