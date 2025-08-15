# SQL-проєкт: Аналіз доходу по континентах

## Мета
Провести аналіз доходу, активності акаунтів та сесій по континентах, з розподілом по пристроях (mobile/desktop).

## Інструменти
- SQL (BigQuery)
- Looker Studio

## SQL-запит
Запит складається з трьох CTE.
Фінальний SELECT об'єднує всі метрики по континентах.

[Переглянути SQL-запит]([[./query.sql](https://console.cloud.google.com/bigquery?authuser=0&project=data-analytics-mate&supportedpurview=project&ws=!1m5!1m4!1m3!1sdata-analytics-mate!2sbquxjob_7061fee_198ad037179!3sUS&inv=1&invt=Ab5iDA)](https://docs.google.com/document/d/15I7wneG3QKnqxmbGUrDAQm_CHfPYmVfcO2BQqg7UEoM/edit?usp=sharing))

## Результати
- Найбільшу частку доходу приносить регіон Americas — понад половину загального доходу. Це свідчить про високий рівень комерційної активності в цьому регіоні.
- У всіх регіонах desktop приносить більше доходу, ніж mobile. Найбільший розрив — у Europe, де desktop перевищує mobile більш ніж у 2 рази.
- Рівень верифікації акаунтів стабільно високий у всіх регіонах (~71–73%), що свідчить про довіру користувачів до платформи.

## Посилання на дашборд
[Переглянути в Looker Studio](https://lookerstudio.google.com/reporting/dfbfa5bd-ca75-4f16-aed4-3a7c853ac73e)
