# Введение в машинное обучение — МИЭМ НИУ ВШЭ, 2026

Материалы для студентов. Презентации доступны с начала курса; практические ноутбуки и домашние задания публикуются после соответствующего занятия.

- [Рекомендуемые материалы на русском и английском](course/recommended_materials.md)

## Презентации

- Занятие 1. Введение в машинное обучение: [PPTX](lesson_01_introduction_to_machine_learning/lesson_01_introduction_to_ml.pptx) · [PDF](lesson_01_introduction_to_machine_learning/lesson_01_introduction_to_ml.pdf)
- Занятие 2. Разведочный анализ данных: [PPTX](lesson_02_exploratory_data_analysis/lesson_02_exploratory_data_analysis.pptx) · [PDF](lesson_02_exploratory_data_analysis/lesson_02_exploratory_data_analysis.pdf)
- Занятие 3. Признаки и предобработка данных: [PPTX](lesson_03_features_and_preprocessing/lesson_03_features_and_preprocessing.pptx) · [PDF](lesson_03_features_and_preprocessing/lesson_03_features_and_preprocessing.pdf)
- Занятие 4. Контролируемое машинное обучение: [PPTX](lesson_04_supervised_learning/lesson_04_supervised_learning.pptx) · [PDF](lesson_04_supervised_learning/lesson_04_supervised_learning.pdf)
- Занятие 5. Неконтролируемое машинное обучение: [PPTX](lesson_05_unsupervised_learning/lesson_05_unsupervised_learning.pptx) · [PDF](lesson_05_unsupervised_learning/lesson_05_unsupervised_learning.pdf)
- Занятие 6. Временные ряды: [PPTX](lesson_06_time_series/lesson_06_time_series.pptx) · [PDF](lesson_06_time_series/lesson_06_time_series.pdf)
- Занятия 7–8. Нейронные сети: [PPTX](lessons_07_08_neural_networks/lessons_07_08_neural_networks.pptx) · [PDF](lessons_07_08_neural_networks/lessons_07_08_neural_networks.pdf)

## Практические материалы и домашние задания

| Занятие | Тема | Статус |
|---:|---|---|
| 1 | Введение в машинное обучение | опубликовано |
| 2 | Разведочный анализ данных | будет опубликовано после занятия |
| 3 | Признаки и предобработка данных | будет опубликовано после занятия |
| 4 | Контролируемое машинное обучение | будет опубликовано после занятия |
| 5 | Неконтролируемое машинное обучение | будет опубликовано после занятия |
| 6 | Временные ряды | будет опубликовано после занятия |
| 7 | Нейронные сети — часть 1 | будет опубликовано после занятия |
| 8 | Нейронные сети — часть 2 | будет опубликовано после занятия |

## Как пользоваться

Можно скачать отдельный файл через интерфейс GitHub или клонировать репозиторий целиком. Для домашних заданий всегда используйте файлы из последнего опубликованного коммита.

Вопросы по условиям и срокам задавайте преподавателю в учебном канале.

## Окружение

uv:

```bash
uv sync --frozen
uv run jupyter lab
```

Conda:

```bash
conda env create -f environment.yml
conda activate miem-hse-ml-course
jupyter lab
```

Оба варианта используют Python 3.11 и PyTorch. TensorFlow не требуется.
