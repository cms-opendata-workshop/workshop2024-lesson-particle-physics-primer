---
title: "Introduction"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is particle physics?
- What is happening at the LHC?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Develop a very broad overview of what particle physics is
- Develop a very broad overview of what takes place at CERN and the LHC

::::::::::::::::::::::::::::::::::::::::::::::::

# Introduction

Particle physics is an broad field which focuses on the study of the very smallest particles. Even
smaller than atoms! 

If you only had 5 minutes to learn about particle physics and wanted the simplest explanation possible, 
you could do worse than the [Simple Wikipedia entry for "Particle Physics"](https://simple.wikipedia.org/wiki/Particle_physics).

If you only had more time and could handle a higher level of discussion, a good starting point is
the [standard Wikipedia entry for "Particle Physics"](https://en.wikipedia.org/wiki/Particle_physics).

You probably want more though, so we'll provide some videos that go into a bit more detail about the specific topics
that the LHC (Large Hadron Collider) experiments focus on. We'll start with some videos intended for the general public, 
then go into some lectures by one of our collaborators, [Dr. Allison Hall](https://www.usna.edu/Users/physics/hall/index.php), 
and then end with some basic computing challenges that walk you through a toy example of discovering particles. 

First, some fun videos!



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

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
