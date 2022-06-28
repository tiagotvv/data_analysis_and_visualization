# Data Analysis and Visualization

In this repository I aggregate all the data analysis and visualizations that I published in the internet. 

I included my participations in Storytelling with Data Challenge #SWDchallenge and the Makeover Monday #makeovermonday 

These analysis uses several data sources, including politics, economics and healthcare data.   

### 1. Gasoline price formation in Portugal

I created waterfall chart showing the price breakdown of one liter of gasoline in Portugal. The chart also highlights the taxes paid by the customers at the pump. 

![Gas](gasprice_portugal.jpg?raw=true "Gas price components")

Tableau link: https://public.tableau.com/app/profile/tiago.vinhoza/viz/GasolinePriceinPortugal/PriceBreakdown

### 2. Misery Index in Portugal (1985-2017)

I created a connected scatterplot using unemployment and inflation data from Portugal. The farther a point is from the origin, the larger is the misery index (sum of the unemployment and inflation rates). We can see that after the 2009-2011 crisis, the misery index was the same as in the early 90s, but high unemployment was the problem, not high inflation.

### 3. 2016 US presidential election exit poll breakdown 

I used a dot plot to break down the 2016 US presidential election exit polls results according to categories such as gender, age, income and party registration.

![US2016](US_2016exitpoll.png?raw=true "2016 US presidential election exit poll")

### 4. 2018 Brazilian presidential elections

#### 4.1 Runoff scenario simulator

This runoff simulator that I prepared in tableau starts with the results from the first round in Brazil and simulates the vote transfer between from the defeated candidates to Jair Bolsonaro and Fernando Haddad. Some features and assumptions:
* A fixed percentage of the defeated candidates voters will abstain or cast blank votes. 
* A small percentage of voters that abstained in the first round will cast a vote in the second round.
* Three turnout models for the runoff.

<img src="brazil_runoff_simulator.png" alt="runoff" width="600"/>


#### 4.2 State-by-state results

I used a dot plot to compare the 2018 and 2014 elections results. To get a left-right partisan effect, I picked the x-axis to represent the % of valid votes for the Worker's Party (PT) and reversed it. After that I colored the background of the graphic in red for x>50% and blue for x<50%.

The blue dot represents the 2014 election result and the black dot the 2018 election result. 

Some insights that can be taken from the visualization:
* There was a hard swing to the right
* Bolsonaro flipped 4 states that went for Dilma Roussef in 2014: AM (Amazonas), AP (Amapá), MG (Minas Gerais) and RJ (Rio de Janeiro).
* PT improved their 2014 vote share in 3 states.
* 9 states had swings >10 pts to Bolsonaro.

<img src="brazil_2018result.png" alt="drawing" width="800"/>


### 5. 2019 United Kingdom general election

A visualization where each of the 650 constituencies in place for the 2019 general election are described in terms of their competitiveness and their Brexit status

The seat competitiveness was defined in terms of the 2017 election majority:
* competitive: majority less than 5%
* leaning to incumbent: majority between 5% and 10%
* fairly safe: majority between 10% and 20%
* safe: majority greater than 20%.

In terms of the 2016 referendum results, Brexit status was defined as:
* weak remain/leave: share between 50%-55% 
* moderate remain/leave: share between 55%-60%
* strong remain/leave: share greater than 60%

The visualization has two tabs, one showing the status at dissolution and the other showing the post-electoral results. The party information is encoded in the colors. In the post-election tab we used the shape to inform which constituencies changed parties (square - seat flipped, circle - incumbent held seat), there is also a filter that the user can see specifically the open seats (i.e. the incumbent MP not running). 

<img src="2019UK_pre_election.png" alt="drawing"/>

<img src="2019UK_post_election.png" alt="drawing"/>

Tableau link: https://public.tableau.com/app/profile/tiago.vinhoza/viz/2019UKElectionResults/Post-Election


### 6. COVID-19 pandemic data analysis

#### 6.1 Portugal

Hospitalized patients (total and ICU) versus number of active cases in Portugal.

<img src="hosp_active.jpg" alt="drawing" width="800"/>
<img src="hospICU_active.jpg" alt="drawing" width="800"/>


Data collected from: Data Science for Social Good Portugal: https://github.com/dssg-pt/covid19pt-data

Link to animation (from March 16, 2020 to Dec 30, 2021): https://twitter.com/tiagotvv/status/1476622702932865030
