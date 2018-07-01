# Js Exif

This module, is the simplest way to get exif data of images

## Getting Started

### Installing

	bower install https://github.com/jsqy/js-exif.git --save

### Usage

Pass imageURI and get the object with EXIF information

```javascript
Exif.readData(imageURI, function(exifObject) {
  console.log(exifObject);
});
```

## What is Exif?

Is a standard followed by manufacturers of digital cameras that record information about the technical conditions of image capture on the image file itself in the form of tagged metadata.

If you want know more about technical information, see these links:
- [Exif Standard 2.2](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf)
- [Description of Exif file format](http://www.media.mit.edu/pia/Research/deepview/exif.html)
- [Exif Tags](http://www.sno.phy.queensu.ca/~phil/exiftool/TagNames/EXIF.html)


## Example of Exif Data on photo

| Key | Value |
|-----|-------|
| Make | Canon |
| Model | Canon EOS 60D |
| DateTime | 2014:02:16 15:00:00 |
| XResolution | 240 |
| YResolution | 240 |
| Resolution Unit | Inch |
| FNumber | f/8.0 |
| Focal Length | 100 mm |
| GPS Latitude | -8.053889 |
| GPS Longitude | -34.880833 |
| Exposure Program | Aperture priority |
| Flash | Flash fired, compulsory flash mode |
| Metering Mode | Pattern |
| Exposure Time | 0.004 |
| Shutter SpeedValue | 7.965784 |
| Custom Rendered  | Normal process |
| White Balance | Auto white balance |
| ISO Speed Ratings | (100) |
| Lens Model | EF100mm f/2.8L Macro IS USM |
| Lens Serial Number | 0000023967 |
| Lens Specification | (100,100,0,0) |
| This is just somes examples, has much more informations. | ... |


## About

#### Who?
Created by [Guilherme Farias](http://guilhermefarias.com/), a web developer from Brazil.

#### License?
Cordova Exif is released under the terms of the [MIT license](https://github.com/guilhermefarias/CordovaExif/blob/master/MIT-LICENSE).
