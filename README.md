# Electron Icon Generator

![Electron Icon Generator Demo](https://github.com/petarmihaylov/electron-icon-generator/raw/master/demo.gif)

### Description

This script aims to make generating icons for Electron projects easier.

At it's stat it generates a full set of icons for a Mac application in an .iconset folder. The icons can then be converted to a .icns file with ``iconutil -c icns path/to/icon.iconset``

The script also generates a full set of icons for an Electron application.

### Prerequisites
This script is dependent on ImageMagick. You must install ImageMagick first.

#### ImageMagick Website
[http://www.imagemagick.org](http://www.imagemagick.org)

#### On Windows
Download the install ImageMagic from their website.

#### On Linux/Mac
Most Linux distributions provide ImageMagick as a package.

| **OS**                                  | **Command**                          |
|-----------------------------------------|--------------------------------------|
| Debian/Ubuntu/Mint                      | ``sudo apt-get install imagemagick`` |
| Fedora/Red Hat                          | ``sudo yum install imagemagick``     |
| MacOS with [Homebrew](https://brew.sh/) | ``sudo brew install imagemagick``    |

### Usage

#### Clone and Chmod
```bash
git clone https://github.com/petarmihaylov/electron-icon-generator
cd electron-icon-generator
chmod +x electron-icon-generator-script.sh
```

#### Run Script
``./electron-icon-generator-script.sh srcfile dstpath``

### Parameters

``srcfile`` - The source png image. Minimum 1024x1024 pixels.

``dstpath`` - The destination path where the icons will be generated.

### Author
Petar Mihaylov ([petarmihaylov.me](http://petarmihaylov.me))

### License
[MIT](https://opensource.org/licenses/MIT)


### Credits
Inspired by [smallmouou's](https://github.com/smallmuou) [iOS Icon Generator](https://github.com/smallmuou/ios-icon-generator)
