---
layout: default
title: Documentation
---

# Getting started

The project relies on two web services: the Harvard's [Dataverse](https://dataverse.harvard.edu) and [GitHub.com](https://github.com/). If you want to collaborate, you can sign up to both services (or to just one of the them) for free.

If you are want to understand what Dataverse and GitHub.com, here two short introductory videos:

## Video introduction to Dataverse

<iframe width="640" height="360" src="https://www.youtube.com/embed/7_Elpmntb1g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Video introduction to GitHub.com

<iframe width="640" height="360" src="https://www.youtube.com/embed/w3jLJU7DT5E" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Workflow

<div class="row">
<div class="column" markdown="1">
A typical workflow would include these steps:

1. Identify a web source that services interesting data but in a format that doesn't allow data analysis.
2. Write code (a little computer program) to scrape the resource and publish in a dedicated *Repository* on **github.com**.
3. Collect the raw data and store it in a *Dataset* within the project's *Dataverse* on **dataverse.harvard.edu**.
3. Write code to make the raw data more readable, and publish the code on   **github.com** and the data on **dataverse.harvard.edu**.
4. Document the data on **github.com**.

</div>
  <div class="column"><img src="/ScrapeOpen/images/workflow-diagram.svg" alt="Workflow diagram" style="height: 550px; display: block; margin-left: auto; margin-right: auto;"/></div>
  </div>

## Essential glossary

Repository
: On **github.com**, a *repository* (or *repo*) is a collection of files in their current version and in their previous versions.

Dataverse
: On **dataverse.harvard.edu**, a *dataverse* is a collection of *datasets*.

Dataset
: On **dataverse.harvard.edu**, a *dataset* is a collection of files and their metadata.

# Coding for data

If you are interested in coding for the project, read this [documentation](coding.html). 

# Storing data

If you want to understand how data is stored in the [project's Dataverse](https://dataverse.harvard.edu/dataverse/ScrapeOpen), visit the [documentation page](dataverse.html).
