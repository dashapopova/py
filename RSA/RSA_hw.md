## RSA Homework

**Due February 5th, by 23:59** Please e-mail me your homework solution

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

**TASK 1 -- Up to 6 points:**

1) what conclusions can one draw from the table of the pragmatic listener? Provide an argument for your view

2) what would happen if the priors are P(r1) = 0.1, P(r2) = P(r3) = 0.45? Provide the corresponding table for the pragmatic listener and comment upon it. Use can use the [prompt](https://github.com/dashapopova/py/blob/main/RSA/RSA_prompt_TheorLing_2024.ipynb) or compute manually.

**TASK 2 -- Up to 2 points -- please choose ONE of the options:**

**Option 1**

1) provide a reference game with two scalar implicatures, apply the RSA analysis to it (provide the tables for literal listener, speaker and pragmatic listener)

2) comment upon the role of parameters (alpha, prior probabilities, cost), try to draw some general conclusions about the values of the parameters that result in the computation of implicatures and those that don't, about the interplay of the parameters

3) comment upon the differences between the game with one scalar implicature (e.g., the one we discussed in class, or the one above) and your game with two scalar implicatures, e.g. is the role of the parameters different, does the modeling reflect your linguistic intuition etc.

**Option 2**

Poirot: Do you have children, madam?

M. Battersby: I've never been married, Monsieur Poirot.

Poirot: Pardon... Mademoiselle...


Poirot Agatha Christie Season 11 Episode 3 Third Girl

Can you detect an implicature in the dialog above? If no, justify your view. If yes, provide the implicature, its computation based on the maxims. In your view, has M. Battersby lied to Poirot if she does have a daughter? Justify your answer. In your view, did she mislead Poirot with her answer (it does not matter whether Poirot believed her or not)? Justify your answer.

**TASK 3 -- Up to 2 points:**

Propose an application of the RSA framework to a linguistic problem that we haven't covered in class (does not have to be a pragmatic problem, could be a syntactic, morphological, semantic, phonetic problem). The proposal should be around 2 pages long. Make sure to address the following questions: 1) what is the linguistic problem that you propose to model 2) why do you think that RSA is a good framework to use to model that problem 3) what modifications, if any, of the formulas are needed, and why 4) what parameters you propose to consider and why. 
