----------------------------------------------------------------

# Copyright © 01-10-2021 [Tyler R. Drury](https://vigilance91.github.io/) (vigilance.eth), All Rights Reserved.

----------------------------------------------------------------

# [web-bundle][1]™

**web-bundle™** is a bundled collection of common free open-source software (FOSS) javascript and css libraries, commonly used in web development including:

* **[jQuery](https://jquery.com/)** - utilities for manipulating the DOM, making HTTP requests and more
* **[bootstrap](https://getbootstrap.com/)** - core UI and styles
* **[highlightjs](https://highlightjs.org/)** - text highlight for displaying code
* **[underscore](https://underscorejs.org/)** - broad range of utilities,
* **[qUnit](https://qunitjs.com/)** - javascript unit testing framework, developed by the jQuery team

**./javascript/bundle.js** and **./css/bundle.css** are for production,
while **./javascript/bundle-test.js** and **./css/bundle-test.css** contain code for unit testing and are intended for unit testing during development.

The **original licenses** of all composite libraries are preserved, as is, in the bundled files.

This project is provided for free, on an **AS IS BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND**, either express or implied.


If you or your organization own the rights to any of the third-party libraries used in this project or have concerns regarding their use,
please [contact me](https://vigilance91.github.io/contact.html).


----------------------------------------------------------------

### Future Developments

As this project expands and other new projects come into use,
more libraries will be added.


----------------------------------------------------------------

## Before Starting

**Be aware** this project is currently in development and intended for use in a browser that is compatible with at least Javascript ES5.
It does not support ES6 module syntax nor is it currently designed for use in a nodeJS environment.

This project has the following directory structure

* **/javascript** - bundled Javascript files
* **/css** - bundled CSS files
* **LICENSE.md** - project license file
* **README.md** - project readme file
* **AUTHORS.md** - authors and other contributors to this project
* **checksums.txt** - a text file containing the SHA256 and SHA512 checksums of the bundled files
* **.gitignore** - file specifying which files and directory patterns not to include when pushing commits


----------------------------------------------------------------

## Get the Project

The most recent, stable release of this project may be cloned or forked from the official [GitHub repo][1].

Start by cloning the web-bundle repo (either using the command line, github desktop or the github website)
into the root directory which contains or will contain a web project.

Once cloned to a local machine, link the javascript and css files in the **head** element of an html document, like normal.

```
<head>
    <link rel='stylesheet'
        type='text/css'
        href="/web-bundle/css/bundle.css">
    
    <script type='application/javascript'
        src="/web-bundle/javascript/bundle.js"></script>
</head>
```

Ensure to link to the fields suffixed with **-test** for unit testing, during development.

```
<head>
    <link rel='stylesheet'
        type='text/css'
        href="/web-bundle/css/bundle-test.css">
    
    <script type='application/javascript'
        src="/web-bundle/javascript/bundle-test.js"></script>
</head>
```


----------------------------------------------------------------

## License

[web-bundle][1]™ is released under the Apache-2.0 License.

See the [LICENSE][2] file for more details.


----------------------------------------------------------------

## Authors

All respective authors and contributors are attributed in [AUTHORS][3].


[1]: https://github.com/vigilance91/web-bundle
[2]: https://github.com/vigilance91/web-bundle/LICENSE.md
[3]: https://github.com/vigilance91/web-bundle/AUTHORS.md
