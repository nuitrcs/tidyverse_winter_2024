# Winter 2024 Tidyverse Workshop Series

These materials support a series of hour long interactive, virtual workshops on using packages that are part of the [tidyverse](https://www.tidyverse.org/).

## Before the Workshop

### Set up R and RStudio

[Install R and RStudio](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/) on your own laptop (both are free).  If you can't install these programs or run into issues installing packages, [RStudio Cloud](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/#option-2-rstudio-cloud)  is a good option.

Also, install (or update) the tidyverse package.  Instructions are at the bottom of the [installation instructions page](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/).  If you run into installation issues (about 5-10% of you are likely to based on past workshops), people affiliated with Northwestern can submit a [consult request](https://app.smartsheet.com/b/form/2f2ec327e6164f83b588b7bbe2e2b56f). Please mention that you're taking this workshop and are having installation issues.

These workshops will be using tidyverse version 2.0 and R version 4.3.2 or later. You might be able to run the code with previous versions, but if you're having troubles you may want to update tidyverse and R. To update R, you can go through the [installation instructions](https://sites.northwestern.edu/researchcomputing/resources/r-and-rstudio/) again. To update tidyverse, make sure you are starting from a fresh R session (no packages loaded), and then install it again:  `install.packages("tidyverse")`.

## Materials

### Background

These workshops assume you are familiar with R outside of these packages.  Sessions build on each other to some extent.  Sessions after the first one assume you understand the material covered in the first session.  Later sessions may also use additional concepts from earlier sessions.

You may also want to learn about R Markdown files (and R Notebooks, which are a special type): https://rmarkdown.rstudio.com.  They're useful for when you want to combine R code, output, and text together in a document. The files for these workshops are R Markdown documents, which will be run in Notebook mode so the output appears below the code cells in the file. 

### Links

Links for each session will show the rendered html file.  There is a button in the upper right corner of each file to download the .Rmd file to work with in RStudio yourself.

The winter 2024 workshop series will include the following six parts:

* [Session 1](https://nuitrcs.github.io/tidyverse_basics/intro.html): Tidyverse basics
  * Recording [here](https://northwestern.zoom.us/rec/share/XekpJ3gTIeAlBtiqI4pLU3Yt_-RzGp84717_K2LkAl5dQbQoP9TJhUx1Uf2dgaVe.RO8uGFSTdq2uNuxv?startTime=1704736440000)
* [Session 2](https://nuitrcs.github.io/tidyverse_dplyr_select_filter_mutate/dplyr_select_filter_mutate.html#): dplyr – select, filter, mutate
  * Recording [here](https://northwestern.zoom.us/rec/share/xlVE5_hPNDicRALA_4Z-GT4zsaaVjjmMt71BYlBrU_mTpZ00T00ZQymMM5RvJVMA.NIK95lzXHIm2WjGm)
* [Session 3](https://nuitrcs.github.io/tidyverse_dplyr_groupby_summarise_arrange_across/dplyr-group.html): dplyr – group by, summarize, arrange, across    
* Session 4 (URL pending): dplyr – joins - working with two data frames
* Session 5 (URL pending): tidyr – pivot_longer, pivot_wider, separate, separate_rows
* Session 6 (URL pending): a quick intro to ggplot2

These are some additional sessions taught in the past that you can take a look at (please note that the code might not be updated):

* [Bonus](https://nuitrcs.github.io/r-tidyverse/html/others.html): utility packages – stringr, lubridate, forcats, readxl: this is an overview lecture without exercises
* [Regular Expressions with stringr](https://nuitrcs.github.io/r-tidyverse/html/stringr.html): requires knowledge of regular expressions
* [dplyr with databases](https://github.com/nuitrcs/databases_workshop/tree/master/r): our database workshop materials include an example of using dplyr directly with a database connection instead of writing SQL queries

## Learning More

[R for Data Science (2nd edition)](https://r4ds.hadley.nz/) covers the use of tidyverse packages for data analysis in depth.  Written by two of the authors of these packages, this free online book is a good place to go for additional information and practice.  

[RStudio Videos](https://www.youtube.com/watch?v=jOd65mR1zfw&list=PL9HYL-VRX0oQOWAFoKHFQAsWAI3ImbNPk): Data Wrangingling with R and the Tidyverse.  These cover material from roughly the first 4 sessions of this workshop series.  

For more on ggplot2, see [our guide](https://sites.northwestern.edu/researchcomputing/2020/04/13/online-learning-resources-r-ggplot2/) with free resources for Northwestern affiliated people.
