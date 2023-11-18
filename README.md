# Decision Tree Model Lab

In this lab, I will build an effective decision tree model. I will be presented with a business scenario and a dataset to use as I explore using a decision tree model to make predictions for a target based on multiple features. I will practice applying importing packages, loading data, and completing the cleaning process to build and evaluate a decision tree model with tuned hyperparameters.

## Data Dictionary

This activity uses a dataset called `Invistico_Airline.csv`. It represents the details of customer feedback for Invistico Airlines (a fictional name).

The dataset contains:

- **129,880** rows – each row is a different customer response
- **23** columns

| Column Name                | Type | Description                                                                 |
|----------------------------|------|-----------------------------------------------------------------------------|
| Satisfaction               | str  | My overall assessment of the airline, either “satisfied” or “dissatisfied” |
| Gender\*                   | str  | For purposes of this dataset, “Male” or “Female” were the only two responses  |
| Customer Type              | str  | My loyalty, “Loyal Customer” or “Disloyal Customer”                   |
| Age                        | int  | My age                                                              |
| Type of Travel             | str  | My reason for travel, “business” or “personal”                        |
| Class                      | str  | My purchased seat class, “Business,” “Eco,” or “Eco Plus”             |
| Flight Distance            | int  | How far did my flight travel                                                 |
| Seat Comfort               | int  | My rating of seat comfort                                           |
| Departure/Arrival Time Convenient | int | My rating of convenience for departure and arrival time             |
| Food and Drink             | int  | My rating of food and drink                                           |
| Gate Location              | int  | My rating of the convenience of the gate location                     |
| Inflight Wifi Service      | int  | My rating of the inflight wifi/Internet service                      |
| Inflight Entertainment     | int  | My rating of inflight entertainment                                  |
| Online Support             | int  | My rating of online support services of the airline                  |
| Ease of Online Booking     | int  | My rating of the ease of booking tickets online                      |
| On-board Service           | int  | My rating of service by airline personnel                            |
| Leg Room Service           | int  | My rating of the amount of legroom                                   |
| Baggage Handling           | int  | My rating of convenience or ease of baggage handling                  |
| Check-in Service           | int  | My rating of check-in service by airline personnel                   |
| Cleanliness                | int  | My rating of cleanliness of the airplane                                 |
| Online Boarding            | int  | My rating of online boarding process                                 |
| Departure Delay in Minutes | int  | How long was the departure delay for my flight measured in minutes          |
| Arrival Delay in Minutes   | int  | How long was the arrival delay for my flight measured in minutes            |

\*This data has been modified for the purposes of this exercise. Specifically, the Gender column was dropped. While acknowledgement of a gender spectrum varies across societies, many societies now understand that gender is not a binary and there is fluidity in the category across people and time, so creating categories that allow for that leads to more accurate data collection processes.

The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction).
