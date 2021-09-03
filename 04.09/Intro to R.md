# Introduction to R

### Installing R

+ <a href="https://cran.r-project.org/bin/windows/base/">Windows</a>
+ <a href="https://cran.r-project.org/bin/macosx/">Mac</a>
+ <a href="https://cran.rstudio.com/bin/linux/">Linux</a>

+ Then, install IDE for R: <a href="https://www.rstudio.com/products/rstudio/download/">RStudio</a>

+ If you don't want to download RStudio on your computer: <a href="https://rstudio.cloud/">RStudio cloud</a> 

### Useful resources

+ <a href="https://r4ds.had.co.nz/">a book <span class="citation">(Wickham and Grolemund <a href="#ref-wickham16" role="doc-biblioref">2016</a>)</span></a> 
+ <a href="https://stackoverflow.com">stackoverflow</a>
+ <a href="https://community.rstudio.com/">RStudio community</a>
+ <a href="https://ru.stackoverflow.com">Russian stackoverflow</a>
+ <a href="https://www.r-bloggers.com/">R-bloggers</a>
+ <a href="https://t.me/rlang_ru">a chat about R</a>, where you can ask questions about R in Russian (but read <a href="https://github.com/r-lang-group-ru/group-rules/blob/master/README.md">the policy</a> first)

### RStudio

When you open RStudio, you will see four spaces: **Code Editor** (to write scripts), **R Console** (interactive: you type a command and see the result), **Workspace and History** (here you can see what variables you have introduced), **Plots and files** (here you will see the plots when we draw some)

### R as a calculator

Use R Console to compute:

```
6 + 13

7-10

2*6

100/5

2^3

(3+5)*2
```
### Functions

What about taking a square root? or a log?

To do so, we can use functions.

```
sqrt(16)

log(8)
```

To learn about a function, we can open help:

```
?log
```
Let's now try:

```
log(x = 8, base = 2)

log(8,2)

log(8, sqrt(4))

log(base = 2, x = 8)

log(b = 2, x = 8)

'+'(3,4)
```

### Variables

To store values we use variables:

```
b <- 2 (Alt - or option - on Mac)

b = 2
```
