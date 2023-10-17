# CVIP
amazon want to know what are reasons affect people decisions from buying from amazon what are most category that is effect people or people search for what area they need to improve 
based on poeple opinion.
so lets explore our data .
in this project amazon consumer behavior dataset from kaggle iused to cleaning data and analysis it and do feature engineering to help model to understand well the data 
first thing i start to see if there's any null values or duplicates and theres was no null valuse.
then i start to search for any anamoly value and i found one in improvement area column which was '.' and i drop it 
then start to remove any white space before and after name of columns to make it easy to access 
then i found in Service_Appreciation column that iti n  value_counts methode which count unique values it count customer service  twice as differnt from each other because one of them was containg whitespace 
at the end so i use strip() methode to remove whitespace.
then istart looking as timestamp column and make it all in same format (datetime) and then start doing feature engineering as i start to extract from it the day and month as columns 
by that our cleaning (cleansing) data is done .
# lets do our analysis (what we understand from data)
our data is 602 rows and 23 columns .
and this data collected in 2023 in june month that time ⌚ when survey was recorded .
its about consumers in amazon .
amazon try to know more about its consumers to maximize their effort 
our data has no outliers 
the most gender is female and most age is 23 and most people search about there products using categories
sometimes they found recommendations are helpful in decision making .
most people browse amazon few times a week.
most people are tend to see  results are viewed in multiple pages .
most people may be add things (products ) in cart while browsing (they in website of amazon).
why people abandonment the products from cart was for reasons and most of them because: 1) found better price elsewhere  2)changed their mind 
most of people reliable on reviews as modularity or Occasionally.
most people vote 3 to reviews importance .
people vote 3 as there stratification on service which is not bad but need to be improved.
people appreciate Product recommendations and Competitive prices as services .
people say that some area need to be improve as : 1) Customer service responsiveness
                                                  2)Product quality and accuracy 
                                                  3)Reducing packaging waste 
                                                  4)Shipping speed and reliability
most people see these 4 areas needs to be improved
most people buy/looking for Clothing and Fashion and Beauty and Personal Care and that is reasonable as most of people of gender female and most aged 23 .


 
 

