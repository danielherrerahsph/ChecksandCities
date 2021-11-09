# ChecksandCities
A salary comparison dashboard


## Collect Data
The cost of living data for this dashboard was collected using webscraping with the 'rvest' and 'httr' packages within R. This data was then cleaned and will be utilized within the shiny app. The data can be found as colcity_data.csv.
The wages data for this dashboard was collected from the Bureau of Labor Statistics (BLS) for 50 cities in the United States. This data were lightly cleaned and are found as wages_norepeats.csv. 

Both of these datasets are found within the folder for the shiny app, so they will be found when implementing the shiny app. 

## Shiny App
The dashboard created uses various tabs to guide users towards making a smarter decision with salary information. The following tabs were created:
1) General Salary by City
2) General Salary by Occupation
3) Offer Comparison

### General Salary by City
The 'General Salary by City' tab offers information for the mean salary within certain states. This data uses estimates from the BLS dataset. 

### General Salary by Occupation
The 'General Salary by Occupation' tab plots the mean salary for the occupation of choice across the 50 cities. This is useful to assess which cities offer more competitive salaries for the desired occupation. 

### Offer Comparison
The 'Offer Comparison' tab is useful for comparing salary offers across two cities. Plots included are: 
1) the average price of a one bedroom apartment in the city center of interest for offer one
2) the average monthly salary for your inputted offer
3) the average monthly surplus (2-1) after accounting for cost of living, which for now is limited to one bedroom apartment cost. 
