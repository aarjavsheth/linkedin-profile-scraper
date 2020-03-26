# linkedin-profile-scraper
Scrapes LinkedIn User Profile.

A simple python script to scrape user's location, experience and education details.

## Usage
Enter path to chromedriver.exe file in the following code
```python
def getData(self):
        driver = webdriver.Chrome('Path:/To/chromedriver/chromedriver.exe')
```
Enter your email address and password in class Scrape
```python
email = "some@email.address" #Enter username of linkedin account here
password = "SOMEPASSWORD" #Enter password of linkedin account here
```

Enter user profile url in the following code
```
person = Person("https://www.linkedin.com/in/someprofile", driver=driver) #Enter LinkedIn profile url of user
```

## Requirements
1. [Chromedriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)
2. Selenium
```
pip install selenium
```
3. lxml
```
pip install lxml
```
4. xlsxwriter
```
pip install XlsxWriter
```

## Disclaimer
Scraping data off of LinkedIn is against their User Agreement. This is purely intended for educational purposes.
