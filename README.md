# Exploring dplyr

This is a selection of scripts that reproduce several tutorials for the `dplyr` package. The focus is on understanding the common idioms that aid data exploration using this package.

There is an argument to be made to teach `dplyr` first, given the underlying goodness, and this repo is an exploration of whether this is a good option.

The battle is between the following two workflows:

`mtcars$mpg` and `mtcars %>% select(mpg)`

How strongly do we hold on to the noodle of weird symbols that is R? 

**What is in this repo?**

- From the package documentation: [Introduction](Introduction.md), [Joins](Understanding-Joins.md)
- [From data to summaries](Summarizing.md)
- [Programming with `dplyr`](Programming.md)
- [Pandas-1](Exploring-Modern-Pandas-1.ipynb)