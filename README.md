Бот написан кодерами из NoBanOnly Sq.

Исполнитель: https://t.me/NoBanOnlyZXC

## Настройка бота

В файле config.py нужно поставить токен бота в переменную TOKEN
Получить токен можно у https://t.me/BotFather

В переменную CHANNEL_IDS вставьте ссылки на каналы, пример:

Есть 3 канала, ссылки:

https://t.me/NoBanOnly
https://t.me/DreamTailDev
https://t.me/TelehashDev

Ссылки преобразуются так:

https://t.me/NoBanOnly -> NoBanOnly
https://t.me/DreamTailDev -> DreamTailDev
https://t.me/TelehashDev -> TelehashDev

Дальше ссылки вставляются в переменную в виде списка:

CHANNEL_IDS = ['NoBanOnly','DreamTailDev','TelehashDev']

Также рекомендую настроить welcome_text (отправляется в ответ на /start) и succ_text (отправляется если все условия выполнены) по требованию

### Бот запускается через main.py
