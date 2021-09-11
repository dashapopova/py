## tidyverse

https://www.tidyverse.org/


   + ```ggplot2``` for visualization
   + ```tibble``` to work with tibbles, modern dataframes 
   + ```tidyr``` for the tidy data format
   + ```readr``` to read files
   + ```dplyr``` for data manipulation
   + ```stringr``` to work with string variables
   + ```forcats``` to work with factor variables

   + ```readxl``` to read .xls and .xlsx
   + ```jsonlite``` to work with JSON
   + ```tidytext``` to work with texts and corpora
 etc.
 
 ```
 library("tidyverse")
 ```
 
 To determine your workdirectory: ```getwd()``` and ```setwd(.../path/to/your/directory)```
 
 ```
 read_csv("...")
 
 read_csv("/home/user_name/work/data/my_file.csv")
 ```
 
 + ```read_tsv()``` – for files with tab separators
 + ```read_csv2()``` – for files with ; separator
 + ```read_delim(file = "...", delim = "...")``` – for files with a separator in the delim argument

 If there are no names for the columns, include ```col_names = FALSE```
 
 If you have problems with encoding, try to include this: ```locale(encoding = "UTF-8")```
 
 To read .xls (```read_xls```) and .xlsx (```read_xlsx```):
 
 ```
library("readxl")
xlsx_example <- read_xlsx("...")
 ```

