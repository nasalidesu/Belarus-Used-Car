# Belarus Used Car EDA and modelling

Dataset https://www.kaggle.com/lepchenkov/usedcarscatalog

## Tool and Language
* Google Colab
* Phyton

## Libraris
* pandas
* numpy
* mathplotlib
* seaborn
* sklearn

## Brief
The dataset contains used car ads from one of the most popular online catalogs in the country Belarus. The shape of data set consist of more than 38000 rows and 30 columns. Some of the column that worth to be highlighted are the cars model name, odometer value, manifacturer name, year produced. The inspiration to do this project analyse the resell value and long term car that was use by the people.

The notebook consist of
* Data Preprocessing
* Data Wrangling
* Data Science Questions , EDA, Visualization

#### Data Science Questions

#### 1. What is the optimal range for odometer value for anyone before they want to buy/sell used car ?

The odometer reading on a used car is important because it can give you an idea of how much the car has been driven, which can help you determine its condition and value. __Higher mileage is generally associated with a higher level of wear and tear on a vehicle, and it can also indicate that the car may need more maintenance or repairs in the future. On the other hand, a lower mileage car may be in better condition and may have a longer lifespan__. The odometer reading is also a key factor in determining the value of a used car

The plotting the data distibution to see which the density of the odometer values and find which the range before someone want to sell their car or someone to buy the used cars.
![image](https://user-images.githubusercontent.com/55817845/209690330-f44c4bb3-5d6e-4a66-8b38-f587827e6c72.png)

By implementing box plot and interquatile we can get the data dispersion and spread. Look like it doesn't have much different by implementing the standard deviation and quartile region

![image](https://user-images.githubusercontent.com/55817845/209690929-7a0db056-e032-486e-a5cd-e545f11ec5ff.png)

#### 2. Which brand is for used car is most and least popular?

There are many reasons why people choose to buy specific cars. Some people may be drawn to a particular make or model of car because of its reputation for reliability, performance, or safety. Others may be attracted to the features or technology offered by a particular car, or they may be drawn to the car's appearance or style. Some people may choose a car based on its fuel efficiency or environmental impact, while others may be more focused on the car's price or value. Ultimately, the specific car that someone chooses to buy will depend on their individual needs and preferences, as well as their budget and other personal considerations.

Most popular car is Volkswagen but there are many other cars in the catalog that significantly have high in number such as Opel, BMW, renault, Mercedes, Audi.

![image](https://user-images.githubusercontent.com/55817845/209691508-38339adb-f3c1-4952-b50a-a4477616f232.png)

#### 3. How long the car is listed in the catalog?

There are several reasons why a used car might be hard to sell, such as high mileage, wear and tear, a model or make that is not in high demand, a high price compared to its age or condition, and competition in the market. These factors can make the car less appealing to potential buyers and make it more difficult to sell.

![image](https://user-images.githubusercontent.com/55817845/209692153-323781f7-ea74-49b5-bc37-1dd2dcb805a4.png)

The car with brand Lincoln will most likely will take a long time to be resell since averagely it takes more than 200 days to sell followed by Москвич russian car which it takes more than 150 days to resell.

![image](https://user-images.githubusercontent.com/55817845/209692186-d0ae14dc-59b4-45a4-9d19-c49a8ff34595.png)

The used car that most likely to be resell faster is brand Rover and Seat. Both of these cars will averagely take less than 2 months to be resell again followed by Dacia, LADA, Skoda which take not more than 70 days to be resell

So if someone that has car with brand Rover most likely it will be sell faster and the brand Lincoln will take a long time to be resell

5. If someone want to know which car to buy for long term investment, which car brand has the highest resell values?
6. What is the forecast for used car price in future?

