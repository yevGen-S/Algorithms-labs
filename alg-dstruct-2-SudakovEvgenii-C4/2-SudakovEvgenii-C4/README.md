Graph BFS from edges list

Необходимо создать программу, которая реализует обход графа в ширину. Следует реализовывать
прямой обход (pre-order). Граф задан списком ребер.

Код реализуется только на языке Си, при отправке следует выбрать язык С.
После отправки нажимайте оранжевую кнопку Играть, чтобы узнать результат.

Входные данные подаются в поток стандартного ввода stdin. В первой строке содержится
количество вершин графа. Далее построчно ребра, заданные парой вершин ему инцидентных.
Нумерация вершин начинается с 0.

Не гарантируется, что граф связный.
Обход графа необходимо начинать с вершины с номером 0.

При выборе следующей вершины из смежных с текущей следует выбирать вершину с наименьшим
номером.

На выходе ожидается список вершин в порядке обхода через пробел.
Примеры входных и выходных данных

Пример 1
stdin
5
0 4
1 3
1 4
stdout
0 4 1 3

Пример 2
stdin
10
0 1
0 6
0 8
1 2
1 3
1 6
2 8
2 9
3 7
4 6
4 7
4 8
5 6
7 8
stdout
0 1 6 8 2 3 4 5 7 9