# TESTING

----

### outline
1. static site overview
2. web dev basics
3. design
4. wdi website (pelican)

----

## Static Sites

----

- Explain: Stories + static visualization
- Explore: Interactive visualization/dashboard

----

### Steps
1. wrangle data
2. format data for visualizations
3. generate visualizations
4. create website

----

### folder structure
![folders](./assets/folder_structure.PNG)

----

### Wrangle data

----

## Website
- the Loop
- images
- tracking code

----

## HTML & CSS Demo
https://codepen.io/freeCodeCamp/pen/NNvBQW
bootstrap: https://codepen.io/freeCodeCamp/pen/mJNqQj

----
### testing

```HTML
<body>
  <p>are you working?</p>
</body>
```
----

### Tracking Code
Review more from their guidelines PowerPoint, basic implementation is below
```javascript
var wbgData = wbgData || {};
wbgData.page = {
  pageInfo: {
      pageName: "en:wdi:home", //clean, descriptive, unique page name
      pageCategory: "home", //home, content page, list
      contentType: "Homepage", //About, Homepage, Stories, Topic, Other
      channel: "DEC waw EXT" //DEC(vpu/gp) site name EXT
    }
},
wbgData.site = {
  siteInfo: {
      siteLanguage: "en", //use ISO-2
      siteType: "waw", //site's sub-domain
      siteEnv: "prod" //prod (for production), qa
  },
  techInfo: {
      cmsType: "sharepoint", //sharepoint, aem, drupal, etc.
      bussVPUnit: "dec",
      bussUnit: "decdg",
      bussUserGroup: "external", // internal or external site
      bussAgency: "ibrd"
  }
}
```
----
### Tracking Code (cont.)
1. wrap the implementation from the previous slide into a `<script>` tag

2. include linked javascript in `<head>`

<!-- <pre><code class="hljs">
<script src="//assets.adobedtm.com/572ee9d70241b5c796ae15c773eaaee4365408ec/satelliteLib-efd6120a6f6ed94da49cf49e2ba626ac110c7e3c-staging.js"></script>

<script src="//assets.adobedtm.com/572ee9d70241b5c796ae15c773eaaee4365408ec/satelliteLib-efd6120a6f6ed94da49cf49e2ba626ac110c7e3c.js"></script>
</code></pre> -->

3. add the html below after the `<footer>`
```html
<script type="text/javascript">
  _satellite.pageBottom();
</script>
```



----

# Links
### Here's a link to [a website](http://foo.bar).
