# Python Course(3.6)

<b>Об этом курсе</b>: Python – простой, гибкий и невероятно популярный язык, который используется практически во всех областях современной разработки. С его помощью можно создавать веб-приложения, писать игры, заниматься анализом данных, автоматизировать задачи системного администрирования и многое другое. “Программирование на Python” читают разработчики, применяющие Python в проектах, которыми ежедневно пользуются миллионы людей. Курс покрывает все необходимые для ежедневной работы программиста темы, а также рассказывает про многие особенности языка, которые часто опускают при его изучении.

Канал обсуждения в телеге: https://t.me/joinchat/DIzo-A8Tw8u-nXtpSs8y4Q

<b>Курс рассчитан на </b> как на людей, которые уже имели опыт программирования на python, так и новичков в этом деле. Однако, в рамках курса предусмотрены только лекции и домашние задания. Основная среда работы: ipython notebook. В ходе курса не объясняется, как и что устанавливать. Предполагается, что слушатели разбираются с этим сами.

<b>Курс читается</b> на кафедре 1С, МФТИ.

<b>Как слать домашки?</b>: Писать на почту login-const@mail.ru, в теме письма указать Python1C_HWX. в письме указать свою фамилию. формат сдачи - jupyter notebook или .py файл. Пожалуйста, называйте файлы ФИО_HWX.py или если файлов много - назовите аналогично архив.

<b>Любой Deadline dd.mm.yy = dd.mm.yy 00:00</b>

<b>Оценка по курсу</b> выставляется по следующей формуле: <i>sum(балл(дз_i), i=1...10) + доп_баллы.</i> оценка переводится в строковый маркер как обычно :).

## Программа курса

### Часть 1. Синтаксис.

<ul>
	<li><a href="https://github.com/king-menin/python-course/blob/master/L1.intro-python/L1.intro-python.pdf">Лекция 1. Python Введение. Основные структуры языка.</a><br><i>Описание</i>: на первой лекции разбираются основные конструкции языка, последовательности выполнения операций, циклы, переменные, объекты и их свойства (Identity, Type, Value). Garbage Collector. Изменяемые и неизменяемые объекты. Стандартные контейнеры. Функции. Библиотека collections.<br>Задание: условие в конце лекции 1.<b>Deadline: 27.02.2020</b></li>
	<li><a href="https://github.com/king-menin/python-course/blob/master/L2.strings/intro-python-2.pdf">Лекция 2. Python. Введение. Строки, кодировки, файлы.</a><br><i>Описание</i>: на второй лекции разбиаются кодировки, строки в python (стандартные функции str). Как работает интерпретатор со строками. Частично затрагиваются менеджеры контекста. Разбираются потоки ввода, вывода и ошибок. <br>
	<a href="https://github.com/king-menin/python-course/blob/master/L2.strings/samples.ipynb">Примеры с лекции</a>
	<br><i>Задание</i>: Знакомство со строками. Реализация алогритма передачи данных: <a href="https://github.com/king-menin/python-course/blob/master/HWS/HW2.ipynb">часть 1</a>, <b>Deadline: 05.03.2020</b>.
	</li>
	<li><a href="https://github.com/king-menin/python-course/blob/master/L3.OOP/oop1.pdf">Лекция 3. Python. ООП.</a><br><i>Описание</i>: третья лекция включает разбор основных принципов ООП в питон. Классы и экземпляры. Наследование в питон и алгоритм MRO. Магические методы в питон. Объясняется как осуществляется доступ к атрибутам класса.<br>
	<a href="https://github.com/king-menin/python-course/blob/master/L3.OOP/samples.ipynb">Примеры с лекции</a>
<br><i>Задание</i>: Знакомство с магическими функциями в питон. Реализация классов CounterGetter, Vector: <a href="https://github.com/king-menin/python-course/blob/master/HWS/HW2.ipynb">часть 2</a>, <b>Deadline: 05.03.2020</b>.
	<li><a href="https://github.com/king-menin/python-course/blob/master/L4.scopes_closures_decorators/scopes_closures_decorators.pdf">Лекция 4. Области видимости. Замыкания. Декораторы.</a><br><i>Описание</i>: на лекции разбираются анонимные функции, области видимости переменных и контексты. Объяснение правила LEBG. Приводятся и объясняются сложные примеры замыканий с атрибутами и методами. Разбирается работа декораторов в питон. Стандартная библиотека functions. Классы декораторы и функции декораторы.<br>
	<a href="https://github.com/king-menin/python-course/blob/master/L4.scopes_closures_decorators/samples.ipynb">Примеры с лекции</a>
<br><i><a href="https://github.com/king-menin/python-course/blob/master/HWS/HW3.ipynb">Задание</a></i>: написать следующие декораторы - кэширования результатов функции (@cached), проверки типов аргументов функции (@checked) и декоратор логирования выполнения функции (@Logger). <b>Deadline: 12.03.2020</b>.
</ul>

## Authors

* **Антон Емельянов** - *МФТИ, кафедра АТП* - *login-const@mail.ru*

## Литература и полезные ссылки
* [Дебаг в ноутбуке](https://davidhamann.de/2017/04/22/debugging-jupyter-notebooks/)
* [python docs](https://docs.python.org/3/)
* [.format](https://pyformat.info/)
* [импорт в питоне](http://asvetlov.blogspot.ru/2010/05/blog-post.html), [импорт в питоне ч.2](http://asvetlov.blogspot.ru/2010/05/blog-post.html)
* [регулярные выражения](https://developers.google.com/edu/python/regular-expressions), [модуль re](https://docs.python.org/3/library/re.html)
* [unit tests](http://asvetlov.blogspot.ru/2011/02/funny-unittests.html)
* [метаклассы](http://python-3-patterns-idioms-test.readthedocs.io/en/latest/Metaprogramming.html)
* [mro (advanced)](https://www.python.org/download/releases/2.3/mro/)
* [itertools](https://docs.python.org/2/library/itertools.html)
* [GIL](http://asvetlov.blogspot.ru/2011/07/gil.html)
### книги:
* [(begginer level): dive into python](http://www.diveintopython3.net/)
* [(begginer level): a byte of python](https://python.swaroopch.com/)
### ссылка на ссылки :)
* [много различной литературы, ссылок на онлайн курсы и задачки](https://ru.stackoverflow.com/questions/420125/%D0%9A%D0%BD%D0%B8%D0%B3%D0%B8-%D0%B8-%D1%83%D1%87%D0%B5%D0%B1%D0%BD%D1%8B%D0%B5-%D1%80%D0%B5%D1%81%D1%83%D1%80%D1%81%D1%8B-%D0%BF%D0%BE-python?rq=1)
