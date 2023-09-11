# Прогнозирование отттока клиентов телеком компании

**Цель проекта:**  
Разработка модели модели машинного обучения для оператора связи, позволяющей прогнозировать отток клиентов.
Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.
Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

Эффективность работы модели будет оцениваться метрикой ROC-AUC.
Модель должна показать на тестовой выборке уровень метрики ROC-AUC не менее 0.85

**Навыки и инструменты:**  
python  
pandas  
numpy  
matplotlib  
seaborn  
sklearn.metrics.accuracy_score
sklearn.metrics.roc_auc_score
sklearn.metrics.roc_curve
sklearn.metrics.confusion_matrix
sklearn.metrics.ConfusionMatrixDisplay
sklearn.preprocessing.OneHotEncoder
sklearn.preprocessing.StandardScaler
sklearn.l_selection.train_test_split
sklearn.model_selection.GridSearchCV
sklearn.ensemble.RandomForestClassifier
sklearn.linear_model.LogisticRegression
sklearn.dummy.DummyClassifier
catboost.CatBoostClassifier
lightgbm.LGBMClassifier
phik.phik_matrix

**Общий вывод:**  
Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
