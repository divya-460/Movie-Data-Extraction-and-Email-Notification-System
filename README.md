## Movie Data Extraction and Email Notification System

# Description
The Bollywood Movie Data Extraction and Email Notification System is a web scraping project developed in Python using BeautifulSoup. This project focuses on extracting detailed information about Bollywood movies from a website, storing the data in a MySQL database, and sending automated monthly email notifications containing the latest movie updates.

The data extraction process involves scraping information such as movie title, director, cast, release date, and the platform where the movie is available for streaming. The extracted data is then organized and stored in a MySQL database for easy management and retrieval.

To orchestrate the ETL (Extract, Transform, Load) process and schedule monthly updates, the project leverages Apache Airflow. Airflow allows for the automation of data extraction and notification tasks, ensuring that users receive timely and relevant information about upcoming Bollywood movies.

Technologies Used
> Python
> BeautifulSoup
> MySQL
> Apache Airflow
> HTML/CSS
