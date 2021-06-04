# Visualize cafes on map with Folium

Cafes are very common in Korea, and many of them are franchise business. In this excercise I will visualize one of the franchise, Coffee Bean, with around 240 shops on the map.

Find the codes and graphs here:
https://nbviewer.jupyter.org/github/chanchanngann/cafe_map/blob/master/coffeebean.ipynb


## Competitors in the neighborhood

Hypothesis: high competition may not be advantageous to Coffee Bean but moderate competitions indicate the coffee demand in the district. Areas with median number of cafes would be good choice of location.

I try to visualize other cafes in the neighborhood for a better idea.

![](https://github.com/chanchanngann/cafe_map/blob/master/image/02_cafe_competitors.PNG)

For example, there is high cafe density in 서대문구 including coffee bean. 


## Conclusion
In this notebook, I visualized the franchise cafe Coffee Bean on the map using folium. By adding district line and other cafes on the same map, we get a better idea of the cafe competitions in the neighborwood. Obviously, there would be more cafes in the commercial area. I tried to hypothesize the target audience of franchise cafe and the project might be continued by validating the hypotheses with more data. Ultimately, we would be able to score the districts using K-means clustering model and aim to find out the best strategic locations for the franchise cafe.
