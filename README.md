# Select a Geolocation with OpenLayers and CallBack
Demo that creates a selector for a geolocation on a map by using [OpenLayers](https://www.openlayers.org). Geolocation Button allows to center map on current geolocation and callback url shows how to call this tool remotely and return the selected geolocation.

## [Geolocation Select Demo](https://niebert.github.io/openlayer_selectlocation)


## Files of Demo
This demo consists of two file stored in ___/docs___
* ___index.html___ and
* ___selectlocation.html___.
___index.html___ calls ___selectlocation.html___ and lets the user select a geolocation. After the users clicks on the map in ___selectlocation.html___ the OpenLayers map returns the selected geolocation back to ___index.html___. In this example ___index.html___ reads the geolocation from the LinkParameter e.g. ___index.html?geolocation=-12.213,65.123___ and stores the geolocation in a input text element with the ID=mygeolocation in the HTML file ___index.html___.

### Libraries
* ___linkparam.js___ The LinkParameter parameter are handled with a Javascript Class ___docs/js/linkparam.js___.
* ___openlayers3.js___ is the OpenLayers3 version as JavaScript library. See [OpenLayers](https://www.openlayers.org) for more details.

### CSS
* ___font-awesome___ Font AweSome is preinstalled for offline use of buttons and further tests.


### Demo
* [Geolocation Select Demo](https://niebert.github.io/openlayer_selectlocation)
* [Download Demo](https://github.com/niebert/openlayer_selectlocation/archive/master.zip) unzip file and checkout the subdirectory ___/docs___. The demo is stored in ___/docs___ because it is used at the same time as root directory for https://niebert.github.io/openlayer_selectlocation
