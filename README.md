
# 🔥🔥 используй PYTHON 3.10 🔥🔥


# BlumBot Автоматизация для Telegram

BlumBot - это инструмент автоматизации для Telegram, разработанный для помощи в управлении и взаимодействии с BlumCryptoBot. Этот бот может создавать сессии, собирать статистику и автоматизировать задачи для ваших аккаунтов.

### Функции
- Создание сессий Pyrogram
- Сбор и сохранение статистики
- Автоматизация взаимодействия с BlumCryptoBot

### Установка

1. **Установить нужный софт:**
    ```bash
    Скачайте и запустите GIT
    https://github.com/git-for-windows/git/releases/download/v2.45.2.windows.1/Git-2.45.2-64-bit.exe
    установка по умолчанию, всегда далее

    Скачайте и запустите Python 3.10
    https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe

        1 экран.
          -Поставьте галочку - Add python.exe to PATH
          -Выберите Customize Installation(это важно)
    
        2 экран.
          -Отметьте/выберите: pip (остальные, оставьте по умолчанию)
    
        3 экран.
          -Отметьте/выберите: Install Python 3.10 for all users

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
    Дважды щелкните по файлу `run.cmd` если у вас Windows

### Конфигурация

Отредактируйте файл `data/config.py`, добавив ваши `API_ID` и `API_HASH`.
API ID и API Hash создаем тут https://my.telegram.org/auth?to=apps

```python
API_ID = 'your_api_id'
API_HASH = 'your_api_hash'
```

### Использование

#### Для пользователей Windows

1. **Запустите скрипт:**
    ```run.cmd```

2. **Выберите действие:**
    - `1` чтобы запустить бота
    - `2` чтобы создать сессии Telegram




