***Summary of the Problem***
With this dataset, I determined how much people prioritize specific ratings when rating the overall value of the car for its respective price. Along with the value, the other ratings people gave out of a scale of five were Comfort, Interior Design, Performance, Exterior Styling, and reliability.

***Analyzing the Data***
First, I got the data of the respective columns, turning the dataframe into a list for easier use. Second, I got the R^2 values of each respective rating compared to the expected value for the value of the car, which luckily was given in the database. Then, I took the average of the other values aside from each respective rating and found the R^2 values of the average compared to the expected value for the value of the car.

***Results**
The initial results I was looking into were the difference in R^2 values between each respective rating vs. the expected value for the value of the car and the R^2 values between all the other ratings averaged vs. the expected value for the value of the car. At first glance, it seems like customers valued reliability and exterior rating the most when considering value. However, since the R^2 values were so close to each other, it can be concluded that on average, a customer will value each rating equally when considering the value of a car compared to its price. 


***Sources I used**
https://matplotlib.org/stable/index.html - graphing
https://www.ncl.ac.uk/webtemplate/ask-assets/external/maths-resources/statistics/regression-and-correlation/coefficient-of-determination-r-squared.html#:~:text=%C2%AFy - R^2 values
https://pandas.pydata.org/docs/reference/index.html - pandas
