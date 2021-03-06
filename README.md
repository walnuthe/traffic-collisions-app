# traffic-collisions-app

This responsive web application can shows traffic collisions on public roads in unincorporated San Juan County WA. Collisions can be filtered by island and severity.

Note: Traffic collisions on private roads or within the Town of Friday Harbor are not available.

This application was forked from Esri's [dojo-bootstrap-map-js](https://github.com/Esri/dojo-bootstrap-map-js) repository.

## Instructions

By default, this application assumes you will want to work from local copies of all dependencies so that you can create a custom build. However, you can also work off of remotely hosted (CDN) dependencies by using `index.html`.

### Quick Start

1. [Download](https://github.com/sjcgis/traffic-collisions-app/archive/master.zip) or [Fork and clone the repo](https://help.github.com/articles/fork-a-repo)
2. Make sure the `traffic-collisions-app` folder is served via your local web server
3. Load `src/index.html` in your browser

### Downloading Dependencies and Building

You will need to install [Node](http://nodejs.org/), [Bower](http://bower.io/), and [Grunt](http://gruntjs.com/) in order to download dependencies and build the app via the command line.

1. [Fork and clone the repo](https://help.github.com/articles/fork-a-repo)
2. `cd` into the `dojo-bootstrap-map-js` folder
3. Run `npm install` to install the Grunt tasks
4. Run `bower install` to download Dojo and other dependencies
5. Run `grunt slurp` to download the Esri JSAPI
6. Run `grunt serve` to load the unbuilt app into a web browser
7. Modify the code as needed
8. Run `grunt build` to build the app under the `dist` folder
9. Run `grunt serve:build` to load the built app into a web browser

You may want to run `grunt clean:deploy` to remove all uncompressed javascript and source maps before you deploy the contents of that folder to your web server.

## Requirements

* Notepad or your favorite text editor
* Web browser with access to the Internet
* [Node](http://nodejs.org/), [Bower](http://bower.io/), and [Grunt](http://gruntjs.com/) to run the command line development tools

## Resources

* [Dojo Boostrap Map](//github.com/Esri/dojo-bootstrap-map-js)
* [Bootstrap Map](//github.com/Esri/bootstrap-map-js)
* [Dojo Bootstrap](//github.com/xsokev/Dojo-Bootstrap)
* [ArcGIS API for JavaScript](//js.arcgis.com)
* [Bootstrap](//getbootstrap.com)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute.

## Licensing
Copyright 2015 San Juan County GIS

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/dojo-bootstrap-map-js/master/license.txt) file.

[](Esri Tags: ArcGIS Web Mapping Bootstrap)
[](Esri Language: JavaScript)​
