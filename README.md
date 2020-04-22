# Dia-vrt-sheets

The [VRT Network Equipment Shape Gallery](https://www.vrt.com.au/downloads/vrt-network-equipment) exported from LibreOffice to the following formats:

* [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics) for use with vector image editing software
* [Dia sheets](http://dia-installer.de/shapes/index.html.en) for use with [Dia Diagram Editor](http://dia-installer.de/)

The shapes in the Dia sheets have been customised as follows:

* Default height of 30px
* A [middle connection point](http://dia-installer.de/doc/en/objects-chapter.html#N40453) to allow connecting lines which rotate around the edge of the shape as it is moved
* A textbox to allow [in-canvas editing of text](http://dia-installer.de/doc/en/objects-chapter.html#entering-text)

These behaviours can be modified by editing the `.shape` files associated with each shape.

# Installation

## Prerequisites

The Dia sheets have been tested and work with Dia 0.97.3.

## Installation instructions

Installation of the Dia sheets should be straighforward in either Linux or Windows but have only been tested in Linux.

### Linux

1. Copy the contents of `Dia Sheets/shapes` to `~/.dia/shapes`
2. Copy the contents of `Dia Sheets/sheets` to `~/.dia/sheets`
3. Restart Dia

### Windows (pre-Vista)

1. Follow Linux instructions but copy the files to `C:\Documents and Settings\[username]\.dia\`

### Windows (Vista+)

1. Follow Linux instructions but copy the files to `C:\Users\[username]\.dia\`

# Limitations

Dia does not properly handle scaling of SVG images. This is fine at sizes close to the default size but becomes noticeable if you significantly enlarge the shapes.

# License

This project is offered under a [Creative Commons Attribute-ShareAlike V3.0](https://creativecommons.org/licenses/by-sa/3.0/) license. 

## Attribution

This project is based on the [VRT Network Equipment Shape Gallery for LibreOffice/OpenOffice](https://www.vrt.com.au/downloads/vrt-network-equipment) which has been modified as specified in this document.