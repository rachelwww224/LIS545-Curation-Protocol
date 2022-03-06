

# LIS545 Curation Protocol
 
The dataset is created to address the homelessness issues in Seattle and other surrounding counties in Washington state. The data covers the annual count of homelessness across regions in Washington state from 2017 to 2020. The targeted audiences are researchers and policymakers. The data is freely available to the public and available in .csv format. 

•	**Potential Data Quality Issues**: The unsheltered homelessness was counted using the “point-in count” method, which uses the day/night of a specific date as an estimation of the actual homelessness situation for that year. Many factors will affect the data accuracy and make the count fluctuate, including the number of volunteers, weather conditions, funding, etc. Please be mindful of the potential data quality issues and use this data with caution. 

•	**Naming Conventions**: 
⁃	No spaces or special symbols for file or variable names, except for underscores or hyphens. 
⁃	The file should be named
“WA_homelessness_cnt_startyear_to_endyear_datatype,” where the start year is the minimum year and the end year is the maximum year in the dataset. Datatype is the type of the numeric columns, being raw or normalized. For instance, the dataset can be named “WA_homelessness_cnt_2017_to_2020_raw”. 


• **Data Normalization**: The data are available in two files, one raw and one normalized. In the normalized dataset, the homelessness count has been normalized to a mean of 0 and a standard deviation of 1. I used the STANDARDIZE function in Excel for normalization.  The normalized dataset helps the researchers and policymakers to use it directly in performing further analysis where normalization is needed. 

•	**Data Dictionary**


| Variable |  Variable Label |  Variable Type | Allow Values|  Description |
| :-------- | :------------- | :------------- | :----------- | :----------- |
|Region   |  Region       | String        | East County, | The regions in Washington State.* |
|         |               |               | North County,  |               | |         |               |               | Northeast County,|          
|         |               |               | Seattle,         |              |
|         |               |               | Southeast County,|              |
|         |               |               | Southwest County |              |
|Year     |Year           |String         | 2017-2020        | The Year.    |
|Type     |Homelessness_Type|String       |sheltered, unsheltered |The type of homelessness.|
|Count    |Homelessness Count|Integer     |>=0              |The number of homelessness. |
                                                            

*Notes: 

**Southwest County** (Algona, Auburn, Burien, Des Moines, Federal Way, Kent, Milton, Normandy Park, Pacific, Renton, SeaTac, Tukwila, Vashon Island)

**East County** (Beaux Arts Village, Bellevue, Clyde Hill, Hunts Point, Issaquah, Kirkland, Medina, Mercer Island, Newcastle, Redmond Sammamish, Yarrow Point)

**Northeast County** (Carnation, Duvall, North Bend, Skykomish, Snoqualmie)

**North County** (Bothell, Kenmore, Lake Forest Park,  Shoreline,  Woodinville)

**Southeast County** (Black Diamond, Covington,  Enumclaw, Maple Valley)

**Seattle**
 

