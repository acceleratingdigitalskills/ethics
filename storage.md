---
title: "Storing Data Carefully"
teaching: 17
exercises: 8
---

:::::::::::::::::::::::::::::::::::::: questions 

- How much data should we collect and keep for research projects?
- How can we store data carefully?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Reflect on benefits and drawbacks of data collection
- Consider principles of data minimisation and secure data storage
- Introduce FAIR principles

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

When academics first consider using web data as part of their research, they may not consider what they want the data for, or how they will store it. In our current data-rich era, it is all too easy to collect a lot of data without a specific plan for keeping it securely. We might end up with more information than we need or risk losing data due to a lack of planning.

::::::::::::::::: callout

### Data-rush!

Koen Leurs^[Leurs, Koen. ‘Feminist Data Studies: Using Digital Methods for Ethical, Reflexive and Situated Socio-Cultural Research’. Feminist Review 115, no. 1 (1 March 2017): 130–54. https://doi.org/10.1057/s41305-017-0043-1.] identifies a 'data-rush mentality' which can be witnessed in the arts and humanities. Can you think of any research initiatives which rushed ahead to collect data without careful consideration?

::::::::::::::::::::::::::::::::::::: instructor

- It may be helpful to provide the learners with a specific example from your own research background. This could be drawn from your work, a colleague's work, or a publication, where you felt data could have been collected with more forethought. Offer this anecdote to help the learners reflect on the trend Leurs identifies.

:::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::


For music researchers getting started with collecting web data about music, it is natural to be somewhat exploratory. However, we have already identified some potential harms of storing excess data -- potential holding on to protected information about other people.

To avoid this issue, it may be better to limit the amount of web data researchers collect.

## Data Minimisation

The idea of collecting only the data you need to complete your research is the main principle of **data minimisation**. This term has been used in both legal frameworks and research guidelines.

It is an important part of approaching a research project using web data about music more responsibly. To help *minimise* the data you have means asking questions like:

### - Do I need to collect this type of data?

If you are not planning to analyse date information as part of a research project, you do not strictly need to collect dates (e.g., the date a music video was uploaded).

If you are working on a deidentified corpus of text like user comments, you may not need to collect commenter usernames. This would help you [protect users](protecting-users.md).



This is an especially important consideration for research on music, as so much data shared by users is distinctly ideological. 






::: challenge 

## Exercise: Music Research Using Web Data

Write one possible benefit and one potential drawback of using web data in music research.

::: solution 

Some potential benefits: 
* Access to a wide range of people's responses to music
* Quickly gain research data
* Minimal cost to data collection
* Increase statistical power of findings
* May discover patterns in big data that could not be seen otherwise

Some potential drawbacks:
* Not representative dataset
* May not be aware who exactly we are studying
* Ethical issues around informed consent
* Risk of losing context for data
* May be difficult to interpret large data sets



## Output
 
```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides": 
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- The principle of data minimisation encourages you to collect and store *less* data
- The dynamic nature of internet data suggests it might be better to collect and store *more* data
- Designing research projects should involve careful consideration of what kind of data to collect, how much data to collect, how to store it, and how long to store it
- FAIR principles of data management are embedded in university research contexts and should also be considered

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
