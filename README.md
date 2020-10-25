# Mississippi River Golf Adventure

Team: Jeff Brown, Emily Frels, Jeanine Vincent

## Project Description
Golf Information Kiosk

    The ultimate golf road trip
    
    The beating heart of America lies in its great middle and the pulsing artery of the nation is the Mississippi River
    
    It stretches from its headwaters in icy Lake Itasca in Northwestern Minnesota and flows more than 2,300 miles to the Golf of Mexico
    
    An opportunity to discover America through it’s golf courses and experience a wide range of American regional culture

## Source

Detailed information on golf courses with green fees range and tees, this complete golf courses database has 15,606 records across 7,891 cities over 53 states in the United States. Each record is comprised of address, street, phone number, zip code, hole, architect, year built, public/private, guest policy, credit card, golf season, range, rental club, pro in house, metal spikes okay, weekday, weekend, tee time welcomed, rental cart available, championship par/yards/slope/USGA, middle par/yards/slope/USGA and forward par/yards/slope/USGA

     https://www.usabledatabases.com/database/golf-courses-in-us/

## Instructions:

    Step 1: Extract, clean and transform the input dataset (golf_ETL.ipynb)

        Before running this Jupyter notebook, make sure that you update the config.py file with a Google Map API Key as gkey

    Step 2 : To load the golf details into a PostgreSQL database, run golf_db_load.ipynb

        Before running the load process, follow these steps:

        create a new database in ProstgreSQL and name it Golf

        run schema.sql to create the table in the new database

        use a config.py file to store username and password for the new database you just created - it should look something like this

            username = "postgres"
            password = "mypassword"


