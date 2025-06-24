# Day 12 Log – Feature Engineering

Today I created new features to give my model more context and signal:

- `Fare_per_Person`: Fare divided by family size
- `IsChild`: Boolean column for passengers under 13
- `Sex_Pclass`: Combined gender and class into one string
- `Fare_to_Median`: Compared a person’s fare to the median of their Pclass

I also explored the effect of some of these using groupby and pivot tables.

Learned that Fare alone isn’t always useful — but Fare compared to the class median tells a better story.  
Same with combining Sex and Pclass — that added more nuance.

This helped me understand that feature engineering is like **teaching the model what to care about** — and I liked it.
