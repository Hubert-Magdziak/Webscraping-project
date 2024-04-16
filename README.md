# Webscraping-project
The repository containts code for webscraping https://lodzka.policja.gov.pl/ld/form/63,Statystyki-dnia.html?page=0 website   
To scrape the pages we used: BeautifulSoup, requests, regex, lambda
The informations that were scraped from the website are numbers of:  
- "Zatrzymani na gorącym uczynku" - Arrested in the act (caught in the act)  
- "Zatrzymani poszukiwani" - Arrested wanted individuals  
- "Zatrzymani nietrzeźwi kierujący" - Arrested drunk drivers  
- "Wypadki drogowe" - Traffic accidents  
- "Zabici w wypadkach" - Killed in accidents  
- "Ranni w wypadkach" - Injured in accidents  
for every day between 2016-01-31 and actual date

On the other hand, we also scrape https://policja.pl/pol/form/1,Informacja-dzienna.html? website  
To scrape the pages we used: BeautifulSoup, requests
The informations that were scraped:  
- "Interwencje"  
- "Zatrzymani na gorącym uczynku" - Arrested in the act (caught in the act)  
- "Zatrzymani poszukiwani" - Arrested wanted individuals
- "Kierujący po spożyciu alkoholu" - Arrested drunk drivers  
- "Wypadki drogowe" - Traffic accidents
- "Zabici w wypadkach" - Killed in accidents
- "Ranni w wypadkach" - Injured in accidents  
for every day between any number of preceiding days and actual date

To scrape headers of the 5 most actual articles on the website https://lodzka.policja.gov.pl/ we used Selenium and BeautifulSoup.
