# Проект для «Викишоп»

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Обучила модель классифицировать комментарии на позитивные и негативные. Для оценки качества моделей применяла метрику f1.

*Стек:* numpy, nltk, sklearn, matplotlib, wordcloud, TfidfVectorizer, LogisticRegression, RandomForestClassifier, DecisionTreeClassifier, CatBoostClassifier
