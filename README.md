# Urban-Data-Mapping-Class
Class assignments and participation

For this assignment, I had issues filtering out the data 
not realising I could filter using 'containing noise' as opposed to 'is noise'
The next issue was uploading the 311 data as a delimited text with geometry points
 of latitude and longitude. After these issues were resolved, the rest of the assignment 
 was about following the instructions and choosing the path of visualizing the data.
 
 The first image below shows the point representation: 311 complaints by descriptor
 using the categorised feature under symbology.
 ![](assignment2images/311%20points%20categorised.png)
 
 The second image shows a graduated map of Manhattan with labels of the count of complaints per NTA code division.
 ![](assignment2images/graduated%20map%20with%20number%20of%20noise%20complaints.png)
 
 The final image shows the map of my data (or a combination or 1 or more of the analyses).
 Using the NTA population data (combining it with the initial map using 
 Processing tools -> vector table -> join using field values -> nta code
 
 Next was to use the field calculator to calculate the population density per nta code area.
 Next, I created a graduated map of 6 classes showing population density along with labels of the population.
![](assignment2images/graduated%20pop_density%20with%20population%20labels.png)

Upon analysing the data, there seems to be a correlation in terms of higher noise complaints with places with higher population density.
