# DataScience_Capstone

# Udacity_Capstone
This is my capstone project for my Udacity DataScience Course.

 # Predicting best location for Halal Restaurant
### Motivation: 
   Halal is an Arabic word meaning lawful or permitted. In
reference to food, it is the dietary standard, as prescribed in the Qur’an (the
Muslim scripture).since most countries have at least a small Muslim
community it would definitely be smart to have halal options on the menu
in order to draw this specific group of customers. Restaurateurs are starting
to realize that catering to the demand of Halal food advantageous to all. To
be more competitive in the food industry it is important to be aware of the
new trends and innovations in the industry.

### Data Description: 
   My client is planning to open a halal restaurant in 
Virginia, and assuming that they will rent a place. We will look at the rent
dataset from (https://www.zillow.com/research/data/) according to
neighborhood, so that it's easy for us to check the rent data neighborhood
wise. I am using only the narrowed down information that I could source
from the website. I have cleaned the dataset. The data set can be found in my repository here Neighborhoods_VA.csv. 
The formula I will be using will tell us which neighborhood is good to open a new halal restaurant. 

### Libraries used:
Pandas
Numpy
bs4 Beautiful Soup
geopy Nominatim
os
Folium
requests
matplotlib.pyplot 
matplotlib.cm 
matplotlib.colors
matplotlib 
re
csv
%matplotlib inline

### Methodology: 
   Narrowing down aspects to compare and consider not all
restaurants are always running business at high peaks because times and
peoples tastes are forever changing. For this reason we will only be looking
at the most recent data. Keeping this trail of thought in mind we will
compare restaurant ratings. This way we can be sure opening another halal
restaurant in the same area will be benificial to us or not. Because if too
many halal restaurants in the area have good ratings already it will be
harder for us to attract customers to us. Since I have average rent data of a
specific area in my data set we will find the longitude and latitude values of
our neighborhoods and join them to our dataset in or table. I then assign
rentScore to data by figuring out rent from maximum to minimum. This
will make it easier for us to compare. Then add a column of rentScore to the
table. Calling foursquare I then sourced all Halal Restaurants only for our
comparison. Then create another table displaying restaurants and their
ratings. Then calculate ratingScore by pulling ratings from maximum to
minimum. And lastly we compare both rent and rating factors for all halal
restaurants in a neighborhood to get our final score and decide which area
is best for us to open a halal restaurant.

### Results: 
   Our answer shows the stakeholder which neighborhood is best
to open a halal restaurant by comparing rent and ratings of only halal
restaurants in the area. It shows which area is best and upto which area is
probably the worst for such a business. These areas either don’t have a halal
restaurant in them at all or the ones they have are rated very low.

### Discussion: 
   One big issue that comes to mind while looking at or results
and process is, the neighborhoods shown with no halal restaurant in them
could might as well not have a large muslim population to attract. Moreover
they could have no muslims living in them at all. However this issue can
easliy be solved by sourcing more data on neighborhoods with large muslim
populations.

### Conclusion: 
   In conclusion we have at least figured out best location for
halal restaurant(which was the initial question of our client) with the
information provided and can proudly say we have a basic template laid out
for ourselves to get an in depth answer provided we get more data of our
benefit to work with.


### Acknowledgements:

I sourced my code from publicly available data from https://www.zillow.com/research/data/.
I was able to get venue and rating information from https://developer.foursquare.com/
