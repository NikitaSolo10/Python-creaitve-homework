# Pygal

Pygal - билииотека, которая позволяет создавать интерактивные *графики и *диаграммы для различных наборов данных.

** К функциям относятся:
+ Возможность загружать визуализации в форматах SVG
+ Возможность отображать графики
+ Работа с большими и сложными данными

Пример:
![](https://avatars.mds.yandex.net/i?id=4aa2994af5a3dbfb611e6dae5a5be29f-5449844-images-thumbs&n=13)

|Функция|Как сделать|
|-----------|-----------|
|Простой график|import pygal
                  bar_chart = pygal.Bar()
                  bar_chart.add('Fibonacci', [])
                  bar_chart.render_to_file('bar_chart.svg') |
|График с несколькими рядами|bar_chart = pygal.Bar()
                            bar_chart.add('Fibonacci', [])
                            bar_chart.add('Padovan', [])
                            bar_chart.render()|
|График с несколькими сложенными рядами|используйте StackedBar вместо Bar|
|Горизонтальный график|HorizontalStackedBar|
