## Release History

## v1.1.3 (2015-05-12)
* don't limit shot to body element
* minor code and jslint fixes

## v1.1.2 (2015-05-05)
* create random .tmp directories to run `documentScreenshot` in parallel - refs #71

## v1.1.1 (2015-05-02)
* moved gm back to dependency list

## v1.1.0 (2015-04-30)
* got rid of cairo and node-canvas dependency by replacing it with [node-resemble-js](https://www.npmjs.com/package/node-resemble-js)
* minor bugfixes and documentation improvements

## v1.0.6 (2015-02-08)
* Using fs-extra to recursively make directories that don't exist. (see #53)
* Switch to node-resemble-js (fixes #49)

## v1.0.5 (2015-01-14)
* Applitools integration: automatic test save (see #48)

## v1.0.4 (2015-01-14)
* no changes

## v1.0.3 (2014-12-01)
* reset takeScreenshot flag after webdrivercss command finised

## v1.0.2 (2014-12-01)
* better support for IE<9 browser
* remove scrollbars before taking screenshots

## v1.0.1 (2014-11-21)
* fixed scope of variables
* document screenshot little bit more mobile friendly

## v1.0.0 (2014-11-12)
* introduced two commands (documentScreenshot, viewportScreenshot)
* use documentScreenshot to always take screenshot of the whole website
* implement support for [Applitools Eyes](https://applitools.com/)
* better result propagation
* changed filenames to *.baseline.png, *.regression.png and *.diff.png
* reuse taken screenshots (different workflow as before)
* minor IE improvements

## v0.3.1 (2014-10-24)
* clear screenshot root properly

## v0.3.0 (2014-09-01)
* make WebdriverCSS compatible with WebdriverIO

## v0.2.3 (2014-07-17)
* x-browser/driver-compatibility improvements

## v0.2.2 (2014-07-15)
* introduced `hide` option, remove local repository before download

## v0.2.1 (2014-07-13)
* fixed scrollTo bug

## v0.2.0 (2014-07-12)
* implemented shot synchronization with an external API

## v0.1.1 (2014-04-07)
* convert screenWidth parameters into numbers

## v0.1.0 (2014-03-28)
* first release
