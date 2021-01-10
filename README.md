# Seattle-AirBnB

## Motivation

This project is to do a brief data exploration on Seattle's AirBnB data. I will analyze the how the listings are distributed across different neighborhoods of Seattle, what are their features and how does the price vary across neighborhoods and time. Following questions are answered in the analysis-

1. What are the popular neighborhoods of Seattle Airbnb listings?
2. What type of listings are popular in these neighborhoods?
3. What's the average price per listing across neighborhoods?
4. Is there a relation between the Airbnb availability and price or minimum number of nights to stay?
5. How does the average price per listing across neighborhoods vary across the year?

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

Python: 3.7.1

Packages: os, folium, pandas, numpy, datetime, matplotlib.pyplot, seaborn


### Installing

You can install python from this [link](https://www.python.org/downloads/release/python-371/).

Packages can be installed using the 'requirements.txt' that is available in the repository.

```python
pip install -r requirements.txt
```

### Files used:
The analysis is present in the jupyter notebook - 'Analysis of AirBnB homes of Seattle.ipynb'. This takes input of 3 files-

* Listings, including full descriptions and average review score
* Reviews, including unique id for each reviewer and detailed comments
* Calendar, including listing id and the price and availability for that day

Data is also available [here](http://insideairbnb.com/get-the-data.html)

### Summary

1. Nearly 40% of all listings are located in Capitol Hill, Central Area, and Downtown neighborhoods. These are the popular areas of AirBnB listings in Seattle.
2. ‘Entire Home/Apt’ are the most abundant type of listings available. Downtown consists mainly of such apartments.
3. Prices of listings across popular neighborhoods like Downtown, Central Area, and Capitol Hill are similar. But Magnolia is the most expensive neighborhood where the average price per night for an entire apartment is about 250 dollars.
4. The higher the price of the listing, the higher are the number of days available to book. There seems to be a correlation between the number of days available to book and the price of the listing.
5. Most of the neighborhoods saw a price surge during summer and it was quite significant for downtown neighborhood where the peak price increase was 44%.

The analysis is summarized in this blog [post](https://suhaskaranth2008.medium.com/seattle-airbnb-data-a-brief-data-exploration-b68fb891952e).

## Licensing, Authors, Acknowledgements

The data was made available by AirBnB and you can view the licensing and further information about the data [here](http://insideairbnb.com/get-the-data.html). I have to acknowledge Stackoverflow community as they rescued me from the errors and bugs faced during the analysis.

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Senrique/Seattle-AirBnB/blob/main/LICENSE) file for details

Please feel free to use my code for your purposes.
