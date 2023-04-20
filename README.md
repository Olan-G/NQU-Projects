# National Quemoy University - Modern Programming Language Projects
 This repository contains my midterm and final project during my exchange student program at National Quemoy University, Kinmen County, Taiwan
 
1. USD - NTD - PHP Exchange Rate Monitoring System
    - This program utilizes a web crawler to extract the exchange rate between USD-PHP, USD-NTD, and PHP-NTD from the folowing websites:
       1. USD - NTD: https://www.exchangerates.org.uk/Dollars-to-Taiwan-Dollar-currency-conversion-page.html
       2. USD - PHP: https://www.exchangerates.org.uk/Dollars-to-Philippine-Pesos-currency-conversion-page.html
       3. NTD - PHP: https://www.exchangerates.org.uk/Taiwan-Dollar-to-Philippine-Pesos-currency-conversion-page.html
   - This program also gets the historical data of these currencies' exchange rates by extracting in from oen website but varies in the date given to it.
      - This is accomplished by editing the "date" part of the URL of the website.
      - `req.get("https://rate.bot.com.tw/cr/"+str(i)+"-0"+str(j))`
