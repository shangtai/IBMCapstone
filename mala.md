# Introduction/ Business Problem

Singapore is a multi-cultural city in the South East Asia. Dishes from all over the world can be found in the city state. Furthermore, it is the country which has nominated the hawker culture in the country on the [UNESCO Representative List of the Intangible Cultural Heritage of Humanity]( https://www.straitstimes.com/singapore/singapore-submits-unesco-bid-to-recognise-hawker-culture). It is highly competitive to survive the food industry in this country.

One particular dish that attracted my attention is a dish called [Mala Xiang Guo]( https://en.wikipedia.org/wiki/Ma_la_xiang_guo). This dish originated from China and now it is gaining popularity lately. 

In my humble opinion, this is quite a unique dish. Usually this dish is not eaten alone. Rather it is eaten with a group of friends. It is not just a typical food; it is a social activity.  

My audience would be potential businesspeople who intend to join in such a venture, to investigate the current locations of Mala Xiang Guo stalls in Singapore and their rating. From the analysis using FourSquare, we hope to analyze possible new locations to set up a new stall. As mentioned earlier, surviving the food sector in Singapore is not an easy task and careful planning would be desirable.


# Data

Most Singaporeans travel by a fantastic train system known as Mass Rapid Transit. I am going to use the stations name to search for suitable existing stalls. The stations names can be found on the Wikipedia page [here]( https://en.wikipedia.org/wiki/List_of_Singapore_MRT_stations_by_planning_area). I can then use Geopy to get the geological location.

I will experiment with various radius to find stalls and possible locations that can be suitable for us to set up the business locations using the Foursquare API.
