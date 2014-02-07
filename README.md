# nw-trainings

This is a simple [node-webkit](https://github.com/rogerwang/node-webkit) application to collect training data, headers and simple textblocks.
The json export can be used to generate training catalogs etc.

Due to the nature of node-webkit apps, this runs on mac os x , windows and linux.

It uses
* [bootstrap-3](http://getbootstrap.com) for the layout and icons,
* [knockoutjs](http://knockoutjs.com) all the databinding
* [nedb](https://github.com/louischatriot/nedb) as a NoSQL-DB.

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

With an empty database you can create one of the three predefined section types (header/textblock/training)

![image1](/screenshots/image1.png)

Before and behind any section you can create new sections.
Moving them up or down is done by the little arrows.
Delete the section with the trash icon.

![image1](/screenshots/image2.png)

Here is a mixture of all sections.

![image1](/screenshots/image3.png)
