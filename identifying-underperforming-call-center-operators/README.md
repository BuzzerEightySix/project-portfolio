# Описание проекта: Определение неэффективных операторов колл-центров

## Используемые данные

Датасеты содержат информацию об операторах колл-центров и о самих колл-центрах.

Данные об операторах:

- Идентификатор клиентского аккаунта в сервисе
- Дата статистики
- Направление вызовов (out - исходящий вызов, in — входящий вызов)
- Является ли звонок внутренним звонком между операторами колл-центра
- Идентификатор оператора
- Является ли звонок пропущенным
- Количество звонков
- Длительность звонка (без учета времени ожидания)
- Длительность звонка (с учетом времени ожидания)

Данные о колл-центрах:

- Идентификатор клиентского аккаунта в сервисе
- Текущий тарифный план колл-центра
- Дата регистрации колл-центра в сервисе

## Поставленная задача
Подсчет количества и идентификация неэффективных операторов в рамках обоснования необходимости внедрения функционала для мониторинга неэффективных операторов колл-центров с определением колл-центров, которых этот функционал может заинтересовать


## Используемые библиотеки

*pandas*, *numpy*, *matplotlib*
