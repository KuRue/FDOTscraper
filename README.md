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

Example:<br/>
This will cover all (as far as I know) cameras in all ranges, but will take the longest time.<br/>
python FDOTscraper.py -sr 0 -er 9999 -sa 1 -ea 18<br/><br/>

DO NOT USE THE WINDOWS STORE PYTHON
It has a hard time with requests-html

Latest releases here: https://github.com/KuRue/FDOTscraper/releases
