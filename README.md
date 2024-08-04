### Using the DecisionTreeRegressor model from scikit-learn
| submission | date | score | commit id | model | description |
|------------|------|-------|----------|--------|-------------|
| 1 | 31.07.2024 | Score: 0.69617 | 006071a | decision tree | included id, pclass, age, sibsp, parch, and one hot encoded sex and embarked
| 2 | 31.07.2024 | Score: 0.75598 | 26505e0 | decision tree | same solution as previously, but included fare 
| 3 | 31.07.2024 | Score: 0.66985 | d261ff5 | decision tree | encoded names and tickets
| 4 | 04.08.2024 | Score: 0.71052 | f36e127 | decision tree | included cabins excluded names and tickets, cabins are dummy encoded, as well as embarked, and Sex, also I decided to leave nan values for encoding to take care of them
| 4 | 04.08.2024 | Score: 0.63397 |  | decision tree | same solution as before, but dropped rows with nans
