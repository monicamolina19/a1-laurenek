CEE 224X | Released: 180925 | Due: 181002
Name:

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

Q1 Response Here (<100 words)
Combined fields mean that if there are less than 100 residential customers or less than 15 non-residential customers, their consumption data will be combined with a neighboring zip code. This might affect our analyses by either over- or under-estimating gas and elctricity consumption by certain zip codes.


#### Q2: Why are the “Average” fields likely not useful for our analyses?

Q2 Response Here (<100 words)
The average fields are likely not useful because we are combining both gas and electric usage data and will need to create a new field that reflects the monthly average for both power sources.


#### Q3: What type of calculations should "X" and "Y" be in the step above? Why?

Q3 Response Here (<100 words)



#### Q4: What is the total KBTU combined electricity and gas consumption in PG&E territory in 2017? What is the average annual electricity consumption per customer, and average annual gas consumption per customer?

Q4 Response Here (<100 words)
-Combined total KBTU of electricity and gas consuption: 2.892 x 10^11 KBTU
-Average annual electricity consumtion per customer: 1.06185 x 10^11 / 57773738 = 1837.85 KBTU
-Average annual gas consumption / customer: 1.8301 x 10^11 / 52940106 = 3457.03 KBTU


#### Q5: How would you explain the results of this chart to an average property owner in Northern California? What would be the value of conducting further "seasonal" analyses of energy use, compared to "year-long" analyses, and how would you define seasonal boundaries?

Q5 Response Here (<250 words)
Gas consumption in Northern California is the highest in winter months (November through March). Electricity consumption is more stable throughout the year with slightly higher peaks in the hotter months of July through September. Conducting futher seasonal analyses could be valuable to identify the onset of increased gas use and electricity use in the winter and summer months, respectively, and when PG&E can anticipate the highest demands for energy load. Seasonal boundaries could potentially be cased off recorded temperatures from the previous year.


#### Q6: Explain your choice of formula for "avgkbtu".

Q6 Response Here (<100 words)
Avg KBTU = (Total electricity ktbu + Total gas ktbu) / (max (sum (electricity customers), sum (gas customers) / 12)
Instead of doing a straight division of total KTBU by the sum of total customers, we instead divide the total KTBU by the maximum number of either electricity or gas customers (to avoid double counting customers who use both gas and electricity from PG&E) divided by 12 (for the monthly average).


#### Q7 Paste a publicly viewable link to your Slides.

Q7 Response Here
https://docs.google.com/presentation/d/17MU1DP4KTyqpCMlqvjSO0RN599pOhpz0Fxso4xDnTNo/edit?usp=sharing


#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

Q8 Response Here (<100 words)
The results in my chosen zipcode validate my expectations on average KTBU use (on the high end because of the campus demands for energy. However, the total KTBU for Stanford was a little contradictory to my expectations, as I would expect the university to use a lot more energy than neighboring areas.


#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

Q9 Response Here (<250 words)
The Pivot table was the most challenging part of Pass One, but the ArcMap steps were less demanding. I would expand the analysis to include data on socioeconomic factors such as income, race, and household size.


#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

Q10 Response Here (<250 words)
Pass One was useful to go through. Pass Two was very difficult for me to understand what I was doing in R. I would rate the difficulty of this assignment as 10/10. 


#### Q11 In total, how long did Assignment 1 take?
This Assignment probably took around 12 hours or more. It took a LOT of time to download all of the software. ArcMap also kept crashing, requiring me to go into the lab to complete the mapping components. Also, it took a long time (~3 hours) for me to understand the link I was fixing in RStudio.

Part 1: Tech Setup: _ minutes

Part 2: Pre-Assessment: _ minutes

Part 3: Readings: _ minutes

Part 4: Practice Data Dive: Pass 1: _ minutes

Part 4: Practice Data Dive: Pass 2: _ minutes
