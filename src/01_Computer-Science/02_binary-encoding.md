# Двоичное кодирование

Разберемся как кодировать информацию с помощью последовательности
двоичных чисел. Эту последовательность можно представлять как
ряд лампочек ( $0$ - лампочка горит, $1$ - не горит )

С помощью двоичных чисел можно закодировать любое число. Это просто
представление этого числа в двоичной системе счисления:

$ N_{10} = 101\ldots010_2$

А чтобы закодировать, что-то более сложное, например текст, можно
определить кодировку - каждой букве сопоставить число (`ASCII`,`UTF-8`,...)

Для растровых изображений можно использовать матрицу из кортежей RGB - разложение
цвета по трём каналам (красный, зелёный, синий). Каждому каналу ставится в соответствие
число от 0 до 255.

Получается что:

- Всё можно представить числами
- Электричество можно заставить работать с числами

Значит электричество может работать с любыми видами информации.
