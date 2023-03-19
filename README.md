# Project_11

Проектная работа 11
Continuous Integration

1. Создать в Я.Облаке виртуальную машину со следующими характеристиками: 2vCPU, 2GB, RAM, 20GB, HDD.
2. Поднять на этой машине CI-сервер на ваш выбор.
3. Создать репозиторий (github/gitlab/проч. на ваше усмотрение) и создать там файл index.html.
4. Настроить CI:
    4.1. Запускающий контейнер с nginx (версия на ваше усмотрение) с пробросом порта 80 в порт 9889 хостовой системы. При обращении к nginx в контейнере по HTTP, nginx должен выдавать измененный файл index.html.
    4.2. Проверяющий код ответа запущенного контейнера при HTTP-запросе (код должен быть 200).
    4.3. Сравнивающий md5-сумму измененного файла с md5-суммой файла, отдаваемого nginx при HTTP-запросе (суммы должны совпадать).
    4.4. Триггер для старта CI: внесение изменений в созданный вами файл index.html из п.3. В случае выявления ошибки (в двух предыдущих пунктах), должно отправляться    оповещение вам в удобный канал связи — Telegram/Slack/email. Текст оповещения — на ваше усмотрение.
    4.5. После выполнения CI созданный контейнер удаляется.
5. Прислать ментору написанный вами для CI код (или скрин с описанием джоба), а также ссылку на репозиторий и на развернутую CI-систему.

Адрес сервера Jenkins:
http://158.160.14.130:8080/

Скрины выполняемой задачи, настройки pipeline, почты:
- http://joxi.ru/p27NOVgTZEaOxm
- http://joxi.ru/gmvy3KjS0BO5jr
- http://joxi.ru/eAOPlv5TGE3ynr
- http://joxi.ru/bmo3kjBsloZRDm
- http://joxi.ru/D2PP4v6TW1O772
- http://joxi.ru/krDY8w7udLa1Mm
- http://joxi.ru/DmBbnv7H6PbWlm
- http://joxi.ru/52aP8VJT0ZOe1m
- http://joxi.ru/KAg6kjETOew8W2
- http://joxi.ru/EA4y9VaS0Ze7jr
- http://joxi.ru/82QPDvWT43enWm
- http://joxi.ru/Q2KPVvjTgXDKkA
- http://joxi.ru/RmzJe3viVGoojm
- http://joxi.ru/a2XBxv7CpZXq1r
- http://joxi.ru/4AkKvjZFV1OdXA
