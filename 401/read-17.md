# **4011 Class #06**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**Web Scraping**](#web-scraping)
  - [**Table of Contents**](#code-401-reading-notes)

---

## **Things I want to know more about**
- Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort
- Read through the website’s Terms and Conditions to understand how you can legally use the data
- Make sure you are not downloading data at too rapid a rate because this may break the website
- What you Import 
  - import requests
  - import urllib.request
  - import time
  - from bs4 import BeautifulSoup
- What Next
  - url = 'http://web.mta.info/developers/turnstile.html'
  - response = requests.get(url)
  - You should get a 200 response code
- Soup Steps
  - soup = BeautifulSoup(response.text, “html.parser”)
  - soup.findAll('a') - find all a tags
- Testing with one Link
  - one_a_tag = soup.findAll(‘a’)[38]
  - link = one_a_tag[‘href’]
  - This code saves the first text file
- Pause our Scrape
  - time.sleep(1)
- 


---

## **Web Scraping**



## [**Code 401 Reading Notes**](/401/401homepage.md)
  1. [Read 01]
  2. [Read 02](/401/read-02.md)
  3. [Read 03](/401/read-03.md)
  4. [Read 04](/401/read-04.md)
  5. Day 04
  6. Day 05
  7. [Read 06](/401/read-06.md)
  8. [Read 07](/401/read-07.md)
  9. [Read 08](/401/read-08.md)
  10. [Read 09](/401/read-09.md)
  11. Day 10
  12. Day 11
  13. [Read 12]()
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
