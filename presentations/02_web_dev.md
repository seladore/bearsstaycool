
## Web Dev Basics

----

### Website
- the Loop (HTML + CSS)
- images
- tracking code

----

### HTML Structure

----

### CSS Structure

----

### HTML & CSS Demo
<https://codepen.io/freeCodeCamp/pen/NNvBQW>

----

### Bootstrap Demo
<https://codepen.io/freeCodeCamp/pen/mJNqQj>

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
