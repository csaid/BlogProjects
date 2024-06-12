# Laboratory acquired infections
This repo contains a copy of the [ABSA Laboratory-Acquired Infection Database](https://my.absa.org/LAI), a somewhat cleaner version, and the code used to clean it. It was used in my [map of laboratory-acquired infections](https://chris-said.io/2022/11/01/map-of-laboratory-acquired-infections/) blog post.

* `Data cleaner and map.ipynb` - code used to clean the data and display it on a Plotly map
* `raw_data.txt` - a copy/paste of the two pages on the ABSA page
* `cleaned_data.xlsx` - cleaned data (mostly just some typo corrections and simplifications)
* `for_map.xlsx` - Like the cleaned dataset but with a few rows removed where the location of the event is unknown or underspecified.
