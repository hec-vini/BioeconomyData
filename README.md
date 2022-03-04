# My Data Repo
## Introduction 
Hi! welcome to my dataset. 
I have been working on this project in order to share some clean general (and diverse) datasets that I've been using on dat-to-day work. Numbers cover topics on the Environment, the Economy, Government, Demographics and so on. Tried my best to comment every line and share cool packages. Mostly done in R. 

Tips and comments are totally welcome!
For some dataviz-related work, follow me on Twitter: [@hec_vini](https://twitter.com/hec_vini).

## Import Packages
```
library(tidyverse) 
library(lubridate) #To work with dates
library(janitor) #To easily manage date, especially Excel dates and clean_names() function. 
library(data.table) #Mainy to use fread() funtion
library(openxlsx) #Work with .xlsx files
library(countrycode) #convert contry names to ISO 3166-1 alfa-3 codes
library(ipeadatar) #IPEA (Brazilian Center for Economics Studies) API package
library(zoo) #
library(tidylog) #Feedback on dplyr operations
library(WDI) #World Bank API package
library(httr) #Mostly to download web data
library(geobr) #Brazilian Geographic data
library(textclean) #Useful to clean strings, mostly to trim white spaces
library(ggh4x) #Hacks for ggplot2
library(anytime) #clean time date string
```


## Default Patterns
Some datasets ae used all over the project. Here they are. 

* 
