### Using the DecisionTreeRegressor model from scikit-learn
| submission | date | score | commit id | model | description |
|------------|------|-------|----------|--------|-------------|
| 1 | 31.07.2024 | Score: 0.69617 | [006071a](https://github.com/kurczakooo/kaggle-titanic-competition/commit/006071a1d5552386ae7f814ac6ed8f6e349115b3) | decision tree regressor | included id, pclass, age, sibsp, parch, and one hot encoded sex and embarked
| 2 | 31.07.2024 | ***Score: 0.75598*** | [26505e0](https://github.com/kurczakooo/kaggle-titanic-competition/commit/26505e06bb28eec708f0114b2d6c10d943e25e82) | decision tree regressor | same solution as previously, but included fare 
| 3 | 31.07.2024 | Score: 0.66985 | [d261ff5](https://github.com/kurczakooo/kaggle-titanic-competition/commit/d261ff53f7c9c9f0e29be5d96ab5c3891597fd0c) | decision tree regressor | encoded names and tickets
| 4 | 04.08.2024 | Score: 0.71052 | [f36e127](https://github.com/kurczakooo/kaggle-titanic-competition/commit/f36e127e0dd30f961f14f77a7263c83a5aac2d06) | decision tree regressor | included cabins excluded names and tickets, cabins are dummy encoded, as well as embarked, and Sex, also I decided to leave nan values for encoding to take care of them
| 5 | 04.08.2024 | Score: 0.63397 | [546f56d](https://github.com/kurczakooo/kaggle-titanic-competition/commit/546f56d92e3848b8b7b2c3c1b34b8e7f989bfd1c) | decision tree regressor | same solution as before, but dropped rows with nans
| 6 | 05.08.2024 | Score: 0.74162 | [f8eb204](https://github.com/kurczakooo/kaggle-titanic-competition/commit/f8eb20472238a3fa2558175e4503b81215c80079) | decision tree regressor | data preparation taken from submission 2, but sorted the features
| 7 | 05.08.2024 | Score: 0.73923 | [228ac3e](https://github.com/kurczakooo/kaggle-titanic-competition/commit/228ac3e1f4e30b319ae18e4a801764c2e2460421) | decision tree regressor | instead of filling nana for age with the average age, I left them as nans
| 8 | 12.08.2024 | Score: 0.72727 |  | decision tree classifier | changed model to DecisionTreeClassifier, excluded PassengerId from fitting
| 9 | 12.08.2024 | Score: 0.74162 |  | decision tree classifier | insted of mean age, i used median
| 10 | 13.08.2024 | Score: 0.73444 |  | decision tree classifier | added FamSize feature by combining SibSp and Parch features.
| 11 | 13.08.2024 | Score: 0.74641 |  | decision tree classifier | excluded SibSp and Parch, but left FamSize