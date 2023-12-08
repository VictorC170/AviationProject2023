# AviationProject2023

Google Doc Word of README:
https://docs.google.com/document/d/1B0clVgCJK74DRRmkZi34d1s__3BE6ktnrgV2QIsi8LU/edit

Dashboard Tableau public:
https://public.tableau.com/authoring/AviationProject2023VCL/Dashboardwith3relevantcharts#2

Presentation Slides:
https://docs.google.com/presentation/d/1013lzbzZ1xjlo6kw0v5xjyhd3uewj_ZA0LqJ4zKuHIc/edit#slide=id.p

NTSB Aviation Data Set:
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses



AVIATION PROJECT
Flatiron School

BUSINESS “PROBLEM”

I am charged with determining which aircraft are the lowest risk for my company to start this new business endeavor. I must then translate my findings into actionable insights that the Head of the new Aviation Division can use to help decide which aircraft to purchase.

I have a data set with 88,889 accidents recorded.

I need to analyze the data and find the top safety aircrafts.

I need to work with CSV files containing data and after merging both CVS files these are my variables also known as columns.


Column 1: Event.Id
Column 2: Investigation.Type
Column 3: Accident.Number
Column 4: Event.Date
Column 5: Location
Column 6: Country
Column 7: Latitude
Column 8: Longitude
Column 9: Airport.Code
Column 10: Airport.Name
Column 11: Injury.Severity
Column 12: Aircraft.damage
Column 13: Aircraft.Category
Column 14: Registration.Number
Column 15: Make
Column 16: Model
Column 17: Amateur.Built
Column 18: Number.of.Engines
Column 19: Engine.Type
Column 20: FAR.Description
Column 21: Schedule
Column 22: Purpose.of.flight
Column 23: Air.carrier
Column 24: Total.Fatal.Injuries
Column 25: Total.Serious.Injuries
Column 26: Total.Minor.Injuries
Column 27: Total.Uninjured
Column 28: Weather.Condition
Column 29: Broad.phase.of.flight
Column 30: Report.Status
Column 31: Publication.Date
Column 32: State


I began my analysis by discarding airplanes made before 01/01/1997 because they were generally characterized as less safe.


Then I focused on the Makers and began to look at the rate of accidents per Maker and found that there are some Makers with many more incidents than others.


Then I filtered data to see if the problem was the Maker or just certain models within the Maker.

I later realized that there are certain less secure models within certain Makers, which negatively impacts a Maker.

After realizing if the problem was the models. I made an account of what type of engine the models use and if there are some models where some have more incidents due to the type of engine, then I started to filter the ratio of incidents, accidents and fatalities now by engine.

Then I realized that the problem was not only the model but also the type of engine.

The turboprop engine had the highest accident rate, the reciprocating tor being the lowest incident rate.

In terms of ratios and averages, Reciprocating is safer due to the number of accidents, but there is another one that is also safe, it is the Turbo fan engine, but this has fewer flights and therefore fewer accident ratios and therefore it is an engine. sure, but Reciprocating, because it has more accidents and fewer fatalities, is characterized as the safest model.

Reciprocating and Turbo fan are safer, but turbo fan have more sales options in the market, there are less Reciprocating for sale.

After that I started to see if the engine number column had any influence but it doesn't, it's just how many engines were intact or destroyed.

The average number of percentages was 1% in the same types of engine, therefore that was not a parameter to talk about safety, it was the type of engine and the fatalities per flight.

Having analyzed almost all my data: remove aircraft models where:

1. There were fatalities.
2. there were minimal or serious injuries.
3. aircraft was minimally, substantially damaged or destroyed,
4. Where there were incidents.
5. Accidents with a plane in staging or taxi position.

My column analysis of 88,889 rows was reduced to 420.

Counting on the TOP 260 safest aircraft in 2023.

Probably the top 10 does not have the reciprocating engine because remember that the Turbo Fan has more models out there, but both are safe.

Within those 260 models there are only 4 that are Helicopters.

Then you have options for a domestic plane or helicopter.

In the end I deleted 98% of rows where there were unsafe accidents.

My result was that out of 100% accidents, I have the options for the 2% safest flights in 2023 so that my CEO and my Head of the new aviation division can start undertaking that business!

I found on Google that Delta is the best airline in the country, and they started in 1925 under another name with only 18 airplanes, so if we want to continue the success of Delta, starting the new division with 18 to 100 airplanes sounds good, if we have 260 options to choose from, and they are safety!!

THE END


My 6 Recommendations before buying an airplane! :

Buy models within the range of my top 260.
Buy airplanes with a reciprocating or turbo fan engine.
Don't buy airplanes with a TurboProp engine.
Do not buy airplanes that have had reports of accidents with incidents, injuries or deaths.
Preferably buy airplanes manufactured after 01/01/1997.
Don't get carried away by the Maker name, what matters is the Model number.


THANK YOU !!!


Data Scientist: Victor Cornejo Leyva
Linkedin: https://www.linkedin.com/in/victorcornejoo/

Project presented on December 8 2023, 11 Broadway, New York, New york.



HOPE YOU ENJOY THE READING !!!

HMU on Linkedin for collaborations or Network
