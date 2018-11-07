## the loop

----

### wbg style guide
<http://pubdocs.worldbank.org/en/754991511203317714/WBG-VIG-20171114.pdf>

----

### typeface
demo_type_face.html

<iframe src="demos/demo_type_face.html" width="800" height="500"></iframe>

----

### jumbotron
demo_jumbotron.html

<iframe src="demos/demo_jumbotron.html" width="800" height="500"></iframe>

----

### cards
demo_card.html\
<iframe src="demos/demo_card.html" width="800" height="500"></iframe>

----

### rows
demo_full_row.html

<iframe src="demos/demo_full_row.html" width="800" height="500"></iframe>

----

### tracking

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
