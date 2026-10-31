# Змейка

Игра на Python и Pygame. Управление — стрелками клавиатуры.
Собирайте яблоки; столкновение с собой начинает игру заново.
Через границы поля можно проходить.

## Установка (Windows, Python 3.12)

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## Запуск

Откройте в VS Code папку этого репозитория.
Выберите интерпретатор `.venv\Scripts\python.exe`
через команду `Python: Select Interpreter`.

Запуск из терминала без активации окружения:

```powershell
.\.venv\Scripts\python.exe the_snake.py
```

## Проверки

```powershell
.\.venv\Scripts\python.exe -m pytest
.\.venv\Scripts\python.exe -m flake8 the_snake.py
```

Виртуальное окружение и локальные настройки VS Code не входят в Git.
