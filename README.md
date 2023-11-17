# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit

Linkedin : 

YouTube Data Harvesting and Warehousing is a project that intends to provide the user with details of the youtube channel. The user have to provide the channel_id they intend to analyze and they can migrate the data from youtube to Mongodb and mysql database with a single click. The user can also analyze the stats of the channel compared to other channels. predefined questions are given to choose from and the user can select one and find the analysis related to the question. 
This project aims to improve the understanding of the API, MongoDB, MySQL and how to integrate all in one place and make a visually appealing web application. 
using SQL, MongoDB and Streamlit

![20231117052836](https://github.com/nandakishore2696/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit-/assets/139628432/0d1c3110-c8f8-4852-9bbd-e48d3d13ec2f)
This is the flow of the data from youtube to MySQL.

TOOLS AND LIBRARIES USED: This project requires the following components:

STREAMLIT: Streamlit library was used to create a user-friendly UI that enables users to interact with the programme and carry out data retrieval and analysis operations.

PYTHON: Python is a powerful programming language renowned for being easy to learn and understand. Python is the primary language employed in this project for the development of the complete application, including data retrieval, processing, analysis, and visualisation.

GOOGLE API CLIENT: The googleapiclient library in Python facilitates the communication with different Google APIs. Its primary purpose in this project is to interact with YouTube's Data API v3, allowing the retrieval of essential information like channel details, video specifics, and comments. By utilizing googleapiclient, developers can easily access and manipulate YouTube's extensive data resources through code.

MONGODB: MongoDB is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas. As a document database, MongoDB makes it easy for developers to store structured or unstructured data. It uses a JSON-like format to store documents.

POSTGRESQL: PostgreSQL is an open-source, advanced, and highly scalable database management system (DBMS) known for its reliability and extensive features. It provides a platform for storing and managing structured data, offering support for various data types and advanced SQL capabilities.

YOUTUBE DATA SCRAPPING AND ITS ETHICAL PERSPECTIVE: When engaging in the scraping of YouTube content, it is crucial to approach it ethically and responsibly. Respecting YouTube's terms and conditions, obtaining appropriate authorization, and adhering to data protection regulations are fundamental considerations. The collected data must be handled responsibly, ensuring privacy, confidentiality, and preventing any form of misuse or misrepresentation. Furthermore, it is important to take into account the potential impact on the platform and its community, striving for a fair and sustainable scraping process. By following these ethical guidelines, we can uphold integrity while extracting valuable insights from YouTube data.

REQUIRED LIBRARIES:

1.googleapiclient.discovery

2.streamlit

3.psycopg2

4.pymongo

5.pandas

FEATURES: The following functions are available in the YouTube Data Harvesting and Warehousing application: Retrieval of channel and video data from YouTube using the YouTube API.

Storage of data in a MongoDB database as a data lake.

Migration of data from the data lake to a SQL database for efficient querying and analysis.

Search and retrieval of data from the SQL database using different search options.
