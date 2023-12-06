## Assignment 2

Due December 13th, 21:00, for max. 8 points

2 bonus points if completed in-class, December 6th, by 21:00

6 points max. for late submission, December 20th, by 21:00

Please e-mail your homework to daschapopowa@gmail.com in a .pdf or an .html format (please use R Markdown to create your file)


### Task 1 -- 3 points

**Please don't forget to provide code for every step!**

Take the data from a frequency dictionary [Ляшевская, Шаров 2011](https://raw.githubusercontent.com/agricolamz/DS_for_DH/master/data/freq_dict_2011.csv)

Use the data in the lemma column to compute how many times each character has occurred in the dictionary.

Then, recreate the plot below (don't forget the source of the data at the bottom of the plot):

![](https://github.com/dashapopova/Intro-to-R/blob/main/HWs/HW3/dictionary.png)

### Task 2 -- 3 points

**Please don't forget to provide code for every step!**

Take [here](https://raw.githubusercontent.com/agricolamz/DS_for_DH/master/data/us_city_average_temperature.csv) the data on 51 US cities, their population (the number of people),  the minimum and the maximum monthly temperature for each city in Fahrenheit. Turn Fahrenheit into Celsius and find the minimum temperature in the dataset (across all the cities and all the months).

Then, recreate the plot below:

![](https://github.com/dashapopova/Intro-to-R/blob/main/HWs/HW3/temperature.png)

### For a 9 or a 10 -- 2 points

Create a bar plot that shows the number of couples with different eye colors. The bars must be colored in the male's eye colors and the female's eye colors must be represented as colored patterns on these bars (as shown on the plot below). All colors must match the eye color they represent. Bars should be named according to the plot below. A hint: you can use geom_bar_pattern(stat = "identity") from the package "ggpattern".
