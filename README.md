my_game.py - игра, в которой необходимо "придавить" всех хомяков, перемещаясь по клеткам поля 4 на 4. 

1. После запуска игры отображается поле с метками хомяков (1, 2, 3, 4) и меткой игрока (х). 
Пустая клетка поля помечается звездочкой (*), например:
```python3
x**1
****
**4*
23**
```
2. Используя клавиши управления ("s" — вниз, "w" — вверх, "a" — налево, "d" — направо), 
перемещайтесь по клеткам поля и "придавите" всех хомяков.
При нажатии на клавишу управления "e" можно повысить уровень здоровья игрока.
Выход из игры — клавиша управления "q".

3. В процессе игры игрок теряет уровни здоровья. Когда вы "придавите" всех хомяков, игра закончится:
```python3
****
****
****
x***
	WOW!!! You won!!!
```
