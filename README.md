# Data Engineering Internship

Stemming from my drive to build a data portfolio, this repo highlights my learnings embarking on an eight week (June - July 2019) remote internship working with contracting data and tools that make it accessible for analysis. It contains both created and curated resources that I developed and studied, which will be beneficial for anyone starting to build technical data skills. 

For beginners in the technical data space, identifying a path of study is usually time consuming, overwhelming and stressful especially due to the abundance of resourses on the web. This usually makes individuals cave in, ditch data skill building and think of themselves as incompetent and incapable. I can relate to this experience as I've been there before many times. I created this repo with you in mind too. 

By documenting and sharing my internship, I hope that you are inspired and motivated in going through this repo and able to acquire the skills I gained within the period.

## Navigating this repo

### 1. [Extracting data from pdf files with tabula](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/extracting-data-from-pdf-files-with-tabula)
In this folder, you'll find:
- An [introduction](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/extracting-data-from-pdf-files-with-tabula/introduction.md) on why tools like Tabula-py are relevant
- A [jupyter notebook](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/extracting-data-from-pdf-files-with-tabula/extracting_data%20_from%20_pdf%20_files_01.ipynb) showing my proceedure in scraping data out of a pdf file
- The [scraped data](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/extracting-data-from-pdf-files-with-tabula/popn_dist_district_brong_ahafo.csv) in a csv file
- The [sample pdf](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/extracting-data-from-pdf-files-with-tabula/Ghana_Health_Sector_2017.pdf) I scraped the data from  

### [OCDS Learning Lab](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab)
The learning lab folder contains all works relating to contracting data. It includes subfolders on:

a. [The Flatten Tool](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab/flatten-tool-tutorial)
    - A [tutorial](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/flatten-tool-tutorial/Introduction%20to%20The%20Flatten%20Tool%20For%20OCDS.md) on how to use the flatten tool
    - A [jupyter notebook](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/flatten-tool-tutorial/analysing-flat-sample-ocds-award-data.ipynb) analysing flat contract data
    - A [jupyter notebook](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/flatten-tool-tutorial/flattening-sample-json-ocds-award-data.ipynb) flattening contract data
    - A [data folder](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab/flatten-tool-tutorial/data) which has the sample [contract json data](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/flatten-tool-tutorial/data/sample-ocds-award-data.json) and a [subfolder](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab/flatten-tool-tutorial/data/flattened_json(csv)) containing flat contract data in csv
    
b. [Scraping contracts data with Beautiful Soup](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab/scraping-gh-contract-data-with-beautiful-soup)
    - Source: Ghana's Public Procurement Authority [website](http://tenders.ppa.gov.gh/contracts)
    - My scraper in a [jupyter notebook](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/scraping-gh-contract-data-with-beautiful-soup/scraping_gh_contracts_data.ipynb)
    - A [requirements.txt](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/scraping-gh-contract-data-with-beautiful-soup/requirements.txt) file listing all the package and software dependancies to run the scraper
    - Scraped [data](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/scraping-gh-contract-data-with-beautiful-soup/contract_data_ppa_gh.csv) in a csv file

c. [Contract Data cleaning](https://github.com/jfarouk/Data-Engineering-Internship/tree/master/ocds-learning-lab/cleaning-gh-contract-data)
    - A [jupyter notebook](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/cleaning-gh-contract-data/cleaning_gh_contract_data.ipynb) showing my cleaning process
    - The [data](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/cleaning-gh-contract-data/contract_data_ppa_gh.csv) before cleaning
    - The cleaned [data](https://github.com/jfarouk/Data-Engineering-Internship/blob/master/ocds-learning-lab/cleaning-gh-contract-data/cleaned_gh_contract_data.csv)  

## Other Resources
- [Getting Started Section of OCDS Data Standard](http://standard.open-contracting.org/latest/en/getting_started/)
- [Learning Git with Bitbucket Cloud](https://www.atlassian.com/it/git/tutorials/learn-git-with-bitbucket-cloud)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Github Community starter kit](https://lab.github.com/githubtraining/community-starter-kit)
- [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Tabula-py Documentation](https://pypi.org/project/tabula-py/)
- [The Linux Command Line for Beginners Tutorial](https://tutorials.ubuntu.com/tutorial/command-line-for-beginners#0)
- [The Linux Command Line](https://drive.google.com/file/d/1tsQ2Uj1X2B8RBL7YI5FsR2hWKjKvj055/view)
- [Getting started with Python environments (using Conda)](https://towardsdatascience.com/getting-started-with-python-environments-using-conda-32e9f2779307)
- [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- [Datasheets for datasets](https://arxiv.org/pdf/1803.09010.pdf)



## Credits
This internship would not have been possible without the guidance and support of [David Opoku](https://twitter.com/sdopoku) in designing the program, providing resources and shaping my learning curve.


## Contribution
Support, resourses and enquiries can be directed at: j.jamilafarouk[a]gmail[.]com or [jamilafarouk_j](https://twitter.com/jamilafarouk_j) 

## Licence
MIT Licence
