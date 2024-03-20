## RSA Homework

**Due March 18th, by 23:59** Please e-mail me your homework solution

A reference game:

three objects (r1, r2, r3)

|            | r1  | r2  | r3  |
|------------|-----|-----|-----|
| 'hat'      | 1   | 1   | 0   |
| 'glasses'  | 0   | 0   | 1   |
| 'mustache' | 0   | 1   | 0   |

Prior probabilities (P(r), prior)

|     | P(r) |
|-----|------|
| r1  | 1/3  |
| r2  | 1/3  |
| r3  | 1/3  |

Utterance cost (C(u), cost)

|            | C(u) |
|------------|------|
| 'hat'      | 0    |
| 'glasses'  | 0    |
| 'mustache' | 0    |

If alpha = 1, then the probability distribution for the pragmatic listener is the following:

|            | r1   | r2   | r3  |
|------------|------|------|-----|
| 'hat'      | 0.75 | 0.25 | 0   |
| 'glasses'  | 0    | 0    | 1   |
| 'mustache' | 0    | 1    | 0   |

**For 6 points:**

1)  what conclusions can one draw from the table of the pragmatic listener? Provide an argument for your view

*If given a prompt "hat", a pragmatic listener is likely to pick r1. They would think that if the speaker wanted to choose r2, they would say "mustache". If given a prompt "mustache" or "glasses", a pragmatic listener will always choose r3 or r2, respectively.*

2)  what would happen if the priors are P(r1) = 0.1, P(r2) = P(r3) = 0.45? Provide the corresponding table for the pragmatic listener and comment upon it. You can use the [prompt](https://github.com/dashapopova/py/blob/main/RSA/RSA_prompt_TheorLing_2024.ipynb) or compute manually.

|            | r1   | r2   | r3  |
|------------|------|------|-----|
| 'hat'      | 0.33 | 0.67 | 0   |
| 'glasses'  | 0    | 0    | 1   |
| 'mustache' | 0    | 1    | 0   |

*In this case, a pragmatic listener would more likely choose r2 given the prompt "hat" since the a priori probability to choose r2 is significantly higher than for r1.*

**Plus 2 points:**

1)  provide a reference game with two scalar implicatures, apply the RSA analysis to it (provide the tables for literal listener, speaker and pragmatic listener)

*The game is as follows. There are three linguists: Varya, Dasha and Yura. They work in different fields of linguistics: Varya works with phonetics, lexicon and grammar, Dasha studies lexicon, and Yura does research on phonetics and lexicon.*

|             | Varya | Dasha | Yura |
|-------------|-------|-------|------|
| 'phonetics' | 1     | 0     | 1    |
| 'grammar'   | 1     | 0     | 0    |
| 'lexicon'   | 1     | 1     | 1    |

*The first implicature: grammar \> phonetics. The second implicature: phonetics \> lexicon.*

*Let us suggest that the priors are 0.25 (Varya), 0.4 (Dasha) and 0.3 (Yura).*

|       | P(r) |
|-------|------|
| Varya | 0.25 |
| Dasha | 0.4  |
| Yura  | 0.3  |

*Literal listener:*

|             | Varya | Dasha | Yura |
|-------------|-------|-------|------|
| 'phonetics' | 0.45  | 0     | 0.54 |
| 'grammar'   | 1     | 0     | 0    |
| 'lexicon'   | 0.26  | 0.42  | 0.31 |

*Pragmatic speaker:*

|         | phonetics | grammar | lexicon |
|---------|-----------|---------|---------|
| 'Varya' | 0.26      | 0.58    | 0.15    |
| 'Dasha' | 0         | 0       | 1       |
| 'Yura'  | 0.63      | 0       | 0.37    |

*Pragmatic listener:*

|             | Varya | Dasha | Yura |
|-------------|-------|-------|------|
| 'phonetics' | 0.26  | 0     | 0.74 |
| 'grammar'   | 1     | 0     | 0    |
| 'lexicon'   | 0.07  | 0.73  | 0.2  |

*If one of the three is called "phonetician", it is most likely Yura. If one of them is called a "lexicologist", it is most likely Dasha. A "grammarian" would undubitably be Varya.*

2)  comment upon the role of parameters (alpha, prior probabilities, cost), try to draw some general conclusions about the values of the parameters that result in the computation of implicatures and those that don't, about the interplay of the parameters

*If alpha is increased, the speaker is more likely to choose the "right" option (the most likely options become even more likely).*

*Increasing the prior probability for one of the objects makes it so that a pragmatic speaker is more likely to choose it. The probability does not change if it is 0 or 1.*

*Increasing the costs for a feature makes probabilities to choose a certain object more even.*

3)  comment upon the differences between the game with one scalar implicature (e.g., the one we discussed in class, or the one above) and your game with two scalar implicatures, e.g. is the role of the parameters different, does the modeling reflect your linguistic intuition etc.

*Unfortunately no idea :(*
