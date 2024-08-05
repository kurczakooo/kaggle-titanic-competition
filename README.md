### Using the DecisionTreeRegressor model from scikit-learn
| submission | date | score | commit id | model | description |
|------------|------|-------|----------|--------|-------------|
| 1 | 31.07.2024 | Score: 0.69617 | [006071a](https://github.com/kurczakooo/kaggle-titanic-competition/commit/006071a1d5552386ae7f814ac6ed8f6e349115b3) | decision tree regressor | included id, pclass, age, sibsp, parch, and one hot encoded sex and embarked
| 2 | 31.07.2024 | ***Score: 0.75598*** | [26505e0](https://github.com/kurczakooo/kaggle-titanic-competition/commit/26505e06bb28eec708f0114b2d6c10d943e25e82) | decision tree regressor | same solution as previously, but included fare 
| 3 | 31.07.2024 | Score: 0.66985 | [d261ff5](https://github.com/kurczakooo/kaggle-titanic-competition/commit/d261ff53f7c9c9f0e29be5d96ab5c3891597fd0c) | decision tree regressor | encoded names and tickets
| 4 | 04.08.2024 | Score: 0.71052 | [f36e127](https://github.com/kurczakooo/kaggle-titanic-competition/commit/f36e127e0dd30f961f14f77a7263c83a5aac2d06) | decision tree regressor | included cabins excluded names and tickets, cabins are dummy encoded, as well as embarked, and Sex, also I decided to leave nan values for encoding to take care of them
| 4 | 04.08.2024 | Score: 0.63397 | [546f56d](https://github.com/kurczakooo/kaggle-titanic-competition/commit/546f56d92e3848b8b7b2c3c1b34b8e7f989bfd1c) | decision tree regressor | same solution as before, but dropped rows with nans
