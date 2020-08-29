Ireland in 2020
Made by PlasticPaddy
Tested on version 1.08
Mod version: 1.0

Installation:
- Copy the contents to the game folder (Program Files/Democracy 4).

Important note:
- In the current alpha version modding isn't fully supported.
- Modding may change entirely (loaded from Documents/democracy4).

You may need to delete the following files and folders from your Program Files/Democracy 4 folder in later versions to work correctly:
- data\mods\ireland.txt
- data\svg\map_ireland.svg
- Ireland
- translations\English\missions\ireland.txt

References and sources of information:
- data\svg\map_ireland.svg - https://commons.wikimedia.org/wiki/Category:SVG_maps_of_Ireland#/media/File:Ireland_stub,_noflag.svg
- Ireland\data\bitmaps\flag_ireland.png - https://upload.wikimedia.org/wikipedia/commons/1/13/Ireland_flag_300.png (resized and cropped into a circle shape)
- translations\English\missions\ireland.txt:
  - description - adapted from paragraph 1 of https://en.wikipedia.org/wiki/Republic_of_Ireland
  - population, size - https://en.wikipedia.org/wiki/Republic_of_Ireland
  - ethnicity, religion - adapted from https://en.wikipedia.org/wiki/Republic_of_Ireland (in some cases I combined groups to fit everything on a single line)
  - Main Export Partners - https://en.wikipedia.org/wiki/Economy_of_the_Republic_of_Ireland
  - tourism - https://en.wikipedia.org/wiki/Tourism_in_the_Republic_of_Ireland
- Ireland\data\missions\ireland\ireland.txt:
  - max_gdp - https://en.wikipedia.org/wiki/Economy_of_the_Republic_of_Ireland
  - fx_rate_to_pound - https://www.xe.com/currencyconverter/convert/?Amount=1&From=GBP&To=EUR
  - starting_debt - https://en.wikipedia.org/wiki/Economy_of_the_Republic_of_Ireland
- Ireland\data\names\irishnames_1981.txt and Ireland\data\names\irishnames_2019.txt
  - Surnames from https://www.irelandbeforeyoudie.com/top-100-irish-surnames-last-names-family-names-ranked/ (English versions only)
  - First names from https://www.cso.ie/en/interactivezone/visualisationtools/babynamesofireland/

Notes:
- I tried to maintain the fadas (diacritic marks / right-slanting lines placed over some vowels) in Irish words and names where possible.
  - I used Notepad++ to edit the configuration files. Encoding files as UTF-8 allows D4 to render the fadas correctly.
- There are 2 versions of the irish names files irishnames_1981.txt and irishnames_2019.txt.
  - irishnames_1981.txt has names registered in 1981 - more traditional Irish names, but no fadas (the CSO only started using fadas in 2018.)
  - irishnames_2019.txt has names registered in 2019 - more modern & foreign names, but traditional Irish names have fadas.
  - The config file Ireland\data\missions\ireland\ireland.txt points to irishnames_1981.txt. Change it to point to irishnames_2019.txt if you want fadas.