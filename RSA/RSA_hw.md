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

2) what would happen to the implicature if the priors are P(r1) = 0.1, P(r2) = P(r3) = 0.45? Provide the corresponding table for the pragmatic listener and comment upon it. Use can use the [prompt](https://github.com/dashapopova/CompSemantics/blob/main/HWs/hw5_prompt.ipynb) or compute manually.

