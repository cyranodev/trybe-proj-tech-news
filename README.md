#### <a name="top"></a> This repo is a clone of an individual project part of [Trybe](https://www.betrybe.com/) junior web developer course.
##### https://www.betrybe.com/ (in Portuguese)

# Tech News

![!project status](https://img.shields.io/badge/status-development-yellow)


- [Requisites](#requisites)
- [Instructions](#instructions)


## Requisites <a name="requisites"></a>

The block enclosed by this project covers Python and data scraping. **Tech News** is a simple app that fetches news from a Brazilian tech website ([TechMundo](https://www.tecmundo.com.br)) and scrapes titles, urls and first paragraphs of its latest news. 🤖

The project's filenames and architecture are defined by the project and must be unchanged to pass the course tests.

Original requirements and instructions (in Portuguese) for the project are [**here**](README_original.md).


**Requisites sum-up:**

- Create functions step-by-step to:
  - fetch data
  - scrape and store contents using MongoDB
- Develop features to:
  - search fetched news by title, date, category and news source
  - Analyze stored news to bring the top 5 most popular news and the top 5 categories
- Create a script to run the app from the terminal

##### [back to top](#top)

## Instructions <a name="instructions"></a>

**Clone** the repo or **download** the zip.

Be sure to have Python installed in your system.

Go to the project folder and run phyton's command to install. **For example** (in Ubuntu):
`python3 -m venv .venv && source .venv/bin/activate` to start a virtual environment
`python3 -m pip install -r dev-requirements.txt`

To **run** the app:
```bash
tech-news-analyzer
```

To run **tests** (within project folder):
```bash
$ python3 -m pytest
```

#### Important: mongoDB services must be installed and active in your machine.

##### [back to top](#top)

