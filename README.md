- Решение задачи регрессии: предсказать температуру сплава в конце процесса обработки стали;
- Используемые библиотеки: numpy, pandas, matplotlib, seaborn, ploty, lightgbm, catboost, hyperopt, keras;
- Анализ и чистка данных (обработка пропусков и выбросов): describe, agg, groupby, apply, query, to_datetime, isnull, fillna, dropna, join, concat, ...;
- Проверка данных на мультиколлениарность: corr (heatmap), variance_inflation_factor (VIF анализ), SelectKBest (F-regression);
- Предобработка данных (разделение на выборки и масштабирование): train_test_split, StandardScaler;
- Используемые модели:
1. Линейная регрессии (LinearRegression);
2. K-ближайших соседей (KNeighborsRegressor);
3. Случайный лес (RandomForestRegressor);
4. Градиентный бустинг (LightGBM, CatBoost);
5. Нейросети (полносвязная сеть (maltylayer perceptron), сверточная сеть (convolution multylayer network), сеть с архитектурой LeNet);
- Кросс-валидация и настройка гиперпараметров (cross_val_score, GridSearchCV, RandomizedSearchCV, hyperopt);
- Анализ значимых признаков (RidgeCV, feature_importances, permutation_importance);
- Упаковка в пайплайн (Pipeline) нескольких шагов, упаковка в пайплайн несколько моделей, использование пайплайн совместно с кросс-валидацией и оптимизацией гиперпараметров.
