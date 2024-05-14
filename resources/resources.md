# Resources
## /resources/

This folder contains all of the resources which are bundled with the application during the build process.

## /resources/index.view

This is the main Fitbit SVG file where the application user interface markup is defined. This is a mandatory file.

## /resources/widget.defs

This Fitbit SVG file controls which system widgets are available for use within the <code>index.view</code> file. This is a mandatory file.

## /resources/*.css

Fitbit CSS files can be included in the application by creating a <code>&lt;link&gt;</code> in the <code>index.view</code> file.

## /resources/*.png &nbsp;&&nbsp; /resources/*.jpg

All image files which are included in the resources folder can be used in the presentation layer by referencing them within an <code>&lt;image&gt;</code> element in the <code>index.view</code>.
