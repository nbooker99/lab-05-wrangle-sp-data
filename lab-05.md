Lab 05 - La Quinta is Spanish for next to Denny’s, Pt. 2
================
Noah Booker
3/26/25

### Load packages and data

``` r
library(tidyverse) 
#library(dsbox) 
```

``` r
states <- read_csv("data/states.csv")
```

### Exercise 1

Filter the Denny’s data frame for Alaska (AK) and save the result as
dn_ak. How many Denny’s locations are there in Alaska?

``` r
load("~/Documents/Documents/Studies/School/WFU/DS4P/Lab_5/data/dennys.rda")
load("~/Documents/Documents/Studies/School/WFU/DS4P/Lab_5/data/laquinta.rda")
dn <- dennys
lq <- laquinta
dn_ak <- dn %>%
  filter(state == "AK")
nrow(dn_ak)
```

    ## [1] 3

There are three Denny’s locations in Alaska.

Now, do the same for La Quinta data frame for Alaska (AK) and save the
result as lq_ak. How many La Quinta locations are there in Alaska?

``` r
lq_ak <- lq %>% 
  filter(state == "AK")
nrow(lq_ak)
```

    ## [1] 2

There are two La Quinta locations in Alaska.

### Exercise 2

Remove this text, and add your answer for Exercise 1 here. Add code
chunks as needed. Don’t forget to label your code chunk. Do not use
spaces in code chunk labels.

### Exercise 3

…

### Exercise 4

…

### Exercise 5

…

### Exercise 6

…

Add exercise headings as needed.
