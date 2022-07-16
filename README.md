# PLANE-CRASH-ANALYSIS-FOR-30-DAYS-OF-LEARNING-CAPSTONE-PROJECT
PLANE CRASH ANALYSIS ALL AROUND THE WORLD FROM 1908-2010 

## INTRODUCTION 
THIS PROJECT IS FOR THE #30DAYSOFLEARNING, To display my skills in the analysis of data in the data analytics track of the #30DAYSOFLEARNING using POWER BI , and all the overall steps involved( E-T-l, DATA MODELLING,EXPLORATORY ANALYSIS AND EXPLANORYANALYSIS/VISUALIZATION)                                                                   
## OBJECTIVE 
After being assigned this project to analyse the data by my project cordinator, i carefully accessed the data. 
And after much critical thinking, i found out questions that needed to be answered: 

1. Total number of flights that crashed from year 1908-2010 
2. Total number of people aboard the crashed flights from year 1908-2010
3. Total number of survivors from the crashed flights 
4. Total number of fatalities as a result of the crashed flights
5. The major causes of flight crashes 
6. The route with the major fatalitis caused by flight crashes
7. The location with highest fatalities

## DATA SOURCE 
since 1908 (full history of airplane crashes throughout the world) until 2010. At the time this dataset was created and hosted by Kaggle in(2016-06-09), the original version was hosted by Open Data by socrata at: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq, but unfortunately that is not available anymore. The dataset contains data of airplane accidents involving civil,commercial and military transport worldwide from 1908-09-17 to 2009-06-08.         

#### [DATA SOURCE:https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908]                                                                                   

#### [DATA LICENCE:http://opendatacommons.org/licences/odbl/1.0]  

## DATA EXTRACTION AND LOADING 
The data was extracted from the data source above and loaded into POWER BI using the get data from web feature on power bi

![Screenshot (14)](https://user-images.githubusercontent.com/107328546/179244863-fc21fe07-51c3-4cdd-a3ea-9ff66bfcd653.png)

## DATA TRANSFORMATION/CLEANING  
After loading the data into POWER BI the data was cleaned and transformed using power query in power bi  

![Screenshot (11)](https://user-images.githubusercontent.com/107328546/179245946-3045c678-634c-465c-a708-4721bf1ea527.png)

## DATA MODELLING 
The data was denormalized( the data was in one table) therefore the data doesnt require additional manual modelling by me, so the data was ready for visualization right after transforming and loading 

![Screenshot (15)](https://user-images.githubusercontent.com/107328546/179247810-40255a36-da7d-426c-a318-034c286d8202.png)

## EXPLORATORY ANALYSIS 
i worked on the data to derive insights and to crack all the neccessary information the dataset has hidden in it, and also to answer my questions/objectives 

## EXPLANATORY ANALYSIS 
After working on the data, going through the data exploratory analysis ohase i got quite some interesting insights and the answers to my questions/ objectives 

1. #### This visual gives us insight into our first, second and third objective
- We can clearly see that over the year 1908-2010 there was 5,268 flight crashes recorded around the globe.
- We  can also see that the number passengers aboard this total of 5,268 flights was 145,000(145k). 
- And also we can see that 39,000(39k) passengers survived the crashes. well, i had always thought everyone involved in a flight crash would always die, like common i mean the high altitude(scary) LOL, but No, wow! that doesn't happen to be the case.   

According to WikiHow; 
the odds of dying on a commercial airline flight are actually as low as 9 million to 1. That said, a lot can go wrong at 33,000 feet (10,058.4m) above the ground , and if you,re unlucky to be aboard when something does , the decisions you make could mean the difference between life and death. Almost 95% of flight crashes have survivors, so even if the worst does happens your odds are'nt as bad as you think. So, if you've never boarded a flight before,you have nothing to be scared of, make your next trip on a flight and enjoy the one of the greatest innovations of engineering.

![Screenshot (6)](https://user-images.githubusercontent.com/107328546/179326781-e034782f-b08f-442e-8e34-9d4453b5df09.png)

2. #### This visual gives us insight into our fourth, fifth and sixth objective 
- We can see that the number of fatalities was 105,000(105k) in all 5268 flights that crashed.
- We can also see that the route "Tenerife-Las Palmas" had the highest number of fatalities (I almost felt like I'm never taking this route next time I'm planning on boarding a flight, LOL).
- We can also see that the major causes of airplane crashes was as a result of fuel shortage up their in the sky, also bad weather conditions, the engine failing just like cars and every other mechanical objects does(but up there is a whole lot of problem, because i've never seen an airplane mechanic come up there with parachutes to do repairs, LOL, and we also saw that another major cause of crashes was as a result of a flight crashing into different objects(mountains, valleys, ...).

![Screenshot (10)](https://user-images.githubusercontent.com/107328546/179347832-6b6ff2e5-5053-44b8-8a9e-488cff23ce48.png)
The outlier in the visual for route are all the routes that were unnamed in the dataset.

3. #### This visual tells us about our last object lets dive in
- We can see that Russia is the country and location with highest total cummulative fatalities with 6317 deaths(6.3k).
- Russia had its worst year from flights death in year 1973 with 398 deaths from a single crash.  

![Screenshot (13)](https://user-images.githubusercontent.com/107328546/179349004-bfa620a7-0f4f-4235-a697-5db2313e5879.png)

## ADDITIONAL INSIGHTS 
Because of my curiosity as a data analyst i dived deeper into exploring/uncovering some more insights from each of my visual, bekow ard my findings
- From year 1908-2010, the year 1972 recorded the total amount of 104 flight crashes(worse year in the history of flight crashes).
- Before the peak year of 1972, the number of crashes grew steadily from year 1908 and then then the numbers declined at a fair rate due to technological findings, it is important to note that the early stages from 1908 through the growth and advancement in flight usage there were not as many flights as of today, hence, the year 1908 had just one crash and so was the years that came after with just a very small arithemetic increase in flight crashes until the first peak in the year 1946 with 80 crashed flights, while six years at 1940 18 crashed flights were recorded, the years after 1940 before 1946 which are 1941 had 20 crashes, 1942 had 21, 1943 had 39, 1944 had 47, 1945 had 69.
- Also i found out that there was a positive correlation between the rise in pasengers aboard, which also would result in an increase in number of flights, and the nuber of fatalities, through the early years.   
- There where was about 3 times more fatalities than survivors, we could clearly see that in the numbers with fatalities summing up to 105k and survivors at 39k.
- Some other causes of airplane crashes were caused by wildlife(birds crashing into the propellers), landing errors, mechanical errors and pilot errors and also miscommunication between flight crews and air traffic control.
- From my analysis which you can clearly see on the visual above for route "Tenerife-Las Palmas" was the route with the highest number of death in a single crash killing 583 passengers, i got curious dug deeper into the summary recorded in the dataset and i found out that this crash was the deadliest ever and still remains the deadliest ever in history, it happened after two boeing747's collided on a foggy runway on the island of tenerife in the canary islands. it occured after series of miscommunications between two flight crew members and Air traffic control 
- When did it all start flight crashes,the first recorded flight crash was in year 1908, which killed just one person of the two people which were aboard the pilot orville wright sustained injuries but survived and Lt. Thomas selfridge a volunteer passenger died making him the first person ever to die in flight crash
- The airplane type that recorded the first crash was a flyer wright iii.
- Also the Douglad DC-3 recorded the highest cumulative fatalities with 4793 deaths ( we would see this from the visual below).
- Military flights crashed the most with about 4.4k crashes of the total 5268 crashes that's a lot, while passenger flights had close to 1k with about 810 flight crashes (wars were a major contributor to military flight crashes).

 ##### Exploring Aeroflot:![Screenshot (12)](https://user-images.githubusercontent.com/107328546/179363075-99c73177-6b19-4f88-b0d2-dbed5d284db1.png)
 ( From our visual looks like Aeroflot has the most number of crashes and fatalities for all time, well,maybe if knew this before I wouldn't have flown with them last summer, haha)
- Through the year 1908-2010 Aeroflot was the airline operator with most number of fatalies with 7156(7.2k) deaths recorded.
- Aeroflot had it's worst year in 1973 with 767 fatalities. Clearly the 1970's were not the best years for aeroflot throughout it's history.

## RECOMMENDATIONS
1. Effective communication should be established between flight crew and flight control there should be mutual agreement before actions are taken by flight crew.
2. Wars should be avoided as they lead to military flight crashes, aircraft been shot at.
3. Fuel should be untilized effectively and if there's a shortage due to aircraft exceeding total distance the fuel can go, before this happens aircraft should seek to land in any of the nearest airports for safety and then refuelling 
4. Weather conditions too should be thoroughly accessed before flight takeoff, if for cases where flight has already taken off and then there is a bad weather change later during flight, pilots should also quickly seek the nearest airport to land for safety and countinue later when the weather is favourable
5. Mechanical routine checks should be don before takeoff on flight to avoid engine failure or mechanical failures later during flight life
6. Flights should have some sort of mechanisms that repels wildlife so as to avoid collision with propellers(just like farms got scarecrows) 


