# kpi-dashboard-eda

Анализ KPI сотрудников по отделам и неделям: сравнение отделов, динамика, выбросы, взаимосвязи показателей.  
Результат: EDA в Jupyter + Power BI дашборд (PDF).

## Project structure
- `notebooks/01_eda.ipynb` — EDA (подготовка, агрегации, boxplot, корреляции, анализ динамики)
- `reports/dashboard.pdf` — Power BI dashboard (экспорт)
- `reports/figures/` — изображения для превью
- `data/raw/` — место для исходных данных (не хранится в репозитории)

## Dashboard preview
![Dashboard preview](reports/figures/dashboard_preview.png)

## How to run
```bash
pip install -r requirements.txt
jupyter lab```



