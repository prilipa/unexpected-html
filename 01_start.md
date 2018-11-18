# Старт

Плюс HTML'я в том, что Вы можете начать очень быстро. Если Вы работаете на Windows, щелкните правой клавишей на свободном месте, выберете "Создать текстовый файл". Далее щелкните правой клавишей на созданном файле и переименуйте его в index.html .

```!!! Не забудьте включить себе отображение расширений файлов!!!```

Откройте созданный файл в блокноте и скопируйте туда следующие строки

```html
<html>
<head>
</head>
<body>
	Hello World!
</body>
</html>
```

Сохраните и откройте данный файл в браузере. На экране Вы должны увидеть Hello World! Если это так - поздравляю - Вы создали свой первый сайт.

Я рекомендую Вам установить себе текстовый редактор с подсветкой, например [Sublime Text](http://www.sublimetext.com/3). Этому редактору можно посвятить отдельную книгу, но в целом его интерфейс интуитивно понятен. Можете также заглянуть в эту [шпаргалку](https://learn.javascript.ru/sublime).

Теперь вернемся к нашему коду и рассмотрим его подробнее. HTML использует теги - слова заключенные в такие скобки &lt;&gt;. Есть открывающие теги, например &lt;html&gt; и закрывающие &lt;/html&gt; - такие теги называют парными. Есть теги непарные, например тег &lt;img&gt; - у него нет закрывающего

То, что мы показываем пользователю в качестве страницы находится в теге <body>. Давайте добавим туда картинку. Для этого заходим в Гугл, набираем Одесса(или другой город, но зачем он Вам нужен!? :) и сохраняем понравившуюся картинку, под названием odessa.jpg.

Пока что картинка должна быть в той же папке, что и наш файл index.html . Добавлем в код, после тега &lt;body&gt; &lt;img src="odessa.jpg"&gt;


```html
<html>
<head>
</head>
<body>
	Hello World!
	
	<img src="odessa.jpg">
</body>
</html>
```

И получаем следующую картинку

Hello World!
![Фотография Одессы](pics/odessa.jpg)

Теперь давайте добавим в наш код гиперссылку

```html
<html>
<head>
</head>
<body>
	Hello World!
	
	<img src="odessa.jpg">
	
	<a href="http://google.com">Ссылка на Гугл</a>
</body>
</html>
```

Можно ставить ссылку не только на внешний ресурс, но и на другую страницу сайта. Для этого в атрибуте href необходимо указать название файла, на который мы хотим сослаться.

**Практика:**

1. Вам нужно сделать два файла, в первом ссылку на второй, во втором ссылку на первый
2. Сделать три страницы. Вверху каждой страницы добавить навигационное меню с ссылками на каждую из страниц.
3. Сделать файл с галереей из трех картинок. При клике на картинку переходим на страницу, в которой показывается увеличенная копия картинки.