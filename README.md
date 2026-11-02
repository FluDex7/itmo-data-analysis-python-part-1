# Анализ данных на Python

Лабораторные работы по курсу «Анализ данных на Python», ИТМО.

**Студент:** Романов Данил Павлович, группа М4181

**Контакты:**
- Telegram: [@romanofflife](https://t.me/romanofflife)
- Email: [9e7erteagle@gmail.com](mailto:9e7erteagle@gmail.com)

## Лабораторные работы

| № | Тема | Данные | Блокнот |
|---|------|--------|---------|
| 1 | [Иерархический кластерный анализ](HW1/) | Economics of Cities | [lab1.ipynb](HW1/lab1.ipynb) |

## Структура репозитория

```
.
├── HW1/                # Лабораторная 1: блокнот, данные, описание
├── requirements.txt    # Зависимости для всех работ
└── README.md
```

Каждая работа лежит в отдельной папке `HWn/` со своим `README.md`: постановка задачи, ход работы и результаты.

## Запуск

Нужен Python 3.12.

```bash
git clone <url репозитория>
cd AD

python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt

jupyter lab
```

Затем открыть блокнот нужной работы, например `HW1/lab1.ipynb`, и выполнить **Run → Run All Cells**. Пути к данным в блокнотах указаны относительно папки работы, поэтому запускать блокнот нужно из неё (Jupyter и VS Code делают это по умолчанию).

Код оформлен в соответствии с [PEP 8](https://peps.python.org/pep-0008/).
