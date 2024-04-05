#Парсер сообщений в чате

### Как установить
Python3.11 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

После чего создайте файл **.env** вида:
```
TG_BOT_TOKEN='token::1234'
HELPER='@tg_user'
KEY_PHRASES=починка,ремонт,починить,не работает,сломалось
```


### Пример запуска

Ниже представлен пример запуска бота для телеграмма. Бот для ВК запускается аналогично.
```
python ./main.py 

```