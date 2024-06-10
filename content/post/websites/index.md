---
date: "2024-06-10"
summary:  Construction of a website using RStudio as the IDE
title: Building Websites
---

## Building a website using RStudio as the IDE

To build a website for the GERALDO tool, I started a repository called geraldo in the UCSC hummingbird server. The original article I read to learn how to build a website was written by Emily Zabor[^1]. 

[^1]: Creating websites in R. [Zabor, (2020)](https://www.emilyzabor.com/tutorials/rmarkdown_websites_tutorial.html).

The first thing I did was to create a repository on GitHub. To begin I put here a link to the repository here[^2].

[^2]: GERALDO repository: [geraldo github repo](https://github.com/gepolianochaves/geraldo). 

After the geraldo repository was created, I cloned it in my local machine. Then I added an R Project to the geraldo directory. 

To do this last step, I opened RStudio, clicked File > New Project.

I noticed by practice that it is necessary to create the _site.yml and index.Rmd files to be able to activate the Build tab in RStudio. 

Configuration of the _site.yml file can be found in the link :  [_site.yml file configuration](https://github.com/gepolianochaves/geraldo/blob/main/_site.yml). 



So last thing I did to complete this part was to create the _site.yml and index.Rmd files that are stored with the geraldo.Rproj file in the geraldo repository I just created. 

With the active Build tab in RStudio, we can then press the Build Website and RStudio does just that in my local machine.

In the future I want to be able to push files to GitHub to be able to develop the GERALDO tool ...




