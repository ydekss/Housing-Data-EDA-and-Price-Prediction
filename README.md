# Housing-Data-EDA-and-Price-Prediction

![The Best Week to List Your House is Just Around the Corner – The MLS™ Blog](https://i0.wp.com/themlsblog.com/wp-content/uploads/2022/03/Sell-a-house-in-april.jpg?fit=800%2C450&ssl=1)

I have taken the MagicBricks ( Real Estate Buyer and Seller ) Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualize them and tried to predict the house prices by fitting a Decision Tree Regressor.
## Exploratory Data Analysis and Decision Tree Regression MagicBricks Dataset

The Magicbricks dataset is a real estate dataset containing information about different properties in India. It includes 13 variables, such as property area, number of bedrooms and bathrooms, furnishing level, locality, parking availability, price, transaction status, property type, and price per square foot.

**This project covers the EDA of the MagicBrick dataset through which i suggested the business by observing the insights i got from the analysis. After the EDA i have also fitted a Decision Tree Regressor and a  Linear Regressor to predict the price of the houses and compare the accuracy of both the models.**

## MagicBricks Data

The data has following features and variables:
-  **Area:** The total area of the property in square feet.
-   **BHK (Bedrooms, Hall, Kitchen):** The number of bedrooms, hall, and kitchen in the property.
-  **Bathroom:** The number of bathrooms in the property.
-  **Furnishing:** The level of furnishing in the property (Unfurnished, Semi-furnished, or Fully-furnished).
- **Locality:** The locality where the property is located.
- **Parking:** The parking availability in the property (Covered or Open).
-  **Price:** The price of the property in Indian Rupees.
-  **Status:** The status of the property (Ready to Move or Under Construction).
-  **Transaction:** The type of transaction (New Property or Resale).
-  **Type:** The type of property (Apartment or House).
-  **Per_Sqft:** The price per square foot of the property.

## We will structure the code as follows

1.  Loading the data
    
2.  Preparing the data
    
3.  Exploratory Data Analysis
    
4.  Building the model and accuracy analysis
    
5.  Final Analysis of the model

## These are some of the insights

![Premium Vector | Illustration of young people have idea. couple having  solution, ideas lamp bulb metaphor in speech bubble above. solved question.  creative thinking.](https://img.freepik.com/premium-vector/illustration-young-people-have-idea-couple-having-solution-ideas-lamp-bulb-metaphor-speech-bubble-solved-question-creative-thinking_126608-1119.jpg?w=2000)

-  Property prices in India vary widely depending on the locality, property type, and other features. The price per square foot ranges from a few thousand Indian Rupees to tens of thousands of Rupees.
-  Most properties are apartments, with very few houses.
-  Most properties in the dataset are fully or semi-furnished, with very few unfurnished properties.
-  Parking availability is usually covered, and open parking is less common.
- The dataset shows that the average price per BHK (bedroom, hall, kitchen) increases as the number of BHKs in the property increases.  
- The dataset indicates that the price of properties is generally higher in urban areas compared to suburban or rural areas.
-  One observation is also that ready-to-move properties are generally priced higher than under-construction properties.
- There are more number of resale houses than new property
- The most common category of BHK or Bedroom hall kitchen in the houses are 3
- There is a strong correlation between the Price and the Number of Bathroom in the house.
-   Price is negatively correlated with Parking, Transaction-Resale, Status-Ready to move, Furnisning-Unfurnished.

**The dataset contains information about properties located in different parts of India, and it can be used to analyze the real estate market in the country.**

## Decision Tree Regressor
![Introducing TensorFlow Decision Forests — The TensorFlow Blog](https://1.bp.blogspot.com/-Ax59WK4DE8w/YK6o9bt_9jI/AAAAAAAAEQA/9KbBf9cdL6kOFkJnU39aUn4m8ydThPenwCLcBGAsYHQ/s0/Random%2BForest%2B03.gif)

After fitting both **Decision Tree Regressor**  and **Linear Regressor** and comparing their accuracy by checking their MSE, RMSE and R quared score. It was observed that Decision Tree Regressor predicts the price more accurately that Linear Regressor.

To take a look at the models, feel freeto look at the `ipnyb` file to explore more.
![This “thank you speech” is a must read! | PlanetSpark](https://lh4.googleusercontent.com/wZCVtsFnGRC6B_0nyNdJeNY5TKM2LWF3JjCGQjmqG-3HBd7gReXAsTXXpAoGKQFfU_oAFr6GsSObY2SOIsHPZ8zCdKEM4TUfWVqf4Q9mQVvaV3kZ7fdrgmG61JRrMEWXnU1aZ2ukTaC4NYKpUExE_b9TZw_C7qVYXP2T78rkqbYe271clci6L0zPMO-41w)



