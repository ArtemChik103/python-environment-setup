# Настройка рабочей среды для Python-разработки

Данный репозиторий содержит базовый шаблон и конфигурацию рабочей среды для разработки на Python с использованием WSL (Ubuntu), Visual Studio Code и Git/GitHub.

## 📋 Чек-лист выполненной настройки

- [x] **WSL (Ubuntu)** установлен и настроен
- [x] **Python 3** и **pip3** установлены внутри WSL Ubuntu
- [x] **Visual Studio Code** настроен для работы через WSL (`Remote - WSL`)
- [x] Установлены расширения VS Code:
  - Remote - WSL (`ms-vscode-remote.remote-wsl`)
  - Python (`ms-python.python`)
  - Pylance (`ms-python.vscode-pylance`)
  - GitLens (`eamodio.gitlens`)
- [x] **Git** настроен (`user.name` и `user.email`)
- [x] Создан публичный репозиторий на GitHub
- [x] Репозиторий склонирован в WSL (`~/projects/python-environment-setup`)
- [x] Создана структура папок `/app` и `/examples`
- [x] Добавлены файлы `.gitignore`, `requirements.txt`, `README.md`
- [x] В `app/main.py` реализован вывод `Hello, world!`
- [x] Скрипт проверен и успешно запускается командой `python3 app/main.py`
- [x] Сделан скриншот VS Code с результатом работы программы и сохранен в `examples/`

## 📁 Структура проекта

```text
python-environment-setup/
├── app/
│   └── main.py
├── examples/
│   └── vscode_screenshot.png
├── .gitignore
├── README.md
└── requirements.txt
```

## 🚀 Запуск программы

Для запуска основного скрипта в среде WSL Ubuntu выполните:

```bash
python3 app/main.py
```

Результат выполнения:
```text
Hello, world!
```
