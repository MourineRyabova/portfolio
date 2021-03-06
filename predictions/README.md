## Минимизация оттока клиентов фитнес-клуба

Сеть фитнес-центров разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.

Основные задачи проекта:
- Выделение характерных групп посетителей клуба и анализ факторов оттока 
- Прогноз вероятности оттока в горизонте следующего месяца методом машинного обучения.

Для разбивки по группам использована кластеризация (дендрограмма, K-Means). Для прогнозирования - модели LogisticRegression, RandomForest. 
Метрики классификации для выбора модели: Accuracy, Precision, Recall, F1, ROC-AUC.

Итог: даны рекомендации по работе с различными клиентскими группами, выделенными путем построения дендрограммы. Выявлен наиболее оптимальный алгоритм прогнозирования оттока. 
