---
layout: default
title: Dataverse
---

[Dataverse](https://dataverse.org/) is a "data repository framework to share and publish research data". The project uses the repository made available by Havard University at [dataverse.harvard.edu](https://dataverse.harvard.edu/) because:
* It is open to contributions from anyone;
* It has very generous limits in terms of file size (2.68 GB per file);
* It opens data to structured searches.

The project *dataverse* (which is a collection of *datasets*) is:

<center><p><a href="https://dataverse.harvard.edu/dataverse/ScrapeOpen">dataverse.harvard.edu/dataverse/ScrapeOpen</a></p></center>

# How to create a dataset

Click on `+Add Data` and `New Dataset`;

## Titling norms

Add an English translation of the actual name of the resource that originally published the data and the URL (without `http://`) of the same resource separated by a `|`.

<pre>
```
Historical Archive of Elections | elezionistorico.interno.gov.it
```
</pre>

## Metadata norms

Add the metadata as following the norms detailed below.

### Author(s) norms

Author should indicated their name and any other detail they wish to add.

### Description norms

The dataset must be described briefly (what do we find in the dataset?). The description should also include the URL of the resource and the URL of the scraper depository on the ScrapeOn repository. The description field accepts HTML tags.

<pre>
```html
Historical archive of Italian elections published by Italy's Ministry of Interior scraped from <a href='http://elezionistorico.interno.gov.it/'>elezionistorico.interno.gov.it</a>.
Code on GitHub: <a href = 'https://github.com/ScrapeOpen/elezionistorico.interno.gov.it'>github.com/ScrapeOpen/elezionistorico.interno.gov.it</a>.
```
</pre>

## Uploading norms

### Raw data

Raw data (i.e. data as downloaded from the original source) should be uploaded in compressed folders. To avoid automatic unpacking of the archive append `_` to the extensions (e.g. `.zip_` or `.tar_`). The file name should start with `raw_` followed by indication of the file type (e.g. `csv`, `xlm`) and brief indication that can help users navigate the different raw data archives.

<pre>
```
	raw_csv_20180304.zip_
```
</pre>
