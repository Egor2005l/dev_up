# DEV UP API wrapper

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![GitHub](https://img.shields.io/github/license/lordralinc/idm_lp)

## Установка 
```shell
pip install -U https://github.com/lordralinc/dev_up/archive/master.zip
```

## Использование

```python
from dev_up import DevUpAPI

api = DevUpAPI("token")
profile = api.profile.get()
```

## Методы

| Секция  | Метод        | Параметры                    | Описание                                |
|---------|--------------|------------------------------|-----------------------------------------|
| vk      | get_stickers | user_id - VK ID пользователя | Получает список стикеров пользователя   |
| vk      | get_groups   | user_id - VK ID пользователя | Получает список групп пользователя      |
| vk      | get_apps     | user_id - VK ID пользователя | Получает список приложений пользователя |
| profile | get          |                              | Получает информацию о профиле           |
| audio   | speech       | url - ссылка на mp3          | Преобразование аудио в текст            |
