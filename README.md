# AB-Testing
A/B Test for an international online store.

Technical description
- Test name: recommender_system_test
- Groups: А (control), B (new payment funnel)
- Launch date: 2020-12-07
- The date when they stopped taking up new users: 2020-12-21
- End date: 2021-01-01
- Audience: 15% of the new users from the EU region
- Purpose of the test: testing changes related to the introduction of an improved recommendation system
- Expected result: within 14 days of signing up, users will show better conversion into product page views (the product_page event), product card views (product_card) and purchases (purchase). At each of the stage of the funnel product_page → product_card → purchase, there will be at least a 10% increase.
- Expected number of test participants: 6000

Libraries used:
- pandas
- numpy 
- matplotlib.pyplot
- seaborn 
- datetime
- sidetable
- plotly.express 
- plotly.graph_objects
- math 
- scipy 
- statsmodels.stats.proportion import proportions_ztest, proportion_confint
- statsmodels.stats.api 

files needed:
- ab_project_marketing_events.csv
- final_ab_new_users_upd.csv
- final_ab_events_us.csv
- final_ab_participants_upd.csv

you will need jupyter notebook installed on your local
