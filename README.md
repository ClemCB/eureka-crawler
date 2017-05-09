# Eureka Crawler

Final project (weeks 11 & 12) at Makers Academy. Tasked with working on a project of our design in languages and testing frameworks of our choice.

Central throughout the project were TDD/BDD, XP values and agile practices.

Team:
- [Clem Capel-Bird](https://github.com/ClemCB)
- [Nicholas Leacock](https://github.com/marudine)
- [Vicky Ledsom](https://github.com/ledleds)
- [Rory McGuinness](https://github.com/rorymcgit)

## Technologies

- python3
- unittest for testing
- PostgreSQL Database

## How to Run

Installation:

- Run ```./db-config.sh``` to create your test and development databases and tables
- If you get an error regarding permissions, you'll need to run ```chmod +x db-config.sh```, then run the above again
- If you have any errors you may need to install some or all of the following: ``` brew install python3 ``` & ``` pip3 install sqlalchemy ``` & ``` pip3 install psycopg2``` & ``` pip3 install bs4 ```

To crawl:

- Open /initiate_crawl.py
- Enter a website to begin crawling
- Run ``` python3 initiate_crawl.py ```

To search your crawled links:

- Follow the installation and run instructions on [Eureka Search](https://github.com/ClemCB/eureka-search-engine)
