Дана информация о данных из Google Analytics (last-click attribution model) по сайту «СберАвтоподписка».

Формат файла — Jupyter Notebook.
Содержание — код для чтения, обработки и EDA; получившиеся графики и текстовые комментарии, а также выводы по данным.

Перед нами стояли следующие задачи: 
- изучение предоставленных данных;
- ответы на вопросы, подразумевающие базовую обработку данных и их
разведочный анализ;
- проверка гипотез;
- ответы на вопросы продуктовой команды.
  
Даны 2 датасета:

1. "ga_sessions" - в нем предоставлена информация о визитах пользователей сайта.
Описание атрибутов:
~ session_id — ID визита;
~ client_id — ID посетителя;
~ visit_date — дата визита;
~ visit_time — время визита;
~ visit_number — порядковый номер визита клиента;
~ utm_source — канал привлечения;
~ utm_medium — тип привлечения;
~ utm_campaign — рекламная кампания;
~ utm_keyword — ключевое слово;
~ device_category — тип устройства;
~ device_os — ОС устройства;
~ device_brand — марка устройства;
~ device_model — модель устройства;
~ device_screen_resolution — разрешение экрана;
~ device_brand — марка устройства;
~ device_model — модель устройства;
~ device_screen_resolution — разрешение экрана;
~ device_browser — браузер;
~ geo_country — страна;
~ geo_city — городv.

2. "ga_hits" - в нем предоставлена информация о событиях одного визита на сайт.
Описание атрибутов:
~ session_id — ID визита;
~ hit_date — дата события;
~ hit_time — время события;
~ hit_number — порядковый номер события в рамках сессии;
~ hit_type — тип события;
~ hit_referer — источник события;
~ hit_page_path — страница события;
~ event_category — тип действия;
~ event_action — действие;
~ event_label — тег действия;
~ event_value — значение результата действияv
