# Steps

* Hypothesis: A well-formed hypothesis (statement) that you will be testing. This
should follow the form discussed in class. Be as specific as possible.
    * see final_project_notebook


* Dataset: explanation of the dataset. This should include an explanation of why the
dataset was created, who created it, and an explanation of features, target variables,
etc. It is important to provide appropriate references. A naive reader should be able
given enough information to understand the work done on the dataset.
    * Parking tickets


* Data preprocessing: identification of required features, proper handling of missing
values (removal, imputation, etc.), and supporting documentation for your decisions
such as the number of missing values relative to the size of the dataset.
    * Preprocessing steps:
        * Holiday Data
        * Weather Data
    * Geotagging
        * Note: Exact address matching failed for many tickets for two main reasons: 1) manual data entry errors by parking enforcers (e.g., using approximate house numbers or "BLOCK"), and 2) the city's GIS Address Points dataset itself is incomplete, missing many valid, existing Milwaukee house addresses (verified via Google Maps). This justifies the use of a 100-block averaging fallback to map approximate ticket locations.



* Data analysis and visualization: quantitative (statistical) and visual analysis of
your data. You should apply quantitative measures of centrality, distribution, and
correlation. In addition, you should provide visual analysis through plots that are
appropriate for a better understanding of your data and how the data can be used to
answer your question. Using the appropriate clustering algorithm for different measures
can be very helpful for better understanding the relationships in your data.

    * Heat Mapping (filter on features)
    * Trend Analysis (Chi-square test across categories, Pearsons r for weather data)


* Data modeling and prediction: development of a predictive model, regression or
classification. Your model development should include experimentation with feature
selection. The effect of different features on your target variable as well as associations
between features should be identified. You should appropriately use train and test data
when evaluating your models. It is expected that you will use an established machine
learning library – you are not expected to implement an algorithm from scratch.
    * Possion regression


* Results analysis: Summary of your interpretation of the results. Are the results
statistically significant? Did you prove or disprove your hypothesis. How could you
improve your analysis? Lessons learned.
    * Dealing with the assumptions of possion regression
    * Features we wanted but couldn't get