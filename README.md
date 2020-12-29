# FDOTscraper
Scrape FDOT Cameras

Does basic scraping off the FL511 website.
Cameras are split into areas and ranges.
Some areas have no cameras, some areas only have cameras in certain ranges.

Flags:
-sa = Start of search area
-ea = End of search area
-sr = Start of search range
-er = End of search range

Example:
This will cover all (as far as I know) cameras in all ranges, but will take the longest time.
python FDOTscraper.py -sr 0 -er 9999 -sa 1 -ea 18


Latest releases here: https://github.com/KuRue/FDOTscraper/releases
