---
title: "R Markdown test"
author: "Philippe Grosjean"
date: 2017-11-27T18:36:00-01:00
categories: ["R"]
tags: ["R Markdown", "plot", "regression"]
draft: false
summary: "Exemple of using R chunks, R figures and reference to figures"
---

Some example Python code:

```python
import re
for test_string in ['555-1212', 'ILL-EGAL']:
  if re.match(r'^\d{3}-\d{4}$', test_string):
    print test_string, 'is a valid US local phone number'
  else:
    print test_string, 'rejected'
```

... and R code:

```r
cube <- function(x) {
  if (!is.numeric(x))
    stop("'x' must be numeric")
  return(x^3)
}
# Use this function
cube(1:10)
```

R Chunks:

```{r setup, include=FALSE}
knitr::opts_chunk$set(collapse = TRUE)
```

## R Markdown

Test of an R Markdown post, see <http://rmarkdown.rstudio.com>. You can embed an R code chunk like this:

```{r cars}
cars_lm <- lm(dist ~ speed, data = cars)
cars_lm
```

## Including Plots

You can also embed plots. See Figure \@ref(fig:pie) for example:

```{r pie, fig.cap='A fancy pie chart.', tidy=FALSE}
par(mar = c(0, 1, 0, 1))
pie(
  c(280, 60, 20),
  c('Sky', 'Sunny side of pyramid', 'Shady side of pyramid'),
  col = c('#0292D8', '#F7EA39', '#C4B632'),
  init.angle = -50, border = NA
)
```

{{% alert note %}}
You can use an `alert note` to stand out a section.
{{% /alert %}}


## Hugo shortcodes

In R Markdown, you should not use the `{{< tweet 936232450006704128 >}}` syntax. Instead, you should use:

```{r echo=FALSE}
blogdown::shortcode('tweet', '936232450006704128')
```


### Other examples

Youtube

```{r echo=FALSE}
blogdown::shortcode('youtube', 'ZwYQPtU2Pa0') # or 'w7Ft2ymGmfc'
```

Vimeo

```{r echo=FALSE}
blogdown::shortcode('vimeo', '146022717')
```

Github Gist

```{r echo=FALSE}
blogdown::shortcode('gist', 'phgrosjean', 'f1d53c0dc1124522b2138033188497d0')
```

Speakerdeck

```{r echo=FALSE}
blogdown::shortcode('speakerdeck', '4e8126e72d853c0060001f97')
```

Figure

```{r echo=FALSE}
blogdown::shortcode('figure', src = '/img/coral.jpg', alt = "A nice fluorescent coral")
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM1Mjk3NzM3Nl19
-->