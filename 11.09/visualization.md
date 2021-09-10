## Visualization

```library("tidyverse")```

[ggplot2 condensed](https://raw.githubusercontent.com/rstudio/cheatsheets/master/data-visualization-2.1.pdf)

### Scatter plot

```
ggplot(data = diamonds, aes(carat, price)) +
  geom_point()
  
ggplot(data = diamonds, aes(carat, price, color = cut))+
  geom_point()
  
ggplot(data = diamonds, aes(carat, price))+
  geom_point(color = "green")
  
ggplot(data = diamonds, aes(carat, price))+
  geom_point(aes(color = cut))
```

dplyr, ggplot2

```
diamonds %>%
  ggplot(aes(carat, price, shape = cut))+
  geom_point()
  
diamonds %>%
  ggplot(aes(carat, price, label = color))+
  geom_text()
  
diamonds %>%
  slice(1:100) %>% 
  ggplot(aes(carat, price, label = color))+
  geom_label()
  
diamonds %>%
  ggplot(aes(carat, price, color = cut))+
  geom_point() + 
  labs(x = "вес (в каратах)",
       y = "цена (в долларах)",
       title = "Связь цены и веса бриллиантов",
       subtitle = "Данные взяты из датасеты diamonds",
       caption = "график сделан при помощи пакета ggplot2")+
  theme(legend.position = "bottom") # у функции theme() огромный функционал
  
diamonds %>%
  ggplot(aes(carat, price, color = cut))+
  geom_point()+
  annotate(geom = "rect", xmin = 4.8, xmax = 5.2,
           ymin = 17500, ymax = 18500, fill = "red", alpha = 0.2) + 
  annotate(geom = "text", x = 4.7, y = 16600,
           label = "help...\n I am in a red\nsquare")
```

