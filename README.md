# DataLoves — Навчання Machine Learning Engineering

Навчальний репозиторій для вивчення Python, Data Science та Machine Learning.

## Мета навчання

- Опанувати Python.
- Вивчити NumPy, Pandas і Matplotlib.
- Зрозуміти алгоритми машинного навчання.
- Навчитися створювати власні ML-проєкти.
- Застосовувати знання для аналізу EEG-сигналів та BCI.

## Виконані домашні завдання

| № | Тема | Рішення | Статус |
|---|---|---|---|
| HW01 | Змінні та типи даних | [Відкрити HW01](python_basics/HW01_variables_data_types.ipynb) | Виконано |
| HW02 | Списки та словники | [Відкрити HW02](python_basics/HW02_lists_dictionaries.ipynb) | Виконано |
| HW03 | Умовні конструкції if / elif / else | [Відкрити HW03](python_basics/HW03_conditionals.ipynb) | Виконано |

Усі рішення представлені у форматі Jupyter Notebook (`.ipynb`).

## Структура репозиторію

- `python_basics/` — домашні завдання з основ Python.
- `environment.yml` — залежності навчального середовища.
- `.gitignore` — правила виключення локальних файлів.
- `README.md` — опис репозиторію та навігація по завданнях.

## Навчальне середовище

Python 3.12, Conda, JupyterLab, NumPy, Pandas, Matplotlib.

Для створення нового середовища:

```powershell
conda env create -f environment.yml
conda activate dataloves
jupyter lab
```

Поточне локальне середовище `dataloves_env` створене окремо за шляхом `C:\Users\user\Learning\dataloves_env`.

## Інженерний напрям

Мета — розвиток компетенцій у Machine Learning, обробці біомедичних сигналів та BCI.

Окремий проєкт: [NeuroTrainer](https://github.com/Oleksandr-Nyemtsev/NeuroTrainer).