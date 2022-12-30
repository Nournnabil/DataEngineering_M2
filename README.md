# DataEngineerinM2
--Description of the newly added dataset:
we've used the merge function to integrate the airlines and flights datasets using the left on-Right on join with the left join on IATA_CODE from airlines and the right join on AIRLINE from flights, to be able to specify columns to join on as the names of the columns are repeated in the 2 datasets but with different data types and values so, merging using the merge wouldn't work in this case, then we've joined the resulted dataframe with the airports dataset using the left on-Right on join with the left join on IATA_CODE from airports and the right join on DESTINATION_AIRPORT from the previously resulted Dataset, The result of these joins is our Main Dataset that is going to be used throughout the project.


--Description of the added features.
we've added "Hour" feature representing the hours of the day that will help us in knowing some statistics that will lead us to answer our research questions, also we've added feature called the "Percentage_per_hour" representing the percentage of delay in flights through the hours of the day so that we can visualize it against different features and gain different insights and finally we've added feature called the "Percentage_Per_Month" representing the percentage of delay in flights through the Months of the year so that we can visualize it against different features and gain different insights.


