# school_milk_ohio

Professor Robert Porter graciously provided the Ohio School Milk bidding data that was used for this analysis (https://economics.northwestern.edu/people/directory/robert-porter.html). Professor Porter provided All.doc, milk_cleaned.cvs, and the DISTRICT.PRN file, which was used to infer locations of the school districts.

The ohio_milk_data.csv file came from Johannes Wachs and Janos Kertesz's paper A network approach to cartel detection in public auction markets (https://www.nature.com/articles/s41598-019-47198-1).

The District_Dairy_Distances.xlsx file was created see how distance affected the bid amounts. I use the District.PRN file to find coordinates for the school districts. The school district locations give a general approximation of the location of the district, as there many schools within each district (some were more spread out than others). About 2/3rds of the school district's coordinates were added manually, in which I typically used the High School as the primary location. 

Milk Processor/Firm locations were much trickier since the data is from the 80s and many of the businesses no longer exist. I primarily used the corporation lookup on state websites to find corporate addresses. This does not take into account multiple locations, which is likely for many of the large milk processors. A few of the firms were also just distributors and not processors, so it is unlikely that their corporate address is the same as the plant/fulfillment center.
