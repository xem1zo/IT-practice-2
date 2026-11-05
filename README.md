# Практическая работа №2: Логирование в MySQL

## Что сделано:
1. Настроен `my.cnf` с включенным общим логом (`general_log = 1`, `log_output = TABLE`).
2. Создано представление (VIEW) `my_actions` для фильтрации системного лога.
3. Создана база `sql_practice`, таблицы `customers` и `orders`.
4. Создан чистый дамп базы данных (`dump_clean.sql`) и экспорт лога (`my_actions_export.txt`).
