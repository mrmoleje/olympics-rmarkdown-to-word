


# Olympics R Markdown to word

Using data from the Olympics this repo gives an example of how to create a simple word document using R Markdown.

This example will use the ['dplyr'](https://dplyr.tidyverse.org/) package to manipulate the data, and the ['ggplot'](https://ggplot2.tidyverse.org/package) to create some bar charts. 

The analysis developed using dplyr will then be put into a word document to create a report. The purpose of this is to highlight how report writing can be reproducable, as when the data is changed, the outputs in the report automatically update.

## Getting Started

You can clone this repo by typing the following into the command line:

```
git clone https://github.com/mrmoleje/olympics-rmarkdown-to-word.git 
```

### Prerequisites

In order to run the script you'll need R Studio installed, as well as the following libraries:

```
libraries (c("tidyverse", "rmarkdown", "readr", "tidyr"))
```

### Data

Olympics data for this example was downloaded from ['Kaggle'](https://www.kaggle.com/ahmetuzgor/my-first-data-analysis-with-athletes-data/data). 
