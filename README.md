#

# Project III - GEOSPATIAL-DATA
## Choosing best location for a new office
### By: Gaspar Masdeu
### Date: August 1st 2022

#

![image info](./pictures/portada.jpg)

#
## Initial conditions:
#

The goal is to place the new company offices in the best place for the company to grow. You have to find a place that more or less covers all the following requirements (note that it's impossible to cover all requirements, so you have to prioritize at your glance):

    Designers like to go to design talks and share knowledge., There must be some nearby companies that also do design.

    30% of the company staff have at least 1 child.

    Developers like to be near successful tech startups that have raised at least 1 Million dollars.

    Executives like Starbucks A LOT. Ensure there's a starbucks not too far.

    Account managers need to travel a lot.

    Everyone in the company is between 25 and 40, give them some place to go party.

    The CEO is vegan.

    If you want to make the maintenance guy happy, a basketball stadium must be around 10 Km.

    The office dog—"Dobby" needs a hairdresser every month. Ensure there's one not too far away.

#
## Where to Search?
#

We have an initial database with the latitudes and longitudes of the largest tech companies in the world. From those longitudes and latitudes, I can launch various geoquerys to the Foursquare API to get information about each location. 

## Querys:

In the queries folder we have the code about each query, and how I store the extracted data. I use both a csv file and MongoDB to organize the data and then be able to draw conclusions.


## Results:

By analyzing the response of each geoquery, we obtain information about those things and places that interest us and we can determine the distance between the possible location of our company and, for example, the nearest Starbucks. 

We end up with about 100 locations on which we can build our company, all over the world.  To find the best of those 100, we will get the total distance between each location and each service the company is interested in: the design firms, the schools, the vegan restaurant... All these distances will add up to a total distance, and the smallest of the remaining 100 locations will be our ideal location.

You have the results in the time_to_plot file.

