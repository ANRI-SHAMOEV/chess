# chess
Задание 1 Задачи для Практикума по программированию. Общая тема задания «Шахматный симулятор: объектно-ориентированная версия».

Создать объектно-ориентированную реализацию программы для игры в шахматы.

Реализовать программу, которая позволяет играть в шахматы на компьютере. Взаимодействие с программой производится через консоль (базовый вариант). Игровое поле изображается в виде 8 текстовых строк, плюс строки с буквенным обозначением столбцов (см. пример на Рис. 1) и перерисовывается при каждом изменении состояния поля. При запросе данных от пользователя программа сообщает, что ожидает от пользователя (например, позицию фигуры для следующего хода белыми; целевую позицию выбранной фигуры) и проверяет корректность ввода (допускаются только ходы соответствующие правилам шахмат; поддержка рокировки, сложных правил для пешек и проверки мата вынесена в отдельные пункты). Программа должна считать количество сделанных ходов.

Сама программа НЕ ходит: т.е. не пытается выполнить ходы за одну из сторон, а предоставляет поочередно вводить ходы за белых и черных.

Требования к реализации: Основные объекты и абстрактные сущности игры должны быть представлены в виде объектов, представителей соответствующих классов, часть классов должны быть организованы в виде иерархии. В частности: шахматные фигуры – объекты, представители классов, организованных в виде иерархии; доска – объект; ходы фигур – объекты. Вся основная информация должна храниться в атрибутах объектов или классов (например, информация о положении фигур, цвете фигур, символах, используемых для визуализации фигур и т.п.). Основная часть функционала должна программы должна быть организована в виде методов, закрепленных за соответствующими объектами или классами. Например, это касается методов определяющих допустимые ходы фигур. Организация иерархий классов, атрибутов и методов должна позволять гибко расширять возможности программы с минимальными изменениям в уже созданном коде.

Дополнительные задания:

На базе игры в шахматы реализовать игру в шашки. Разработать модификацию шахмат с минимальным вмешательством в существующий код. Сложность 2

Реализовать поддержку для пешки сложных правил: «взятие на проходе» и замены на другую фигуру при достижении крайней горизонтали (в базовой версии их поддержка не обязательна, но возможность первого хода на одну или две горизонтали - обязательно). Подробнее о правилах см.: https://ru.wikipedia.org/wiki/Правила_шахмат . Информация о допустимых ходах должна храниться в объектно-ориентированном виде, алгоритм без модификации должен работать при добавлении новых типов фигур со сложным поведением (задание берется совместно с Заданием 1 и как минимум одна из новых фигур должна иметь сложное поведение, т.е. изменение правил хода и взятия фигуры в зависимости от дополнительных условий). Сложность 1

Добавил возможность рокировки. Сложность 1

Добавил дамку для шашек и замену пешки на другую фигуру при достижении крайней горизонтали.
