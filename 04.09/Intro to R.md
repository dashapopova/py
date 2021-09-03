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
Can you find a place where the variable and its value gets recorded?

```
a <- b^b+b*b
a

log(b,a)

a == b

a = b
a

a <- 2
b <- 3

a==b

a!=b

a>b

a<b

a>=b

a<=b
```

### Data types

```
class(a)
```

+ **numeric**
+  **character**: strings, marked by '' or ""
```
s <- "Всем привет!"
s

class(s)
```
+ **logical**

```
t1 <- TRUE
f1 <- FALSE

t1

t2 <- T
f2 <- F

TRUE <- FALSE

TRUE

T <- FALSE
T

comparison <- a == b
comparison

t1

!t1

!!t1 #double negation

t1&t2 #and

t1&f1

t1 | f1 #or

f1 | f2

xor(t1, f1)
```

### Vector

atomic vector or atomic

```
c(4,8,15,16,23,42) #to create a vector

c("ho", "ho", "ho")

1:10 #to create a numeric vector

5:-3

seq(10,100, by = 10) #to create a sequence

seq(1,13, length.out = 4)

rep(1, 5) #to create a sequence with repetitions

rep(1:3, 3) #arguments can be vectors

rep(1:3, 1:3)

v1 <- c("Ho", "Ho-ho")
v2 <- c("Merry", "Christmas!")
c(v1,v2)
```
#### Coercion

```
c(FALSE, 2)

2 + TRUE

c(TRUE, 3, "Hi!")
```

Coercion hierarchy: NULL < raw < logical < integer < double < complex < character < list < expression

You can also change the type with a function:

```
as.numeric(c(TRUE, FALSE, FALSE))

as.character(as.numeric(c(TRUE, FALSE, FALSE)))

as.numeric(c("1", "2", "три"))
```

#### Operations with vectors

```
n <- 1:4
m <- 4:1
n + m

n - m

n * m

n / m

n ^ m + m * (n - m)

sqrt(1:10)
```

#### Recycling

```
n <- 1:4
m <- 1:2
n * m

n * 2

n + c(3,4,5)
```


