---
title: "Как создать подключение к {{ prometheus-name }} в {{ datalens-full-name }}"
description: "Следуя данной инструкции, вы сможете создать подключение к {{ prometheus-name }}." 
---

# Создание подключения к {{ prometheus-name }}

Чтобы создать подключение к {{ prometheus-name }}:

1. Перейдите на [страницу подключений]({{ link-datalens-main }}/connections).
1. Нажмите кнопку **Создать подключение**.
1. Выберите источник **{{ prometheus-name }}**.
1. Укажите параметры подключения:

   * **Имя хоста**. Укажите путь до хоста {{ prometheus-name }}. Вы можете указать несколько хостов через запятую. Если к первому хосту подключиться не получится, {{ datalens-short-name }} выберет следующий из списка.
   * **Порт**. Укажите порт подключения к {{ prometheus-name }}.
   * **URL-адрес**. Укажите URL-адрес API {{ prometheus-name }}. 
   * **Имя пользователя**. Укажите имя пользователя для подключения к {{ prometheus-name }}.
   * **Пароль**. Укажите пароль для пользователя.
   * **Время жизни кеша в секундах**. Укажите время жизни кеша или оставьте значение по умолчанию. Рекомендованное значение — 300 секунд (5 минут).
   * **HTTPS**. Активируйте опцию безопасного подключения, если ваш сервер поддерживает протокол HTTPS.

1. Нажмите кнопку **Создать подключение**. Если вы работаете с новой объектной моделью {{ datalens-short-name }}, включающей [воркбуки и коллекции](../../../datalens/workbooks-collections/index.md), выберите или создайте воркбук, в котором сохранится подключение.
1. Введите имя подключения и нажмите кнопку **Создать**.

{% include [datalens-check-host](../../../_includes/datalens/operations/datalens-check-host.md) %}
