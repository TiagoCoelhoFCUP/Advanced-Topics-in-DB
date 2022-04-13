# Advanced-Topics-in-DB
Projects developed under the Advanced topics in Databases college chair during the 2019/2020 school year


## Simulation of Covid-19 contagion in Portugal's taxi network 

In this project we were given the spacial data about the tracks of every individual taxi in Portugal on the 10th of October 2019 as well as geometric data about the country and its municipalities/counties and we were asked to simulate and animate the contagion of the Covid-19 pandemic given that we start with 2 randomly selected taxis, one in Porto and one in Lisbon. The more time taxis interact with an infected taxi (the more time they spend within 50m of eachother), the more likely they are to get infected, with a probability of infection for each interaction of 0.01826.

The geometric data was provided to us as a postgresql database and the python code present in the repository makes queries to the specific tables within that database.
The final result of this project is an animation that allows us to better visualize the spread of the disease:

https://user-images.githubusercontent.com/13381706/163206859-f0ed62d0-cf4d-4628-a390-dcd9c0875d14.mp4

