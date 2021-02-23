# Ford GoBike dataset Exploration

## dataset:

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area, containing 183412 record with 15 variable. 
original dataset here: https://www.fordgobike.com/system-data

                            -----------------------------------------------------------------
                            
## findings sammary :
univariate: 
- in duration there are a fair number of customers spend (more than 200~1400 minutes) which mean, we have some cutomers love
to spend half day or day with bikes but they are not alot 
- looks most of users are males by 75% and the rest (23% females) , (2% other or unkown)
- most of the renters are young ages betwean(1980-2000)
- it apears that stations with first 100 ids are the most used ones that will need further investegation with some more variables tells more about the stations
- most of the rents happens between(8-9AM) and (5-6PM) we may focus in these two periods in our days to put offers and gain more of the customers
- the most used bikes are bikes with high ids more than 4000, this also will need more investigation with bikes characterstics with ids to figure out the reason behind the high demand on them
                              ----------------------------------------------------------------
bivariate:
- females like to spend longer durations with bikes more than males we should put that in consideration and may be put some female orianted bikes 
- in both gender the higher propotion was subscribers but in case of males the percentages for subscribers and customers was (91%,9%)respectivly and for females (89%,11%) for now its a good ratio but if we really want to improve the service we may focus on the users in the customers proportion to try turning them into subscribers 
- looks males share bikes more than females sense the sharing rates was (10%,8.8%)respectivly
                              ----------------------------------------------------------------

multivariate:
- from the plots we can see for the both genders age and duration relation is the same a postive correlation
- although females have fewer data points but most of them have higher duration than males 
- the relation betwean tha year of birth and duration is a strong relation but its non-linear.
-it seems subscribers spend less time with the bikes than customers in both genders, but females still have higher duration even after dropping outliers.

## Key Insights for Presentation
i focus first in viewing eatch solo variable to view thair distrubutions and clear how they look and that will become useful later sense i will merge these distrubutions later i do that for duration, gender, customer types,year of birth ,stations ,bikes ids  and starttime.

then i started viewing the relations betwean some numerical variables and we will find that thair are no strong linear relations betwean variables except for the longtitude and latidude which is only represent locations and didn't come useful answering questions, so i will start searching the relations betwean (numerical and categorical) and (categorical with eatch other)
like durations with gender and user type with gender,there is some parts i make use of feature engineering to come up with sharing rate.

at last i started putting 
multivariables together to gain an overal look betwean the 3 variables like (gender ,age and duration)