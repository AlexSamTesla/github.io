---
layout: page
title: 20 сентября 2018
excerpt:
comments: true
---

Мы расскажем, как уместили в одном решении 20 различных приложений, которыми пользуется каждая  2-я российская  компания!  А  также,  как добились высокого  коэффициента «переиспользования» кода... Научим, как расставить приоритеты и выполнить все задачи в срок в условиях многозадачности!

Ведущие JS разработчики компании «Тензор» поделятся уникальным опытом на RTF 18!

[**Регистрируйся**][register] и приходи – мы ждем тебя!
	

Доклады
-------

<ul class="post-list">
{% for post in site.categories.talks %}
  {% if post.author %}
    {% capture authorslist %}
      {% for a in post.author %}
        {% assign author = site.data.authors[a] %}
        {% if author %} {{ author.name }}{% if author.company %}, {{ author.company }}{% endif %}{% endif %}{% unless forloop.last %};{% endunless %}
      {% endfor %}
    {% endcapture %}
  {% endif %}
  {% if post.announce %}
  <li><a href="{{ site.url }}{{ post.url }}"><b>{{ post.title }}</b><br/>{{ authorslist }}</a></li>
  {% endif %}
{% endfor %}
</ul>

Когда
-----

Итак, 20 сентября в 18:30 состоится первая встреча программистов в рамках RTF – 2018. На все доклады  отведено  3  часа. Между  выступлениями  запланирован  кофе-брейк, чтобы  вы  могли перекусить. Для первых 30-ти зарегистрировавшихся after-party за счет компании!

Дата: 20/09/2018, четверг.

Время: с 18.30 до 21.30.

__Вход – free.__


Где
---

Встреча пройдет в ТРЦ «VIKONDA», Вход через отель, 1 этаж. По адресу: г. Рыбинск, Бабушкина 29.

Маршрут от остановки общественного транспорта указан на карте.

Места для парковки автомобилей указаны на карте зеленым цветом.

Контактные телефоны: +7(920) 653-51-73 Полина


<script type="text/javascript" charset="utf-8" async src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3Acd52f8c116e73c39bb701429ca0e459d78ce8793e4e75da7c77b2f9773f0cddc&amp;width=687&amp;height=502&amp;lang=ru_RU&amp;scroll=true"></script>


<!--
<ul class="post-list">
{% for post in site.posts limit:10 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
-->

[register]: /register/
[place]: http://rybinsk.vikonda.ru/
[tensor]: http://tensor.ru/
[speakers]: /speakers/
