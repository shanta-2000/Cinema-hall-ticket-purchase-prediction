# Cinema-hall-ticket-purchase-prediction
## Dataset description
This dataset records detailed information about ticket sales and customer behavior at a cinema hall, offering insights into various aspects such as demographics, movie genre preferences, seat selection, ticket pricing, and customer retention patterns. It is designed to help analyze customer engagement, spending behavior, and factors that influence repeat visits to the cinema. The data is useful for predictive modeling and can support decision-making processes related to customer retention, marketing strategies, and optimizing cinema operations.

## Columns Overview:

Ticket_ID (Categorical):

Description: A unique alphanumeric identifier for each ticket purchase. The ID consists of a random uppercase letter (A-Z) followed by a 4-digit number (e.g., B7539, Y1344). Significance: This column helps identify each individual transaction. It's a categorical variable, essential for tracking specific customer purchases but not related to other variables directly.

Age (Numerical):

Description: The age of the customer who purchased the ticket, ranging between 18 and 60 years. Significance: Age is an important demographic feature, providing insights into customer segments. For example, younger audiences might prefer different movie genres or seating types compared to older customers. Analyzing age data can help cinema halls cater to the needs of various age groups.

Ticket_Price (Numerical):

Description: The price the customer paid for the ticket, typically ranging from  10to 25. The price varies based on factors like movie time, seat type, or cinema location. Significance: Ticket price reflects customer spending and the cinema's pricing strategy. Understanding how ticket pricing impacts customer behavior can help optimize ticket sales and maximize revenue.

Movie_Genre (Categorical):

Description: The genre of the movie the customer attended, which can include one of the following: Action, Comedy, Horror, Drama, or Sci-Fi. Significance: Genre preferences are crucial for understanding customer interests. Analyzing which genres are most popular can guide movie scheduling, marketing strategies, and even help in curating personalized recommendations for customers.

Seat_Type (Ordinal):

Description: The type of seat selected by the customer, with three ordinal categories: Standard (Basic seating option) Premium (Enhanced seating with added comfort) VIP (Exclusive seating, offering premium features like extra legroom and priority service) Significance: Seat type provides insights into customer spending behavior. Premium and VIP seat types typically correlate with higher ticket prices, and understanding seat preferences can help in optimizing cinema layout and pricing strategies. Additionally, this column can be used to gauge the popularity of high-end seating options.

Number_of_Person (Mixed Variable):

Description: The number of people accompanying the customer. This can either be: Alone: The customer attended alone. 2–7: The customer attended with a group of 2 to 7 people. Significance: Group size is an important factor in understanding customer preferences and behavior. For example, groups might purchase more tickets or opt for different movie genres and seat types than solo attendees. This column is crucial for analyzing social dynamics and group behavior in cinema attendance.

Purchase_Again (Target - Binary):

Description: A binary target variable indicating whether the customer is likely to return and purchase another ticket. It has two possible values: Yes: The customer is likely to return for another movie. No: The customer is not likely to return. Significance: This is the key column for predictive modeling. It is used to assess customer retention and predict the likelihood of future ticket purchases. Analyzing the factors that influence repeat purchases (e.g., age, genre preferences, seat types) helps cinema halls optimize marketing and customer engagement strategies.

# Task
Rename this notebook with your id

Load given dataset

Display dataset information and clean the data (print first 15 rows, show all column name, check for null, handle null values, show all unique values for non numeric column)

Map the non numeric colum using dictionary. Note, your target column is "Purchase_Again".

Apply Machine learning algorithms (SVM, DT and RF) and display their accuracy, precision, recall, confusin matrix. Note, you MUST write your findings after each code blocks. This is where you discuss regarding the reuslt you received.

Make a comparison table with all the results from different ML Algos.

Apply "grid search" to improve the achieved results for SVM, DT and random forest. Hint: you need to find what are the parameters to be tuned and what is their expected range. Accordingly, set 'grid search' parameters.

Suggest and use anyother parameter tuning technique that is more suitable that grid search for any of these ML Alogs. Justify your choice.

Finally, report the best models that you created. Justify why it is best. Carefully report required performance measures. Hints: Different performance measures may be selected for balanced vs unbalanced dataset.

