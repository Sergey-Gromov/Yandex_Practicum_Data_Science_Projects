# Анализ текстовых комментариев  для интернет-магазина

Интернет-магазин запускает новый сервис: теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах.   
То есть, клиенты предлагают свои правки и комментируют изменения других.   
Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

**Цель проекта:**  
Обучить модель классифицировать комментарии на позитивные и негативные.  
В распоряжении имееется набор данных с разметкой о токсичности правок.  
В результате построения модели необходимо достичь значения метрики качества F1 не меньше 0.75.

**Навыки и инструменты:**  
python  
pandas  
matplotlib  
seaborn  
sklearn.model_selection.train_test_split  
sklearn.linear_model.import LogisticRegression  
sklearn.feature_extraction.text.TfidfVectorizer  
sklearn.dummy.DummyClassifier  
sklearn.metrics.f1_score  
sklearn.model_selection.GridSearchCV  
sklearn.decomposition.TruncatedSVD  
lightgbm.LGBMClassifier  
re  
tqdm.notebook.tqdm  
tqdm.pandas()  
string  
nltk.stem.WordNetLemmatizer  
nltk.tokenize.word_tokenize  
nltk.download('punkt')  
nltk.download('stopwords')  
nltk.download('wordnet')  
nltk.corpus.stopwords  
nltk.corpus.wordnet  

**Общий вывод:**  
Сотрудникам интернет-магазина предлагается использовать разработанную в данном проекте модель Логистической регрессии с подобранными гиперпараметрами для классификации комментариев на позитивные и негативные, в рамках нового сервиса, с целью поиска токсичных комментариев и отправки их на модерацию.  
Данная модель показала наилучший результат по метрике F1 существенно выше требуемого значения.
