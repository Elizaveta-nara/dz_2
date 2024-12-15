# dz_2
Конфигурационное управление
Задание №2 
Разработать инструмент командной строки для визуализации графа 
зависимостей, включая транзитивные зависимости. Сторонние средства для 
получения зависимостей использовать нельзя. 
Зависимости определяются для git-репозитория. Для описания графа 
зависимостей используется представление Graphviz. Визуализатор должен 
выводить результат на экран в виде кода.

Построить граф зависимостей для коммитов,в узлах которого содержатся номера коммитов в хронологическом порядке.
Граф необходимо строить для ветки с заданным именем.
Ключами командной строки задаются:
• Путь к программе для визуализации графов.
• Путь к анализируемому репозиторию. 
• Путь к файлу-результату в виде кода.
• Имя ветки в репозитории.
Все функции визуализатора зависимостей должны быть покрыты тестами
