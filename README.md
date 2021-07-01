# YelpLogisticModel
Aggregated and prepped open-source Yelp data into two subgroups, permanently closed and open restaurants, represented in dataset as binary variables for retrospective case study
The predicting variables were restaurant’s price range, Yelp star ratings, and review count. 

## Results
From the predicting variables, review count had the strongest association with the outcome of a restaurant staying open or not.

The final logistic regression: $y = 1.3529 - 0.189 price_range - 0.670 stars + 0.608 lnreview$
