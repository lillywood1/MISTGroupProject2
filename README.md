# Group 4 MIST Group Project 2 (Tableau)
# Team Name
29704 Group 4

# Team Members:
1. Ryan Kelly: [@Rjk4133](https://github.com/Rjk4133)
2. Ryan Dean: [@RDean45](https://github.com/RDean45)
3. Cameron Smith:[@camjshmitt](https://github.com/camjshmitt)
4. Mattie Garett: [@MatGar22](https://github.com/MatGar22)
5. Lilly Wood: [@lillywood21](https://github.com/lillywood1)
7. Wyatt Smith: [@wsmith1287](https://github.com/wsmith1287)

# Data Set Link: 
https://catalog.data.gov/dataset/sales-tax-collections-by-state

# Data Set Description & What it Contains
This data set is titled “Real Estate Sales 2001-2020” and was obtained on the data.gov website. This data set contains all real estate sales that took place between 2001 and 2020 in the state of Connecticut. Additionally each sale that is included must have been above two-thousand dollars. In terms of dimensions, this real estate data has 13 columns and 997,213 rows of data. The data that each on of these columns contains are, the serial number of the sale, the list year of the property, the date the sale was recorded, the town the property is located in, the address of the property, the assessed value of the property, the sale value of the property, the ratio of property assessed value to property sale value, the type of property, if that property is residential then the type of residential property, accessor remarks, OPM (Office of Personnel Management) remarks, and finally specific geographic location. Also, it should be noted that the accessor remark data column refers to remarks of local government officials that assess the value of a property and the OPM remarks is regarding the remarks of the Office of Personnel Management, which manages government officials in a quasi-human resource role.

# Question 1
How has the average sale price per year changed of one family, two family, and three family homes in Hartford, Bridgeport, and Connecticut as a whole from 2007-2020?

# Question 2
How do the unemployment rate and median income relate to the difference in sale amount and assessed value?

# Question 1 Importance


# Question 2 Importance


# Data Set Manipulations
-A residual was calculated by taking the averaged assessed value from the average selling price. The purpose of this was to use the residual to evaluate the unemployment rate on the difference between these two variables. A positive residual would show average selling price to be higher, while a negative would show average assessed value to be higher. Comparing the residuals to the unemployment rate over a span of time allows more insight for real estate market. This calculation was used for question two.

-Question one used the average selling price and how it changed across one, two, and three family homes in two cities and the state of Connecticut. This was already provided in the data set, but the data was manipulated to compare how the prices changed over time based on these variables, and then visualized to provide more clarity on how exactly the average selling price differs. Data was excluded to focus on the specific cities and provide an accurate visualization of the data. 

# Question 1 Analysis
Our visualizations show that the average sales price of a single family home in Connecticut as a whole is much greater than the average price of a single family home in the towns of Bridgeport and Hartford respectively. It is also interesting to break this data down by the type of home because two and three family home prices look much different than the one family home prices - the average sales prices of two and three family homes in Connecticut is about the same as the average sales price of two and three family homes in both the towns of Bridgeport and Hartford. From the data, we can also conclude that single family homes had the highest average selling price over two and three family homes no matter the location of the home. 

# Question 2 Analysis
Our visualization shows that as the unemployment rate increases, the residual between the sale amount and assessed value decreases. This can be explained by the fact that sales price decreases and gets closer to the assessed value as economic conditions worsen. In 2010 when the unemployment rate peaked at 9.5%, the residual reached a minimum of $-50,000 which shows that the average selling price was lower than the average assessed value. The opposite is true for the median income which has a direct relationship with the residual, as the demand for luxury goods like real estate increases as income increases, driving sales prices up. The visualization shows that until 2016, as the median income increases the residual increases as well. After 2016 it is important to note that the correlation drops off, hinting that there may be other factors at play. 

# Tableau File
