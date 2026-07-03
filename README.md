# OpenAPI Generator Templates

Кастомные шаблоны для OpenAPI Generator (Python + asyncio).

## Структура

python/
├── api.mustache # API-классы с @allure.step и декораторами
├── model.mustache # Обёртка файла модели
├── model_anyof.mustache # Шаблон для моделей с anyOf
├── model_doc.mustache # Docstring модели
├── model_enum.mustache # Enum-классы
├── model_generic.mustache # Тело класса модели (Pydantic)
├── model_oneof.mustache # Шаблон для моделей с oneOf
├── partial_api.mustache # Тело API-метода (сериализация параметров)
├── partial_api_args.mustache # Аргументы API-метода
├── partial_header.mustache # Заголовок файла (лицензия, кодировка)
└── asyncio/
└── rest.mustache # REST-клиент с allure-логированием








