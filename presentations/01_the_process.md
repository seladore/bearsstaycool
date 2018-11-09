
## static site process

----

* Explain: Stories + static visualization
* Explore: Interactive visualization/dashboard

----

### steps

1. wrangle data
2. format data for visualizations
3. generate visualizations
4. create website

----

### folder structure
![folders](./assets/folder_structure.PNG)

----

### junk drawer

* use iso3c and economies (not "countries")
  - fyi, countrycode package does not use Bank economy names
* data should be in long format for Tableau and ggplot
* code should read from output of initial data cleaning for additional formatting scripts
* you can use wbgviz to build visualizations
  - `wbg_choropleth()`for maps, FYI: use pdf output until bug is fixed
  - examples in the [sdgatlas](https://github.com/worldbank/sdgatlas2018) repo
* remember to include analytics code
