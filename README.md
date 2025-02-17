Web Scraping and Data Cleaning

Overview

This project focuses on web scraping data from the web and performing data cleaning to prepare it for analysis.(Website: smartprix.com)
The project demonstrates techniques such as extracting data from websites using BeautifulSoup and Selenium, handling missing values, removing duplicates, and performing feature engineering.

Features

Web Scraping: Extracts data from a website using BeautifulSoup and Selenium.

Data Cleaning: Handles missing values, removes duplicates, and processes inconsistent data.

Data Preprocessing: Transforms raw data into a structured format for analysis.

Technologies Used

Python

BeautifulSoup (for parsing HTML content)

Selenium (for automating web browsing and scraping dynamic content)

Pandas (for data manipulation and cleaning)

NumPy (for numerical operations)

Matplotlib/Seaborn (for data visualization)

Installation

To run this project, follow these steps:

Clone the repository:

git clone https://github.com/RohitKunjadiya/Web-Scraping-and-Data-Cleaning.git
cd Web-Scraping-and-Data-Cleaning

Create a virtual environment :

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Usage

Data Gathering:

The Mobile_Phone_Web_Scraping.ipynb notebook contains code for scraping smartphone data.

The smartprix.py script automates the scraping process using BeautifulSoup.

The raw HTML file smartprix.html is also included for reference.

The extracted data is stored in smartphone.csv.

Data Cleaning:

The cleaning-1.ipynb and cleaning-2.ipynb notebooks perform data cleaning steps such as:

Handling missing values

Removing duplicates

Standardizing column names

Converting data types

The cleaned datasets are saved as:

smartphone_cleaned_v1.csv

smartphone_data_cleaned.csv

smartphones.csv

Folder Structure

Web-Scraping-and-Data-Cleaning/

│── Data Gathering/

│   │── Mobile_Phone_Web_Scraping.ipynb  # Jupyter Notebook for scraping

│   │── smartprix.py                     # Web scraping script

│   │── smartprix.html                   # HTML file used for scraping

│   │── smartphones.csv                    # Raw scraped data

│── Data Cleaning/

│   │── cleaning-1.ipynb                  # Data cleaning steps - Part 1

│   │── cleaning-2.ipynb                  # Data cleaning steps - Part 2

│   │── smartphone_cleaned_v1.csv         # Cleaned dataset version 1

│   │── smartphone_data_cleaned.csv       # Final cleaned dataset

│   │── smartphones.csv                   # Additional processed data

│── README.md                             # Project documentation

Contributing
                  
Feel free to submit issues or pull requests if you want to improve the project. Contributions are welcome!
      
Contact

For any queries or suggestions, contact:

GitHub: RohitKunjadiya

Email: rohitkunjadiya1919@gmail.com

      
