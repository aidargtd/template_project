# template_project
Project Repository Template

### Readme

- **Название и используемые инструменты** в хот-баре
- **Описание проекта**: здесь важно ответить на вопросы: *Что это за проект? Для кого он создан? Зачем он нужен?*
- **Инструкция по установке**: подробно опиши процесс установки проекта. Для разработчиков *(dev, contributor)* желательно предоставить отдельные инструкции, включая особенности установки зависимостей, настройки среды и т.д.
- **Ссылки на документацию, поддержку и контакты для связи**: укажи, где можно найти дополнительную информацию о проекте, как получить поддержку и куда обращаться с вопросами. Это упростит коммуникацию с пользователями и другими разработчиками.

### Также для каждого проекта отдельным md-файлом стоит расписать ML-system-design

```bash
ML_project/
│
├── data/                   # Директория для хранения данных
│   ├── raw/                # Исходные данные, необработанные
│   ├── processed/          # Обработанные данные, готовые для обучения моделей
│   └── external/           # Внешние данные, например, из других источников
│
├── docs/                   # Директория для документации и файлов проектирования
│   ├── systemdesign.md     # Систем дизайн документ
│   └── *docs/              # Папка или файлы с документацией в формате .md
│
├── notebooks/              # Jupyter notebooks для исследований, прототипирования
│
├── src/                    # Исходный код проекта
│   ├── __init__.py         # Инициализация Python пакета
│   ├── data                # Скрипты для обработки данных
│   │   └── make_dataset.py
│   ├── features            # Скрипты для генерации признаков
│   │   └── build_features.py
│   ├── models              # Модели, включая скрипты обучения и оценки
│   │   ├── train_model.py
│   │   └── predict_model.py
│   └── visualization       # Скрипты для визуализации данных и результатов
│       └── visualize.py
|
├── tests/                  # Тесты для проверки кода
│
├── environment.yml         # Конфигурация среды (например, для Conda)
│
├── Dockerfile              # Для создания Docker-контейнера проекта
│
├── .gitignore              # Список игнорируемых git файлов и папок
│
├── requirements.txt        # Список зависимостей Python для pip
│
└── README.md               # Описание проекта, инструкции
```
