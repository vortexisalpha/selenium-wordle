# selenium-wordle

This code uses selenium library with python and chromedriver to play the popular game wordle.

This involves  bypassing of shadow roots in a web page which is a challenge I had to overcome while building this.
  The New York Times Wordle website uses a type of web scraping prevention called shadow roots, hiding elements from any web scraping devices. In the file main.py you can see how I bypassed this bot prevention and was able 
  to scrape the information nessecary for using an algorithm to solve the game.

This chromedriver is just a sample file. To find the one that works with your chrome, look at your chrome version and install the necessary chromedriver associated with that version:  
https://chromedriver.chromium.org/downloads

Install the selenium webdriver with pip aswell to use this code:
pip install selenium
OR
pip3 install selenium
