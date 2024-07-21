# Классификация твитов

Решаем простую задачу классификации настроений твитов.

## Данные

Работаем с данными [Sentiment140 dataset with 1.6 million tweets](https://www.kaggle.com/datasets/kazanova/sentiment140).

## Модели

Были испытаны всего четыре модели: BernoulliNB, LinearSVC, LogisticRegression и CatBoostClassifier.

## Метрика и результаты

Все четыре модели справились с задачей на приемлемом уровне: Accuracy >80%. Лидировала модель логистической регрессии со значением метрики 82.57% на валидационной выборке.
