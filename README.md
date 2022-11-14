# bike_routing
Finding the best bike route by avoiding accident hotspots in Hamburg


General idea:
- use web scraping (https://stackoverflow.com/questions/44187490/downloading-files-from-a-website-using-python) to download accident info from https://unfallatlas.statistikportal.de/_opendata2022.html 

- use openstreetmaps to find optimal route and avoiding high accident zones (https://medium.com/@nilufarmohammadi1/find-the-best-route-with-openstreetmap-using-python-da70eff5b1ac) 

- add some kind of risk factor rating for top 3 routes, or speed vs risk factor

- how to make it focus on paths, not streets?