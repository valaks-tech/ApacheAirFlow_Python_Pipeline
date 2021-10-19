# ApacheAirFlow_Python_Pipeline
Creating data pipeline using Python, Apache AirFlow

To Do: 

* Need to create data pipeline from source database (mySQL) to target database (PostgreSQL) 
* Read the data from mySQL and write to target db
* Read a file which has tables list , get the data from those tables into collections and those collections will be used to write to PostgreSQL database and few logics will be used around processing 

Quick Note: SQLAlchemy may not be needed here as its just for pipelines and we dont have to write complex SQL queries in this test case. SQLAlchemy (an ORM) will only steamline the way you connect to the database and may not add any benefit in the case of pipelines. So not choosing SQLAlchemy here.


