### Using the DecisionTreeRegressor model from scikit-learn
| submission | date | score | model | description |
|------------|------|-------|-------|-------------|
| 1 | 31.07.2024 | Score: 0.69617 | decision tree regressor | included id, pclass, age, sibsp, parch, and one hot encoded sex and embarked
| 2 | 31.07.2024 | Score: 0.75598 | decision tree regressor | same solution as previously, but included fare 
| 3 | 31.07.2024 | Score: 0.66985 | decision tree regressor | encoded names and tickets
| 4 | 04.08.2024 | Score: 0.71052 | decision tree regressor | included cabins excluded names and tickets, cabins are dummy encoded, as well as embarked, and Sex, also I decided to leave nan values for encoding to take care of them
| 5 | 04.08.2024 | Score: 0.63397 | decision tree regressor | same solution as before, but dropped rows with nans
| 6 | 05.08.2024 | Score: 0.74162 | decision tree regressor | data preparation taken from submission 2, but sorted the features
| 7 | 05.08.2024 | Score: 0.73923 | decision tree regressor | instead of filling nana for age with the average age, I left them as nans
| 8 | 12.08.2024 | Score: 0.72727 | decision tree classifier | changed model to DecisionTreeClassifier, excluded PassengerId from fitting
| 9 | 12.08.2024 | Score: 0.74162 | decision tree classifier | insted of mean age, i used median
| 10 | 13.08.2024 | Score: 0.73444 | decision tree classifier | added FamSize feature by combining SibSp and Parch features.
| 11 | 13.08.2024 | Score: 0.74641 | decision tree classifier | excluded SibSp and Parch, but left FamSize
| 12 | 11.09.2024 | **Score: 0.77511** | fine-tuned random forest classifier | added features: FamSize, IsAlone, FarePerPerson, NameLength. not using Name, Cabin, Ticket
| 13 | 14.09.2024 | Score: 0.76794 | XGBClassifier, finetuned | same features as previously