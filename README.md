# userver_tg_types_codegen

Небольшой скрипт реализующий частичную кодогенерацию типов библиотеки для создания Telegram ботов в userver: <https://github.com/haufont/userver/tree/telegram-bot/telegram>

Генерация примера для типов:

```bash
cd types_generator
python main.py -f ./example/api.txt --hpp ./example --cpp ./example
```

Генерация примера для методов:

```bash
cd method_generator
python main.py -f ./example/api.txt --hpp ./example --cpp ./example
```
