# Улучшение процесса обогащения золота

**Цель проекта:**  
Подготовка прототипа модели машинного обучения для компании, которая разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды, что может помочь оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

При работе над проектом будут использованы предоставленные данные с параметрами добычи и очистки.

**Навыки и инструменты:**  
python  
pandas  
numpy  
matplotlib  
scipy  
sklearn.model_selection.cross_val_score  
sklearn.metrics.mean_squared_error  
sklearn.metrics.mean_absolute_error  
sklearn.metrics.make_scorer  
sklearn.linear_model.LinearRegression  
sklearn.tree.DecisionTreeRegressor  
sklearn.ensemble.RandomForestRegressor  
sklearn.dummy.DummyRegressor  
sklearn.model_selection.GridSearchCV  

**Общий вывод:**  
Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
