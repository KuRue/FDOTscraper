# FDOTscraper
Scrape FDOT Cameras<br/>

Does basic scraping off the FL511 website.<br/>
Cameras are split into areas and ranges.<br/>
Some areas have no cameras, some areas only have cameras in certain ranges.<br/>

![alt text](https://github.com/KuRue/FDOTscraper/blob/main/Image.jpg?raw=true)

Flags:<br/>
-sa = Start of search area<br/>
-ea = End of search area<br/>
-sr = Start of search range<br/>
-er = End of search range<br/>
-p  = Path (default = fl511) 
nothing = REGULAR mode : queries for each camera in area and range defined,  saves any images it can find.<br/>
-s = SCAN mode : Scans through area and range defined, saves list of good cameras without downloading images.<br/>
-l = LIST mode :  Uses saved list of good cameras to avoid checking bad areas and ranges.<br/>

Examples:<br/>
Scrape cameras 600 through 700 in area 12<br/>
```FDOTscraper.py -sr 600 -er 700 -sa 12 -ea 12```<br/>
Scan entire range and save good cameras to list called cameras.txt<br/>
```FDOTscraper.py -s cameras.txt```<br/>
Scan cameras 0 to 1000 in area 7 through 9 and save good cameras to list called cameras.txt<br/>
```FDOTscraper.py -sr 0 -er 1000 -sa 7 -ea 9 -s cameras.txt```<br/>
Scrape all good cameras from are 8.<br/>
```FDOTscraper.py -sa 8 -ea 8 -s cameras.txt```<br/>


DO NOT USE THE WINDOWS STORE PYTHON <br/>
It has a hard time with requests-html

Latest releases here: https://github.com/KuRue/FDOTscraper/releases
