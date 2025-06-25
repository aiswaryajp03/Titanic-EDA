# Titanic-EDA

1.Dropped irrelevant columns (PassengerId, Name, Ticket, Fare, Cabin, Embarked).
Handled missing values by filling Age with a constant value (29).

2. Feature Engineering
Created one‑hot encoding for Sex.
Created new features:
FamilySize = SibSp + Parch
IsAlone = 1 if FamilySize == 1, else 0

3. Exploratory Data Analysis (EDA)
Visualized Age distribution and its outliers.
Analyzed relationships between family connections (SibSp vs Parch).

4. Data Pre‑Processing
Normalized the data using Min‑Max Scaling.

5. Modeling
Trained a Logistic Regression model.
Evaluated performance using a train‑test split.
