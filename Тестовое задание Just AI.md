## Формулировка задания
Проведите ручное тестирование разговорной игры "Виселица".

**Бот доступен в Телеграме: @JustAI_TesterTaskBot**. 

**Дизайн бота проработан на [схеме](https://miro.com/app/board/uXjVKc7Exco=/).**

В боте реализовано 2 игры, в рамках данного задания просим сосредоточиться на тестировании игры «Виселица», тестировать «Угадай столицу» не нужно.

В процессе тестирования учитывайте, что бот должен соответствовать дизайну, а также поддерживать разговор на естественном языке (распознавать различные формулировки текстовых запросов пользователя, а не только реагировать на нажатие кнопок).

Для удобства, в боте реализован автоматический вывод загаданных ответов, этот функционал не влияет на ход тестирования, а создан лишь для его ускорения. На сообщения с выводом правильных ответов заводить баг-репорты *не нужно!*

Для составления тестовой документации мы подготовили шаблон в формате MS Excel. Его использование не обязательно, можете оформить тестовую документацию в удобном для вас формате.

Для перезапуска бота можно пользоваться командой **/start**.

### Технологический стек:

* Графический редактор -  Miro ;
* Табличный редактор - MS Excel.

### Что нужно передать на проверку:

* Чек-лист из шагов (проверок), по которым проводится тестирование;
* Баг-репорты для ошибок. Для каждого баг-репорта необходимо заполнить их обязательные поля: указать лог диалога (цитату с проблемным местом), описание ошибки (в т.ч. ожидаемое поведение), приоритет (Критический / Значительный / Незначительный / Тривиальный);
* Таблица с замечаниями по NLU (понимание естественного языка);
* Дополнительно можно оформить таблицу с идеями для доработок бота.

### Список навыков, которые задание проверяет:

* Работа с документацией (чтение дизайна бота);
* Проведение полного ручного функционального тестирования бота (с учетом всех сценарных ответвлений, интеграций и т.д.);
* Техники проведения тестирования (тест-дизайна);
* Составление тестовой документации;
* Тестирование точности распознавания намерения пользователя.
