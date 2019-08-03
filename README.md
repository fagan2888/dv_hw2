# dv_hw2
holding code and viz related files
https://bl.ocks.org/vvt221/7cfa475e697bd838b6bec37e61913d37

## Objective:
Visualize the path of any NYC bus diplaying the route, its stops and the location of buses obtained from the realtime GTFS data.
Here, I am primarily looking at the B82 bus.

## Data Collection:

### 1. Static gtfs data collection:
This part involves collecting the coordinates of the stops associated with a particular route and generating the corresponding json file which stores the coordinates sequentially.

### 2. Realtime gtfs parsing
We make use of the MTA API to retrieve the realtime gtfs feed showing the postion of buses. This GTFS feed is then parsed to make it more readable and then converted to csv files.
We then generate the json files containg the reatime position of the buses.


The above two json files are then used to plot the final visualization which can be accessed here:
https://bl.ocks.org/vvt221/7cfa475e697bd838b6bec37e61913d37




