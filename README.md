
<h1 align="center">Data Analysis of the USA and its allies invasion of Iraq</h1>
<h2 align="center">Rewriting the history of the invasion of iraq using data</h2>
<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/mosul.jpg" width ="400" height = "200">
</p>
The idea of analysing this historical event has growing in my mind after watching  former President George W. Bush accidentally switched "Ukraine" with "Iraq" in a line meant to criticize Vladimir Putin's "wholly unjustified and brutal invasion.", in a  <a href="https://www.youtube.com/watch?v=lrnaqpkBmOA&ab_channel=GuardianNews">speech</a> at his presidential center in Texas.

>__Warning__
> Before your trip inside details, Please note that I am not a specialist in geopolitics and armed conflicts. I am only a data nerd with a passion for current events in international Politics and the History of the globe. 

 # $\textcolor{brown}{\text{I. Analysing President George W. Bush speech declaring War against Iraq using (Audio Data)}}$

In this part of my work 

>__Warning__
> This is a warning.

<h2> $\textcolor{brown}{\text{II. Analysis Iraq deaths and wounded in USA invasion between 2004 and 2009}}$ </h2>


> __Note__
> About dataset.

this data is published in <a href="https://www.theguardian.com/news/datablog/2010/oct/23/wikileaks-iraq-data-journalism">The Guardian Datablog</a>. this data is originaly leaked by <a href="https://wikileaks.org/">Wikileaks</a> giving journalists and NGO 391 000 records of the Iraq War. Every minor detail is now in front of us to analyse and breakdown. I am particularly interested in the civilian dead and wounded of this war. 

<h3> $\textcolor{BurntOrange}{\text{II.1 Adding some context to every column}}$ </h3>

Column names |  My explanation after the preliminary analysis |
--- | --- |
Report Key | An Id given to the event reported |
Type   | Type of Event (Most reported events are Criminal Event) | 
Category  | Categorization of event recorded made by coalition army to help them give a title to the event  | 
Title   | A description of the event | 
Region   | Region in this dataset does not refer just to a geographic localization but to an army division  | 
Attack on   | Clustering the event to neutral, friend or enemy fire  | 
Civilian wia   | Number of civilians wounded in action  | 
Civilian kia  | Number of civilians killed in action  | 


<h3> $\textcolor{BurntOrange}{\text{II.2 Some major facts and figures}}$ </h3>

The first very disturbing observation is that 60% of the deaths in the recorded cases are civilians. In armed conflicts, the civilian - combatant ratio ( the ratio of civilian casualties to combatant casualties) is a measurment that can be applied to describe the casualties in war. I calculated it and compare it with <a href="https://wikileaks.org/"> others conflicts in the in the last century</a>


War |  The civilian to combatant fatality rate |
--- | --- |
World War II | between 3:2 and 2:1 |
Korean War   | 2:1  | 
Vietnam War  | 2:1  | 
$\textcolor{Red}{\text{Our data}}$   | $\textcolor{Red}{\text{3:2}}$ | 

this ratio should be calculated with the total dead recorded by independent organizations but it clearly demonstrates the tremendous brutality of this war, The death of two combatants in this conflict provokes the death of three civilians.

<h3> $\textcolor{BurntOrange}{\text{II.3 Analysis of the number of deaths and injuries by categories}}$ </h3>

> __Note__
> About our results.

In order to reduce the number of categories in my data, I choose to rename all incendent categories that have less that 2000 wounded persons in total to 'Other'. It will help me to do better visualisations. 


<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/wounded.PNG">
</p>

<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/pourcentagewounded.PNG">
</p>
In the 2003–2011 Iraq War, Improvised explosive devices have been used extensively against Coalition forces and by the end of 2007 they have been responsible for at least 64% of Coalition deaths in Iraq and unfortunately it wounded civilians for the simple reason, it do not directly target the enemy.


<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/table_killes.PNG">
</p>

<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/pourcentagedeath.PNG">
</p>

>__interpretation__
> More than 7.2 % of civilians in those records are dead by direct fire. If this term means that coalision forces was directly targeting civilians, then it is a very significant number and it is necessary to start legal actions against those responsible. 

> 45 % of civilians deaths are caused by military actions (Attack - Direct Fire - Escalation of Force - Indirect Fire)

<h3> $\textcolor{BurntOrange}{\text{II.4 Analysis of the number of deaths and injuries by Coalition Division}}$ </h3>

Coalition Forces or Multi-National Force – Iraq was a military command during the 2003 invasion of Iraq and much of the ensuing Iraq War, led by the United States of America (Operation Iraqi Freedom), United Kingdom (Operation Telic), Australia, Italy (Operation Ancient Babylon), Spain and Poland, responsible for conducting and handling military operations. the geographic presence of those divisions is shown in the map below


<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/Iraq_2003_occupation.png" width ="400" height = "350">
</p>


<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/deadbydivision.PNG">
</p>

<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/pourcentagekilldivision.PNG">
</p>

>__interpretation__
> The number in civilian death is more frequent in division MND-baghdad, MND-C and MND-N. those divisions are formed with US Army under US generals. 


<h3> $\textcolor{BurntOrange}{\text{II.5 Analysis of the number of deaths and injuries by time}}$ </h3>

<p align="center">
<img src ="https://github.com/BentarHamza/IraqWar/blob/main/photos/killedbytime.PNG">
</p>

>__interpretation__
> Everyday, one civilian was killed by direct fire from the Multi-National Division North leaded by Major General Robert L. Caslen Jr in in 6 years of invasion (the period between the first report and the last report in this dataset). 

> 2006 was the begining of The Iraqi civil war was a civil war <a href="https://en.wikipedia.org/wiki/Iraqi_civil_war_(2006%E2%80%932008)">civil war </a> fought mainly between the Iraqi government along with American-led coalition forces and various sectarian armed groups. It was unbelievably brutal and that's can be observed in our analysis

> More that one civilian was killed every hour for 6 years of invasion (the period between the first report and the last report in this dataset

> 2 Civilians are killed by direct firing from coalition army everyday day in 6 years (the period between the first report and the last report in this dataset). that's represents the third cause of civilian death in those reported incidents.

<h3> $\textcolor{BurntOrange}{\text{II.5 Analysis of the number of deaths and injuries by geolocalisation }}$ </h3>

>__interpretation__
> After grouping the number of dead civilians by geolocation of reports in our dataset we clearly observe a concentration of deaths in the north and center of the country. 



