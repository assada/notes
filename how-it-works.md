# Як працює цей сайт

Я довго шукав платформу що дозволить швидко і зручно створювати нотатки і публікувати їх у тому вигляді який мені подобається. 

Загалом найбільш схожим проектом є GitHub Pages. Але мені здалось що реалізація кастомних фіч займе забагато часу. Тому я написав супер простий проект на Laravel що просто рекурсивно сканує папку з md файлами. Без бази. З одним лиш контролером. Мені навіть здається що даремно я взагалі взяв Laravel.(я скоріше використав вже існуючий ларавель проект що в мене вже був і просто видалив все зайве). 
Для md парсеру можна писати кастомні теги тощо. Так, авжеж, Jekyl в GitHub Pages це теж дозволяє. Але, у мене на меті створювати тут якісь складніші спецпроекти. 
Саме репозиторій з нотатками "підєднаний" до основнго рушію цього блогу як гіт сабмодуль та налаштований git actions виконує ssh команду для апдейту сабмодуля на сервері. Таким чином будь-які зміни в нотатках автоматично публікуються.


Наразі одна з головних проблем це те що я створюю лише маркдаун файли і вийти за рамки контейнеру(наприклад для SEO мета-тегів) доволі складно. Але можливо. Цього поки немає.
