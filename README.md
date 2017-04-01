# Coursera Dump

The script takes a list of all [Coursera](https://www.coursera.org/) courses from [here](https://www.coursera.org/sitemap~www~courses.xml) and randomly picks up 20 of them. Then it parses the page of each one of these courses and finds its title, language, starting date, number of weeks and rating. Finally, it outputs the result to the excel file .xlsx into the desired directory.
To run, install the required packages:
```#!bash
$ pip install -r requirements.txt
```
Note, that in rare cases the script cannot identify some of the data. Either because it is not indeed indicitated at the page or the page source does not explicitely contain this information. For instance, this was noticed with the reference to some non-English courses pages.
Also it might take a couple of minutes to gather all the info.

# Usage

Indicate a filepath to a file in which you would like to save the results and voilà:
```#!bash
$ python coursera.py courses.xlsx
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
