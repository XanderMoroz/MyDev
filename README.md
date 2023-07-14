# Игры в командной строке

## Sea Battle 

Sea Battle  представляет собой один из вариантов известной ретро-игры - морской бой. 
Игра выполнена по принципам ООП, на основе классов, моделирующих правила игры. Главным классом является `Game` - игровая сессия. 
Игровая сессия содержит в себе всю логику взаимодейстия второстепенных классов: 

`Board` - класс игрового поля, на котором распологаются корабли. Состоит из клеток

`Ship` - класс корабля. Состоит из клеток. 

`Dot` - класс клетки игровой доски, имеет координаты.

В ходе каждой игровой сессии создаются 2 игровых поля. Далее запускается игровой цикл, состоящий из ходов. 
Каждый свой ход игрок должен выбрать координаты клетки, в которую хочет выстрелить. 
Игра заканчивается когда один из игроков уничтожит все корабли противника.
