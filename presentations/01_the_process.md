
## static site process

----

* Explain: Stories + static visualization
* Explore: Interactive visualization/dashboard

----

### components

* data
* visualizations
* website

----

### folder structure
![folders](./assets/folder_structure.PNG)


----

### data
* code should read from output of initial data cleaning for additional formatting scripts
* use iso3c and economies (not "countries")
  - fyi, countrycode package does not use Bank economy names

----

### visualizations
* data should be in long format for Tableau and ggplot
* you can use the wbgviz R package to build visualizations
  - `wbg_choropleth()`for maps, FYI: use pdf output until bug is fixed
  - examples in the [sdgatlas](https://github.com/worldbank/sdgatlas2018) repo

----

### tableau
* requires a license
* fairly straightforward to use, lots of youtube tutorials and tableau community forums
* easily gets you 90% of the way, the other 10% requires a little patience
* make sure to export workbooks with the extracted data
* highly recommend having a versioning system for data and dashboard iterations

----

#### dashboard
establish dimensions of dashboard using website parameters (height and width)

![dashboard dimensions](https://onlinehelp.tableau.com/current/pro/desktop/en-us/Img/dashboard_resize1.png)

----

#### story
establish dimensions of dashboard using website parameters (height and width)

![story dimensions](https://onlinehelp.tableau.com/current/pro/desktop/en-us/Img/story_first_point.png)
