jQuery.slide.effect
===================

Что это?
--------

Этот jQuery-плагин позволяет использовать у себя на странице эффект перелистывания.

Пример использования
---------------------------------

- (‘#slider’).slideEffect(‘ajax_respond_url’,N);
Эффект будет применен к элементу с id=”slider”. Первый аргумент – адрес обработчика ajax-запросов, второй – общее количество страниц.

По адресу обработчика плагин посылает запросы вида  ‘ajax_respond_url?p=k’ k – запрашиваемая страница, 0<=k<N
Предполагается, что сервер вернет готовый html для размещения в слайде.

Опция пока всего одна: высота элемента, к которому будет применен эффект:
- $(‘#slider’).slideEffect(‘ajax_respond_url’,5,{height:600});
Высота элемента будет явно установлена в 600px.

Создатель
---------

&copy; 2010 Андрей Мокроусов

About
------

This jQuery-plugins helps you to use slide effect on your page.

Copyright
----------

&copy; 2010 Andrey Mokrousov