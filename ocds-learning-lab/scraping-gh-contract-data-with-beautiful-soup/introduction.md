# Extracting data from pdf files with Tabula

Have you ever worked on a project where most of the data you need sits in a pdf file(s)? If you haven't, good for you! I've been in that situation a number of times and it's just annoying and time consuming to deal with especially if your only option is to manually copy and paste into an excel sheet. 

This repo is a starter guide on how you can extract data from tables in pdf format using [Tabula](https://pypi.org/project/tabula-py/). The first jupyter notebook (extracting_data_from_pdf_files_01) shows how you can extract data from a table on a single page in a pdf and cleaning it up. 

I'll be using the pdf 'Ghana_Health_Sector_2017.pdf' which I downloaded from the [Ghana Health Service](http://ghanahealthservice.org/downloads/FACTS+FIGURES_2017.pdf) website. It contains facts and figures of the health sector in Ghana as at 2017. This file a good example to demonstrate data extraction as it contains multiple tables in different formats spanning across multiple pages.

Over time, I'll add more notebooks with more complicated extractions like multiple page extraction, table with no borders etc.

Until data publishers spare us the headache of publishing in pdf formats, tools like Tabula will still be relevant.

## Software Installation
Installing Tabula is as simple as running
``` pip install tabula-py ``` in your terminal.

But just hold on, before installing Tabula the following are required:
* Java (confirmed working with Java 7 & 8)
* pandas
* urllib3
* distro

The internet is your best friend!
