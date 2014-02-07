# nw-trainings

This is a simple [node-webkit](https://github.com/rogerwang/node-webkit) application to collect training data, headers and sinple textblocks.
The export can be used to generate training catalogs etc.

Due to the nature of node-webkit apps, this runs on mac os x , windows and linux.

It uses [bootstrap-3](http://getbootstrap.com), [knockoutjs](http://knockoutjs.com) and [nedb](https://github.com/louischatriot/nedb) as a NoSQL-DB.

## Features
* create headers sections
* create multiline textblock sections
* create training sections
* move sections up/down
* delete sections
* export sections as json

## Installation
* download node-webkit runtime for your platform (all from the node-webkit project)
 * mac os x: node-webkit.app
 * windows: nw.exe, nw.pak, icudt.dll, libEGL.dll, libGLESv2.dll
* install nedb node module `npm install nedb --save`

## Run
Simply double-click on the `nw.exe` for windows or the `node-webkit` app on the mac.

## Screenshots
![image1](/screenshots/image1.png)
![image1](/screenshots/image2.png)
![image1](/screenshots/image3.png)
