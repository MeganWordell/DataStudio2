<b>Apartment Hunters: NYC Edition</b><br>
<br>Data Studio 2 project

For this Data Studio project, I wanted to see if there was anywhere in NYC that an individual person, who makes an average amount of money, could afford and not be “rent burdened.” This was a partly selfish endeavor, as my boyfriend and I are most likely moving to Brooklyn next month leaving our lovely roommate, dual income-less. To do this, my goal was to create a map of the city, or at least Manhattan for now, that displays the average rent of a one bedroom apartment, contrasted with the average monthly income of residents.

To do this I started with this Census Data that broke income per capita down by census tract. I used excel to clean it up a bit and then used pandas to merge it with neighborhood tabulation data from the city’s website. The data show the conversions between neighborhoods in Manhattan and Census tracts.

Next I used Street Easy’s data section to pull the median cost of a one bedroom for rent in 2021 and matched up neighborhoods with my cleaned Census/City data.

I next calculated the difference between median monthly income (times .3 to calculate a rent-burden free budget) and median monthly rent for each neighborhood. I found that for a single person making the average neighborhood income monthly, there were almost no neighborhoods with places that wouldn’t leave them rent burdened. However, when doubling this calculation — say, the average couple — I found that affordable options were scattered around the city. 

The data collection and cleaning for this took up the majority of my time. When matching, joining, and calculating things I knew I needed to use code and really saw my work last semester pay off — super proud of myself in that regard. 

I really wanted to create a calculator where readers would put in their income and it would show them where on the map they could live and not be rent-burdened, but I ran out of time. 
