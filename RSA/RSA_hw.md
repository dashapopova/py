## RSA Homework

**Due February 6th, by 9am**

A reference game:

three objects (r1, r2, r3)

|        | r1         | r2  | r3 |
| ------------- |-------------| -----|------|
| 'hat'    | 1 | 1 | 0 |
| 'glasses'     | 0     |   0 | 1|
| 'mustache' | 0      |    1 | 0|

Prior probabilities (P(r), prior)

|        | P(r)|
| ------------- |-------------|
| r1    | 1/3 | 
| r2     | 1/3     |  
| r3 | 1/3      |   

Utterance cost (C(u), cost)

|        | C(u)|
| ------------- |-------------|
| 'hat'   | 0 | 
| 'glasses'     | 0     |  
| 'mustache' | 0      |   

If alpha = 1, then the probability distribution for the pragmatic listener is the following:

|        | r1         | r2  | r3 |
| ------------- |-------------| -----|------|
| 'hat'    | 0.75 | 0.25 | 0 |
| 'glasses'     | 0     |   0 | 1|
| 'mustache' | 0      |    1 | 0|

**For 6 points:**

1) describe the implicature that one can draw from the table of the pragmatic listener

2) what would happen to the implicature if the priors are P(r1) = 0.1, P(r2) = P(r3) = 0.45? Provide the corresponding table for the pragmatic listener and comment upon it. Use can use the [prompt]([https://github.com/dashapopova/CompSemantics/blob/main/HWs/hw5_prompt.ipynb](https://github.com/dashapopova/Intro-to-R/blob/main/RSA/RSA_prompt_TheorLing_2023.ipynb)) or compute manually.

**Plus 2 points:**

1) provide a reference game with two scalar implicatures, apply the RSA analysis for it (provide the tables for literal listener, speaker and pragmatic listener)

2) comment upon the role of parameters (alpha, prior probablitties, cost), try to draw some conclusions about the values of the parameters that result in the computation of an imlicatures and those that don't, about the interplay of the parameters

3) comment upon the differences between the game with one scalar implicature (e.g., the one we discussed in class, or the one above) and your game with two scalar implicatures

**Plus 2 points:**

Sketch an application of the RSA framework to a linguistic problem that we haven't covered in class. State at least the following: 1) the linguistic problem 2) why do you think that RSA is a good framework to use to model that problem 3) what modifications, if any, of the formulas are needed 4) what parameters you propose to consider and why

