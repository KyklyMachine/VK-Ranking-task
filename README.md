# VK-Ranking-task
Solving the ranking problem

В папке src представлены следующие файлы:
- eda.ipynb – разведочный анализ данных.
- xgboost_model_baseline.ipynb – базовая модель (XGBoost ranker с LambdaMART).
- catboost_model.ipynb – (catboost ranker)

|       Модель       | NDCG@Doc |
|--------------------|----------|
|XGBRanker (baseline)|  0.5245  |
|Catboost Ranker     |  0.9153  |
