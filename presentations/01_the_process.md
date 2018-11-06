
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

### 1. wrangle data

* use iso3c and economies (beware of using country name)
  - fyi, countrycode package does not use Bank economy names

----

### 2. format data for visualizations

* code should read from output of initial data cleaning
* data should be in long format for Tableau and ggplot
* check for economy name accents, etc.

----

### 3. generate visualizations

* [wbgviz](https://github.com/worldbank/wbgviz) has functions to create different charts
  - `wbg_choropleth()`for maps
  - FYI: use pdf output until bug is fixed
* examples in the [sdgatlas](https://github.com/worldbank/sdgatlas2018) repo
* tableau access

----

### 4. create website

* remember to include analytics code
  - qa and production have different analytics codes
