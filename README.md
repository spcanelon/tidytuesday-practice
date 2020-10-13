# TidyTuesday
Repo for #TidyTuesday R data visualization exercises

## Getting started

- [Intro Blog and history](https://themockup.blog/posts/2018-12-11-tidytuesday-a-weekly-social-data-project-in-r/)
- [Intro Tweet by Tom Mock (RStudio)](https://twitter.com/thomas_mock/status/1315774083225845764?s=20)
- [TidyTuesdays GitHub](https://github.com/rfordatascience/tidytuesday/blob/master/README.md)
- [TidyTuesday Podcast](https://twitter.com/tidypod)
- [TidyTuesday Sight-Unseen on YouTube](https://www.youtube.com/watch?v=ImpXawPNCfM)
- [{tidytuesdayR} package to help you easily download the dataset](https://github.com/thebioengineer/tidytuesdayR)

## tidytuesdayR example

```r
install.packages("tidytuesdayR")
remotes::install_github("thebioengineer/tidytuesdayR")
# OR devtools::install_github("thebioengineer/tidytuesdayR")
```

```r
library(tidytuesdayR)

# load the data
tt_data <- tt_load("2020-10-13")
tt_data <- tt_load(2020, week=42)

# take a peek
readme(tt_data)
print(tt_data)
```
