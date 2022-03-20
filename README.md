# PyBer_Analysis
An analysis of ride sharing data by city type. 

**Overview**

This analysis was completed utilizing Python skills and knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type. Then using Pandas and Maplotlib, a multiple-line graph shows the total weekly fares for each city type. Laslty, a written report was complete to summarize how the data differs by city type and how those differences can be used by decision=makers at PyBer. 

**Results**

Using the Pandas groupby() function, count() function, and sum() function methods on PyBer, we were able to get the "Total Rides", "Total Drivers", and "Total Fares". Further data analysis also gives the average fare per ride and "Average Fare per Driver". 

<img width="648" alt="PyBer Summary" src="https://user-images.githubusercontent.com/99268646/159078523-e14112f9-79cd-448a-aa32-4ab70cbe70b8.png">

To graph these results, the object-oriented interface method, the df.plot method, and the the Matplotlib "fivethirtyeight" graph style were used.

<img width="653" alt="Total Fares by City Type" src="https://user-images.githubusercontent.com/99268646/159079695-5ca86434-9436-49eb-b5af-6152ca835948.png">

<img width="647" alt="PyBer Ride-Sharing Data" src="https://user-images.githubusercontent.com/99268646/159167536-33057c6d-8922-4f31-a902-ca9641a1d78b.png">


**Summary**

In summary, when looking at the graphs and charts created in the analysis, Urban settings over the year 2019, are much more common areas to use PyBer Ride Sharing compared to Suburban areas and Rural areas. Because of this, business recommendations using the "Growth Share Matrix" can be generated: 


<img width="574" alt="Growth Matrix" src="https://user-images.githubusercontent.com/99268646/159168625-93a97873-4705-4588-bebc-bd5fa2ac634f.png">


*   Urban Areas (Recommendation 1):  
    *    The first recommendation is to focus on maintaining the largest sector of PyBer income, the Urban areas. By definition, Urban areas are more densely populated areas of many people allowing for ride sharing to convenient and often times the preferred method of transportation. It makes sense for these areas to create the largest source of income for PyBer. These areas should be viewed as "Stars". These settings have "high-growth" and "high-share" values meaning companies should significantly invest because they have high future potential. 
*   Sub-urban Areas (Recommendation 2):
    *    The second recommendation is to "watch" opportunities in Suburban areas. Suburaban areas are viewed as "Question Marks" meaning they have "high-growth" and "low-share" value. In these instances, companies should invest or discard depending on the liklihood of these areas becomming "Stars". For example, in Ohio (and all over the country) there are some sub-urban areas that are gowing rapidly and others that are declining with people moving in or out. So after analysis to review those sub-urban areas that are growing rapidly PyBer should invest and other sub-urban areas that are declining PyBer should discard their resources. 
*   Rural Areas (Recommendation 3): 
    *    The third recommendation is to divest the lack of opportunity in Rural areas. Again by definition, rural areas are areas of low population density with the majority of the population living distinct distances from one another and ride sharing is not convenient or a preferred method of transportation. Rural areas are viewed as "Pets" they have "low-share" and "low-growth" value and it is recommended to liquidate or divest in areas like this. The resources and money spent in rural areas could be used to better grow the company in Urban or Sub-urban areas. 
    

<img width="253" alt="Total Fares by City Type" src="https://user-images.githubusercontent.com/99268646/159169095-579c0420-36a4-4f0e-a08d-00d1583cd7ef.png">


<img width="251" alt="Total Rides by City Type" src="https://user-images.githubusercontent.com/99268646/159169105-f22b2d58-c702-4d4e-9dc1-325e42146eb1.png">


<img width="265" alt="Total Drivers by City Type" src="https://user-images.githubusercontent.com/99268646/159169108-ecf69c27-3dbd-420a-9377-88d1ae26675e.png">

