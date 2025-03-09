# Russian-real-estate
That project provides categorical boosting model which has 0.913 R-squared coefficient and predicts russian real estate prices in 2018-2021 time period with about 11.45% average accuracy. This project also provides some visualisations and interactive maps. Model works in 1-100 million rubbles price variety and 16-125 square meters price 

Initially CatBoost model has R-squared equal to only 0.3 cause of some strange values where price for square meter was extremely lower or higher than average, so I cleaned original database from that values
And SQL-requests helped to understand what borders of strange values should be installed

Applied ipynb-file also provides hist-plot with the model errors distribution
Final model has the maximum acceptable depth of 16 knots and includes 1200 trees 
It has 1 GB size and required 2 hours for training

1/3 of all predicts have lower than 5% error
