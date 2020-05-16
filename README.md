## Introduction

Welcome to **Introduction to R and Data Science**, a 10-lecture course that will (hopefully) convince all of you to start using R, and teach you the basic principles as well as several advanced aspects of the programming language [R](https://en.wikipedia.org/wiki/R_(programming_language)), a statistical programming language which has recently seen a surge in popularity because of its power and ease of use.

This course will introduce you to the basic tenets of R, including tidying and analyzing data. More specifically, it will (hopefully) convince you that *almost everything* can be done **easier and more efficiently** using R than in other ways. The syntax of R takes a while to get used to, but after a (short) initial period of frustration, you will quickly find yourself making less and less syntactical mistakes, and programming in R will go smoother and smoother. This course is an attempt of making that period of frustration as short as possible. 

First, we will focus on the fundamentals: installing R/Rstudio, and importing and reading data in various formats in R. This is a relatively simple task, but there are several dangers/nuances which are useful to know beforehand. Afterwards, we focus on **core programming**: we will learn about variable classes, functions, for loops, and indenting. 

Afterwards, we tackle arguably one of the most important task: tidying our data. Data comes in many formats, and it is not always straightforward to get the data in a format which can be recognized by programs/functions that perform statistical or graphical analysis. The process of doing this is called **data tidying**, and R programmers have developed a fantastic set of packages, together called the **tidyverse** to do this. In this course, we will familiarize ourselves with the most common and most useful tidyverse functions to learn how to tidy just about every format of untidy data. 

After you've mastered how to tidy data in R, we can use several plotting environments to create graphs and other visualizations of our data. In the past, many people used MS Excel or other programs to generate graphs, which harmed reproducibility (there is no code leading up to a graph), and the graphs are ..not aesthetically pleasing. We will learn how to efficiently program visualizations, and make our **workflow** more efficient by learning how to easily update our figures when, for example, we use additional data, or we want to add an additional variable. 

Next, we will learn how to perform basic statistical analyses in R, and efficiently report them, for example, in your next presentation at a conference, or in your current paper. We consider this to be the essentials of any R user. 

## Course contents

| Lecture | Subject                                               | Slides |
| ------- | ----------------------------------------------------- | ------ |
| 1       | Installing R, RStudio, Sneak Preview                  | Here   |
| 2       | Basic R Syntax, Object Classes                        | Here   |
| 3       | Packages, Swirl, Functions, `for` loops               | Here   |
| 4       | The `apply()` family and the tidyverse                | Here   |
| 5       | Data cleaning and string extraction                   | Here   |
| 6       | Data manipulation, selection, filtering               | Here   |
| 7       | Graphics: `ggplot2` - Basics                          | Here   |
| 8       | Graphics: `ggplot2` - Customizing your visualizations | Here   |
| 9       | Graphics: Spacial data and Choropleths                | Here   |
| 10      | Statistics: Linear models and the `stargazer` package | Here   |
| 11      | Statistics: Time series models                        | Here   |
| 12      | Web scraping: server-side                             | Here   |
| 13      | Web scraping: API's                                   | Here   |
| 14      | Data Transparency                                     | Here   |
| 15      | Reproducible research: RMarkdown - Basics             | Here   |
| 16      | Reproducible research: RMarkdown - Rpubs, Blogdown    | Here   |

## Prerequisites

None, but some preliminary experience in a spreadsheet programme, or in another statistical language makes you appreciate more easily the benefits of R. 

## Course objectives

The objectives of this course are: 

- Learn how to use R for basic data treatment.

- Learn how to effectively visualize data that meets quality standards required for journal submissions

- Learn how to perform basic statistical analyses in R

- Learn to effectively report all previously mentioned aspects using RMarkdown and/or basic LaTeX 

- Develop an effective workflow, and ensure reproducibility of your work

## Lecture Notes

At the beginning of each session, you can follow along by downloading the __RMarkdown__ files which we have created for each session. This way, you can (i) reproduce everything we do, and (ii) add spontaneous pieces of code to explore variations. Additionally, it will (hopefully) spontaneously teach you some of the syntax of Markdown and/or LaTeX, and encourage you to use those to make your own workflow as efficient as possible. 

## Cheat sheets

Many packages in R have so-called cheat sheets available. As it takes a lot of time to memorize all commands and arguements, it is more logical to have a cheat sheet at arms length that can (i) briefly describe the most common functions of a particular function and (ii) explain which arguments can and should be specified in a function call. In this section, I provide links to a few cheat sheets for the most often-used R packages:

### Languages/Programs

- [RStudio](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)

- [Markdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)

- [LaTeX](https://wch.github.io/latexsheet/)

### Data treatment

- [Forcats](https://github.com/rstudio/cheatsheets/raw/master/factors.pdf)

- [Data Import](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf)

- [Dplyr](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)

- [Stringr](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf)

- [purr](https://github.com/rstudio/cheatsheets/raw/master/purrr.pdf)

- [lubridate](https://github.com/rstudio/cheatsheets/raw/master/lubridate.pdf)

### Data analysis

- [ggplot2](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)

- [stargazer](https://www.jakeruss.com/cheatsheets/stargazer/)

- [estimatr](https://github.com/rstudio/cheatsheets/raw/master/estimatr.pdf)

## Questions

Please mail any questions and suggestions to [a.h.machielsen@uu.nl](mailto:a.h.machielsen@uu.nl) or open an Issue. 

