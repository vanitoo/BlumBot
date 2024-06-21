
# 🔥🔥 используй PYTHON 3.10 🔥🔥


# BlumBot Автоматизация для Telegram

BlumBot - это инструмент автоматизации для Telegram, разработанный для помощи в управлении и взаимодействии с BlumCryptoBot. Этот бот может создавать сессии, собирать статистику и автоматизировать задачи для ваших аккаунтов.

### Функции
- Создание сессий Pyrogram
- Сбор и сохранение статистики
- Автоматизация взаимодействия с BlumCryptoBot

### Установка

1. **Установить Python:**
    ```bash
    Скачайте и запустите Python 3.10
    https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe

    Поставьте галочку - Add Python 3.10 to PATH.

    Выберите Customize Installation(это важно)
    Отметьте/выберите: pip (остальные, оставьте по умолчанию)

    Отметьте/выберите: Install for all users

    Укажите путь C:\Python310

    ```


2. **Клонируйте репозиторий:**

   запускаем cmd
    ```bash
    mkdir c:\bot
    cd c:\bot
    
    git clone https://github.com/vanitoo/blumbot.git
    cd blumbot

    
    ```

4. **Запустите скрипт:**
    Дважды щелкните по файлу `run.bat` если у вас Windows

### Конфигурация

Отредактируйте файл `data/config.py`, добавив ваши `API_ID` и `API_HASH`.

```python
API_ID = 'your_api_id'
API_HASH = 'your_api_hash'
```

### Использование

#### Для пользователей Windows

1. **Запустите скрипт:**
    ```run.bat```

2. **Выберите действие:**
    - `1` чтобы создать сессии Pyrogram
    - `2` чтобы запустить бота



