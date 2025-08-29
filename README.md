# AI-ассистент для подбора недвижимости

Этот проект представляет собой AI-ассистента, который помогает пользователю подбирать подходящие объявления о недвижимости, используя LLM (Large Language Models) и технологии семантического поиска.

## Возможности

- Обработка пользовательского запроса на естественном языке
- Семантический поиск подходящих объектов недвижимости
- Работа с эмбеддингами, таблицами и индексами
- Поддержка внешних источников и инструментов (Chromadb, OpenTelemetry, Arize)

## Используемые технологии

- **[LlamaIndex](https://github.com/jerryjliu/llama_index)** — для индексации и поиска
- **HuggingFace Transformers** — для использования моделей
- **ChromaDB** — как векторная база данных
- **Pandas, Numpy** — для работы с данными
- **Selectolax** — для парсинга HTML
- **OpenTelemetry + Arize** — мониторинг и трекинг

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yourusername/real-estate-ai-assistant.git
   cd real-estate-ai-assistant
   ```

## Структура проекта

- `notebook.ipynb` — основной Jupyter Notebook с кодом
- `README.md` — документация

## Лицензия

MIT License
