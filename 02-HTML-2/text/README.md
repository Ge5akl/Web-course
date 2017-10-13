[Назад к описанию занятия](https://github.com/Vladislav-Lyuminarskiy/Web-course/tree/master/02-HTML-2)

[Посмотреть пример на JSFiddle](https://jsfiddle.net/Vladislav_Lyuminarskiy/4sgeu37s/)

# Текст и форматирование

Элементы в этом примере:

Элемент                                        | Описание
-----------------------------------------------|-----------------------------------------------
[`<abbr>`](http://htmlbook.ru/html/abbr)       | Тег `<abbr>` указывает, что последовательность символов является аббревиатурой. С помощью атрибута `title` дается расшифровка сокращения, что позволяет понимать аббревиатуру тем людям, которые с ней не знакомы. Кроме того, поисковые системы индексируют полнотекстовый вариант сокращения, что может использоваться для повышения рейтинга документа.
[`<address>`](http://htmlbook.ru/html/address) | Тег `<address>` предназначен для хранения информации об авторе и может включать в себя любые элементы HTML вроде ссылок, текста, выделений и т.д. Планируется, что поисковые системы будут анализировать содержимое этого тега для сбора информации об авторах сайтов.<br>По умолчанию текст внутри контейнера `<address>` отображается курсивным начертанием. Если эта особенность не требуется, используйте стили для изменения начертания шрифта.
[`<b>`](http://htmlbook.ru/html/b)             | Устанавливает жирное начертание шрифта. Допустимо использовать этот тег совместно с другими тегами, которые определяют начертание текста.
[`<bdo>`](http://htmlbook.ru/html/bdo)         | Тег `<bdo>` устанавливает направление вывода текста и преимущественно предназначен для использования с языками, где чтение происходит справа налево. Например, к ним относится арабский язык.
[`<br>`](http://htmlbook.ru/html/br)           | Тег `<br>` устанавливает перевод строки в том месте, где этот тег находится. В отличие от тега абзаца `<p>`, использование тега `<br>` не добавляет пустой отступ перед строкой. Если текст, в котором используется перевод строки, обтекает плавающий элемент, то с помощью атрибута `clear` тега `<br>` можно сделать так, чтобы следующая строка начиналась ниже элемента.
[`<cite>`](http://htmlbook.ru/html/cite)       | Тег `<cite>` помечает текст как цитату или сноску на другой материал. Такое выделение удобно для изменения стиля текста через CSS, а также применяется для разделения кода HTML на структурные элементы. Браузеры обычно устанавливают текст внутри контейнера `<cite>` курсивом.
[`<code>`](http://htmlbook.ru/html/code)       | Тег `<code>` предназначен для отображения одной или нескольких строк текста, который представляет собой программный код. Сюда относятся имена переменных, ключевые слова, тексты функции и т.д. Браузеры обычно отображают содержимое контейнера `<code>` как моноширинный текст уменьшенного размера.<br>В отличие от тега `<pre>`, дополнительные пробелы внутри контейнера `<code>` не учитываются, так же как и переносы текста. Поэтому используйте тег `<br>` или `<p>` для создания переносов.
[`<del>`](http://htmlbook.ru/html/del)         | Тег `<del>` используется для выделения текста, который был удален в новой версии документа. Подобное форматирование позволяет отследить, какие изменения в тексте документа были сделаны.<br>Браузеры обычно помечают текст в контейнере `<del>` как перечеркнутый.
[`<dfn>`](http://htmlbook.ru/html/dfn)         | Как правило, в документе, когда упоминается новый термин, он выделяется курсивом и дается его определение. При использовании этого термина в дальнейшем, он считается уже известным читателю. Тег `<dfn>` применяется для выделения таких терминов при их первом появлении в тексте.<br>Браузеры отображают содержимое контейнера `<dfn>` с помощью курсивного начертания.
[`<em>`](http://htmlbook.ru/html/em)           | Тег `<em>` предназначен для акцентирования текста. Браузеры отображают такой текст курсивным начертанием.
[`<h1>`](http://htmlbook.ru/html/h1)...`<h6>`  | HTML предлагает шесть заголовков разного уровня, которые показывают относительную важность секции, расположенной после заголовка. Так, тег `<h1>` представляет собой наиболее важный заголовок первого уровня, а тег `<h6>` служит для обозначения заголовка шестого уровня и является наименее значительным. По умолчанию, заголовок первого уровня отображается самым крупным шрифтом жирного начертания, заголовки последующего уровня по размеру меньше. Теги `<h1>`...`<h6>` относятся к блочным элементам, они всегда начинаются с новой строки, а после них другие элементы отображаются на следующей строке. Кроме того, перед заголовком и после него добавляется пустое пространство.
[`<hr>`](http://htmlbook.ru/html/hr)           | Рисует горизонтальную линию, которая по своему виду зависит от используемых параметров, а также браузера. Тег `<hr>` относится к блочным элементам, линия всегда начинается с новой строки, а после нее все элементы отображаются на следующей строке.
[`<i>`](http://htmlbook.ru/html/i)             | Устанавливает курсивное начертание шрифта. Допустимо использовать этот тег совместно с другими тегами, которые определяют начертание текста.
[`<ins>`](http://htmlbook.ru/html/ins)         | Тег `<ins>` предназначен для выделения текста, который был добавлен в новую версию документа. Подобное форматирование позволяет отследить, какие изменения в тексте документа были сделаны.<br>Браузеры обычно помечают текст в контейнере `<ins>` как подчеркнутый.
[`<mark>`](http://htmlbook.ru/html/mark)       | Тег `<mark>` помечает текст как выделенный. Такой текст ничем не отличается от обычного, но его вид может быть изменен с помощью стилей. В некоторых браузерах фоновый цвет текста внутри `<mark>` выделяется желтым цветом.
[`<p>`](http://htmlbook.ru/html/p)             | Определяет текстовый абзац. Тег `<p>` является блочным элементом, всегда начинается с новой строки, абзацы текста идущие друг за другом разделяются между собой отбивкой. Величиной отбивки можно управлять с помощью стилей. Если закрывающего тега нет, считается, что конец абзаца совпадает с началом следующего блочного элемента.
[`<pre>`](http://htmlbook.ru/html/pre)         | Элемент `<pre>` определяет блок предварительно форматированного текста. Такой текст отображается обычно моноширинным шрифтом и со всеми пробелами между словами. По умолчанию, любое количество пробелов идущих в коде подряд, на веб-странице показывается как один. Тег `<pre>` позволяет обойти эту особенность и отображать текст как требуется разработчику. Внутри контейнера `<pre>` допустимо применять любые теги кроме следующих: `<img>`, `<small>`, `<sub>` и `<sup>`.
[`<q>`](http://htmlbook.ru/html/q)             | Тег `<q>` используется для выделения в тексте цитат. Содержимое контейнера автоматически отображается в браузере в кавычках.
[`<small>`](http://htmlbook.ru/html/small)     | Тег `<small>` уменьшает размер шрифта на единицу по сравнению с обычным текстом. В HTML размер шрифта измеряется в условных единицах от 1 до 7, средний размер текста, используемый по умолчанию, принят 3. Таким образом, добавление тега `<small>` уменьшает текст на одну условную единицу. Допускается применение вложенных тегов `<small>`, при этом размер шрифта будет меньше с каждым вложенным уровнем, но не может быть меньше, чем 1.
[`<span>`](http://htmlbook.ru/html/span)       | Тег `<span>` предназначен для определения строчных элементов документа. В отличие от блочных элементов, таких как `<table>`, `<p>` или `<div>`, с помощью тега `<span>` можно выделить часть информации внутри других тегов и установить для нее свой стиль. Например, внутри абзаца (тега `<p>`) можно изменить цвет и размер первой буквы, если добавить начальный и конечный тег `<span>` и определить для него стиль текста. Чтобы не описывать каждый раз стиль внутри тега, можно выделить стиль во внешнюю таблицу стилей, а для тега добавить атрибут `class` или `id` с именем селектора.
[`<strong>`](http://htmlbook.ru/html/strong)   | Тег `<strong>` предназначен для акцентирования текста. Браузеры отображают такой текст жирным начертанием.
[`<sub>`](http://htmlbook.ru/html/sub)         | Отображает шрифт в виде нижнего индекса. Текст при этом располагается ниже базовой линии остальных символов строки и уменьшенного размера.
[`<sup>`](http://htmlbook.ru/html/sup)         | Отображает шрифт в виде верхнего индекса. Шрифт при этом отображается выше базовой линии текста и уменьшенного размера.
[`<time>`](http://htmlbook.ru/html/time)       | Помечает текст внутри тега `<time>` как дата, время или оба значения. Может указываться непосредственно внутри контейнера `<time>`, либо задаваться через атрибут datetime.
[`<wbr>`](http://htmlbook.ru/html/wbr)         | Тег `<wbr>` указывает браузеру место, где допускается делать перенос строки в тексте, если этого требует ширина родительского элемента.