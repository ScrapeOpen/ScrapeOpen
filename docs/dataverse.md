---
layout: default
title: Dataverse
---

[Dataverse](https://dataverse.org/) is a "data repository framework to share and publish research data". The project uses the repository made available by Havard University at [dataverse.harvard.edu](https://dataverse.harvard.edu/) because:
* It is open to contributions from anyone;
* It has no limits in terms of file size or type;
* It opens data to structured searches.

The project *dataverse* (which is a collection of *datasets*) is:

<center><p><a href="https://dataverse.harvard.edu/dataverse/ScrapeOpen">dataverse.harvard.edu/dataverse/ScrapeOpen</a></p></center>

# How to create a dataset

1. Click on `+Add Data` and `New Dataset`;

## Titling norms

2. Add an English translation of the actual name of the resource that originally published the data and the URL (without `http://`) of the same resource separated by a `|`.

```
Historical Archive of Elections | elezionistorico.interno.gov.it
```

## Metadata norms

3. Add the metadata as following the norms detailed below.

### Author(s)

Author should indicated their name and any other detail they wish to add.

### Description

The dataset must be described briefly (what do we find in the dataset?). The description should also include the URL of the resource and the URL of the scraper depository on the ScrapeOn repository. The description field accepts HTML tags.

```html
Historical archive of Italian elections published by Italy's Ministry of Interior scraped from <a href='http://elezionistorico.interno.gov.it/'>elezionistorico.interno.gov.it</a>. Code on GitHub: <a href = 'https://github.com/ScrapeOpen/elezionistorico.interno.gov.it'>github.com/ScrapeOpen/elezionistorico.interno.gov.it</a>.
```


