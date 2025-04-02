# Реализация фундаментальной структуры данных - двоичного дерева поиска.

![двоичное дерево поиска](https://github.com/user-attachments/assets/896d0307-9456-4a2c-8f3c-68e19be2d68f)

## Содержание:

- [Описание проекта:](#описание-проекта)
- [Некоторые особенности:](#некоторые-особенности)
- [Предоставляемый функционал:](#предоставляемый-функционал)
- [Примеры использования:](#примеры-использования)
- [Лицензия:](#лицензия)
- [Автор:](#автор)

## Описание проекта:

Данный проект содержит реализацию двоичного дерева поиска на языке программирования C++. Класс *BinarySearchTree* представляет собой двоичное дерево поиска и включает все основные операции, необходимые для эффективной работы с деревом:

1) `ДОБАВЛЕНИЕ ЭЛЕМЕНТОВ В ДЕРЕВО:` *добавление элементов в дерево ( позиция вставки выбирается автоматически ).*
2) `УДАЛЕНИЕ ЭЛЕМЕНТОВ ИЗ ДЕРЕВА:` *полная очистка дерева.*
3) `ПРОВЕРКА НАЛИЧИЯ ЭЛЕМЕНТА В ДЕРЕВЕ:` *определение, содержится ли некоторый элемент в дереве.*
4) `РЕКОНСТРУКЦИЯ ДЕРЕВА:` *реконструкция дерева в случае его неправильной структуры или сильной несбалансированности.*
5) `ДОСТУП К ЭЛЕМЕНТАМ ДЕРЕВА:` *получение значений минимального и максимального элементов дерева.*
6) `ИНФОРМАЦИЯ О ДЕРЕВЕ:` *получение длины дерева, суммы всех элементов, проверка дерева на пустоту.*
7) `ПРЕОБРАЗОВАНИЕ К ВЕКТОРУ:` *преобразование дерева к std::vector.*

- Кроме того, в проекте реализован итератор, позволяющий работать с данным контейнером через STL, что облегчает жизнь пользователю. Реализованы все необходимые конструкторы, обеспечено грамотное управление всеми ресурсами и строгое соблюдение принципов инкапсуляции. Также перегружены все необходимые операторы для удобства и эффективности использования класса.
