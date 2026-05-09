# iad-lab5
# Лабораторная работа №5 «Анализ последовательностей»

## Данные
Файл: `data/online_retail.xlsx`

## Структура репозитория
- `notebooks/lab5_sequences.ipynb` — основной ноутбук с анализом (реализация AprioriAll, PrefixSpan, поиск контрастных паттернов, построение графов переходов).
- `data/` — папка с исходным датасетом.
> **Примечание:** Самого файла `online_retail.xlsx` в репозитории нет, так как он слишком большой для загрузки на GitHub.

## Запуск

### 1) Клонирование репозитория
git clone https://github.com/chasernoy/iad-lab5.git
cd iad-lab5

### 2) Окружение и зависимости
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install pandas numpy matplotlib networkx prefixspan mlxtend jupyter openpyxl

### 3) Запуск ноутбука
python3 -m jupyter lab
