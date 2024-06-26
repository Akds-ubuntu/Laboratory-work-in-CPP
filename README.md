# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&random=false&width=650&lines=Laboratory+work+about+polygons+intersection+area)](https://git.io/typing-svg)
#### В нашей программе для определения точек получившегося полигона при наложении фигур мы использовали алгоритм Сазерленда-Ходжмана.
#### Суть алгоритма, для простоты, рассмотрим на 2 фигурах:
![image](https://github.com/Akds-ubuntu/Laboratory-work-in-CPP/assets/125271579/e68139dc-c492-488c-abb0-4020423854cd)
#### Изначально точки должны быть расположены по часовой стрелке у всех фигур. Теперь выбираем первые две вершины у красной фигуры и у синей
#### K1, K2 – для красной
#### C1, C2 – для синей
![image](https://github.com/Akds-ubuntu/Laboratory-work-in-CPP/assets/125271579/4a3ab186-ce21-475a-aa5f-efdfd23b7316)
#### Мы проверяем, где лежат точки C1 и C2 относительно отрезка K1K2. Если обе точки лежат слева от K1K2, то мы их отбрасываем. Если обе точки лежат справа от K1K2, то мы    сохраняем последнюю. А если последняя точка взятого нами отрезка лежит справа от K1K2, а первая точка отрезка синей фигуры лежит слева, то мы вычисляем точку пересечения взятых отрезков сохраняем её и также последнюю точку отрезка синей фигуры. Чтобы проверить, что вершины синей фигуры внутри треугольника, вычисляем P:   P = (C2x – K1x) * (K2y – K1y) - (C2y – K1y) * (K2x – K1x) Если P < 0, то C2 справа от K1K2, если P > 0, то наоборот. И производим такие действия до тех пор, пока не пройдем по всем отрезкам синей фигуры. Затем мы меняем отрезок у красной фигуры и выполняем те же самые действия, описанные выше, еще раз, но уже с точками, которые получились после первой итерации.
# Команда
## ![Service Name](https://img.shields.io/badge/-Данил_Паршин-red?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Михаил_Паршин-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Кирилл_Спаращуков-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Андрей_Знаков-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Алексей_Разживин-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Илья_Тимофеев-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Алексей_Фадеев-green?style=for-the-badge&logo=<LOGO_NAME>)
## ![Service Name](https://img.shields.io/badge/-Максим_Курашин-green?style=for-the-badge&logo=<LOGO_NAME>)
