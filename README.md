# NRTLCTS
# Near Real Time Landscape Change Monitoring
 This guide provides step-by-step instructions on how to use the LCTS interface to track landuse/landcover of Bale and West Arsi ecoregions of Ethiopia. It visualizes forest cover, the changes in landuse and forest. It allows users to explore the geographical distribution of stable forest areas, newly gained forest areas, forest areas that have been lost, and areas that have remained non-forest. 
## The Landscape Change Tracking System User Manual thus consists three interlinked sub-applications of the system yet can be visualized independently viz:
```
 1.	Forest Cover explorer
 2.	Forest Cover Change Explorer
 3.	Landscape Change Explorer
```
The guide also includes instructions for selecting specific zones or districts/woredas and accessing summary statistics for those areas. Overall, this guide is useful for anyone interested in studying and understanding forest cover changes in the selected ecoregions of Bale and West Arsi areas.
# Forest Cover Explorer
This application provides a visualization of forest cover in Bale and Arsi landscapes. It displays the geographical distribution of forest areas and the respective forest cover by year in each landscape based on Sentinel-satellite images of 10m spatial resolution as produced by ESRI.
To open the Forest Cover Explorer, 
Navigate to [https://oytisa.users.earthengine.app/view/forestcover](url)
 Click **"Select Zone"**. 
 Click **"Bale"** for example in the dropdown list.

 ![image](https://github.com/oytisa/NRTLCTS/assets/25427373/165e4547-16fd-47f0-b67e-b59f04338691)

Now the application visualizes the forest cover in Bale. 
### Forest Cover Summary Statistics
It displays the geographical distribution of forest areas and the respective forest cover by year in the selected Bale ecoregion based on Sentinel-satellite images of 10m spatial resolution as produced by ESRI.

 
 Click on **"Select District"** to select the district/woreda of your interest. 

 ![image](https://github.com/oytisa/NRTLCTS/assets/25427373/81f07b03-5592-4913-b1d4-f251902d5b80)

Now it visualizes the extent of the selected woreda in white polygon, the corresponding forest cover and summary statistics as shown below.

  ![image](https://github.com/oytisa/NRTLCTS/assets/25427373/e3df735d-ebff-4827-b9d2-31f9184f5f28)

Now let’s change the woreda of interest
 Click **"Mena"** to visualize forest cover of Mena woreda and cover statistics.


![image](https://github.com/oytisa/NRTLCTS/assets/25427373/6ae62c7d-96e1-41ef-a2b8-e487f8c3992e)


# Forest Cover Change
This application provides a visualization of the changes in selected ecoregions forest cover. It displays the geographical distribution of stable forest areas, newly gained forest areas, forest areas that have been lost, and areas that have remained non-forest.Based on the 2015 Ethiopia  new forest definition (MEF 2015) a forest is 'Land spanning more than 0.5 ha covered by trees (including bamboo) (with a minimum width of 20m or not more than two‐thirds of its length) attaining a height of more than 2m and a canopy cover of more than 20% or trees with the potential to reach these thresholds in situ in due course. The PROCESSES OF CHANGE DETECTION adopted followed the Ethiopian FRL types of land use changes; non-forest land use change to forest as gain, and forest land use change to the non-forest land use as loss.

 - Click **"Forest Cover Change"** or copy this link [https://oytisa.users.earthengine.app/view/ffnf](url) and paste to browser tab
 
- Click **"Select zone"**
 
- Click **"Mirab Arsi"**
 
- Or Click **"Bale"**. 
 
 It will now compute the forest change for the selected ecoregion and display the map
 See the **Summary Statistics Chart** to the right. 
 In the figure below “Bale” ecoregion was selected showing its extent and districts represented with white polygons. The change shows the following categories
```
- Stable forest (FF)
- Lost forest (FNF)
- Gained forest (NFF)
- Stable non-forest (NFNF)

```
This is depicted in the graph as per the IPCC guidelines for biomass invetory in the AFOLU sector in the following nomenclature as shown in the consequent figure;
- **F->F** = Forest land remaining Forestland
- **F->NF** = forestland converted to Non-forest land
- **NF->F** = Non-forest land converted to forestland
- **NF->NF** = Non-forest land remaining Non-forest land
 The figure below shows forest cover convertions from 2017 to 2022 when Bale ecoregion is selected.
 ![ee-chart](https://github.com/oytisa/NRTLCTS/assets/25427373/db34f719-a432-4018-9774-410d3977f134)

 Switch to tab **"Earth Engine Chart"** to enlarge the graph
 
 Click **"Select District"**
 
 Click **"Harena Buluk"**
 ![image](https://github.com/oytisa/NRTLCTS/assets/25427373/21168c0e-aac1-48cd-aa76-0b35b1d25602)

Now it will display the forest cover change map and statistics of Harena Buluq district
 
 Switch to tab "Earth Engine Chart" to enlarge the summary statistics graph
![image](https://github.com/oytisa/NRTLCTS/assets/25427373/62e7db33-df43-40a8-9b46-a3ab727449e7)
 
# Forest Cover
Click "Forest Cover"
or use the link  [https://oytisa.users.earthengine.app/view/forestcover ](url)

# Landscape Change Explorer

 Click "Land Cover Change (LCTS)" or click this link [https://oytisa.users.earthengine.app/view/forestcover ](url)
 ```
Select zone/district
Select "2017" as initial year
Click "2024" as final year
Now Click "Show Changes"
Click "Grass"
```

## user defined area of monitoring
 User can monitor the landcover and landcover change probabilities * at a point along line or within a polygon* drawn.
Click draw to draw 
 
![image](https://github.com/oytisa/NRTLCTS/assets/25427373/5aa6eb86-38a0-4c4e-8f39-379496d9eb8d)

Click "Clear drawing"

![image](https://github.com/oytisa/NRTLCTS/assets/25427373/ed44f22d-a4d7-4510-bd5e-16d9141c79d4)
