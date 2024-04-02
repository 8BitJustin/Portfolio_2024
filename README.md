# Portfolio 2024

Long overdue, here is what I hope is a website to show what I've done professionally, and what I do for fun.

## About

My last portfolio was built over four years ago, and a lot has changed in that time. The purpose here is to create a website that has two sides:

- Professional
    - This is where I give a long and short description of my entire working career.
    - Here I will give details into what I know coding and how I went about learning.
    - I'll go over the specifics of what I built with Caliber to demonstrate what I've done.
    - Maybe I'll go over my git stuff here, or will add that to...

- Fun and Hobbies
    - This is where I'll go over the fun side.
    - 3D printing, coding, car stuff, etc.

### Getting Started/Prerequisites

What is needed for this to work.

Python 3 (3.7 used)

Selenium (webdriver)


### Installing

Download or clone the repo.

Place into desired folder.

Ensure Python is installed.

Install Selenium
```
pip install selenium
```

## Running Script

If using PyCharm, within the project directory, simply run the main.py file.

If using the terminal, while in the project directory, type the following:
```
python main.py
```

To change the search parameter, change the parameter within the send_keys
 method.
```
driver.find_element_by_id("search").send_keys("INPUT SEARCH HERE")
```

## Versions

- V2.0
  - 11/22/2020
  - Program simplified. As send_email.py didn't need to be used multiple
   times, the code for it was reworked and placed within oktane.py, along
    with main.py code. Program now works out of one file, as send_email.py
     is no longer used.
- v1.0
  - 11/15/2020
  - Initial commit. Both main.py and send_email.py both used, main.py input
   within launchPy.bat file

## Built With

-   [Python](https://www.python.org/) - Programming Language Used
-   [Selenium](https://pypi.org/project/selenium/) - Automates Web Browser Interaction

## Authors

-   **Justin Olson** - _Initial work_ - [Portfolio](https://jodportfolio.herokuapp.com/)

## Acknowledgments

-   Kaden
-   Stack Overflow
-   Google Searching
