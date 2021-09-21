## Homework assignment 3

HW 2 is due 02.10 at 23:59

Please e-mail your homework to daschapopowa@gmail.com in a .pdf or an .html format (please use R Markdown to create your file)

### Task 1 -- 4 points

Take the data [about the UK pubs](https://raw.githubusercontent.com/dashapopova/Intro-to-R/main/HWs/HW2/UK_pubs.csv)

Plot the 40 or 50 most frequent names of pubs in the UK: the x-axis is for the number of symbols in the pub name, the y-axis is for the number of bars with the same name.

Your goal is to recreate the plot below (don't forget the names for the axes, the title and the source of the data at the bottom of the plot):

![](https://github.com/dashapopova/Intro-to-R/blob/main/HWs/HW2/pubs.png)

**A hint:**

+ use ```geom_point()``` and ```geom_text_repel()``` from the ```ggrepel``` package

### Task 2 -- 4 points

Take the data from [a questionnaire](https://raw.githubusercontent.com/dashapopova/Intro-to-R/main/HWs/HW2/mad_questionary.csv)

You can notice that the values for the sex variable are spelled inconsistently: *Ж/ж/женский/Женский* and *М/м/мужской/Мужской*. Manipulate the data so that *Ж/ж/женский/Женский* is turned into *женский* and *М/м/мужской/Мужской* is turned into *мужской*. Then plot the data.

Your goal is to recreate the plot below:

![](https://github.com/dashapopova/Intro-to-R/blob/main/HWs/HW2/questionnaire.png)

**A hint:**

+ use ```geom_dotplot()``` with the argument ```method = "histodot"``` and with a deleted axis ```scale_y_continuous(NULL, breaks = NULL)```

### For a 9 or a 10 -- 2 points

Create your own homework problem that targets the topic of functions. Provide a dataset, a problem formulation and a solution. Successful homework problems will be included in the next year's homework for students to solve.

Typically, a 9 and a 10 are reserved for students who show exceptional knowledge, skills and enthusiasm for the assignment, who make their assignment truly original and help other students by answering their questions in the chat.

