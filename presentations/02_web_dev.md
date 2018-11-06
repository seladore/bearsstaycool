
## web dev basics

----

### building blocks
* HTML
  - tracking code
  - images
* CSS (the loop)

----

### html structure
_element, tags, attributes, name, value_
```html
<element name="value"></element>
<h1>My First Heading</h1>
<p class="headers">My first paragraph.</p>
<p id="main-header">My first paragraph.</p>
```

----

### css structure
_selector, declaration, property, value_
```css
selector {
  property: "value";
}
h1 {
    text-align: center;
    color: red;
}

.headers {
    text-align: center;
    color: red;
}

#main-header {
    text-align: center;
    color: red;
}
```

----

### html & css demo
open /demo_1.html
<https://www.w3schools.com/html/tryit.asp?filename=tryhtml_css_internal>

----

### bootstrap demo
open /demo_2.html
<https://codepen.io/freeCodeCamp/pen/NNvBQW>
<https://codepen.io/freeCodeCamp/pen/mJNqQj>

----

### tracking code (cont.)

1. wrap the implementation from the previous slide into a `<script>` tag
2. include linked javascript in `<head>`
3. add the html below after the `<footer>`

```html
<script type="text/javascript">
  _satellite.pageBottom();
</script>
```

----

### tracking code
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
