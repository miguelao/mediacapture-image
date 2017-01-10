image-capture
=============

Image Capturing for the Web :camera:

This document specifies methods and camera settings to produce photographic image capture.

Specification and Samples
-------------
* [Image Capture (a.k.a. MediaStream Image Capture) Specification](https://w3c.github.io/mediacapture-image/), including code samples.
* [Implementation Status](implementation-status.md) describes various browser support on platforms, hardware compatibility, etc.
* [Sample code](https://rawgit.com/Miguelao/demos/master/imagecapture.html)
* [Image Capture polyfill](https://github.com/dandv/imagecapture)

Notes on bikeshedding :bicyclist:
--------------

To compile `index.bs` into `index.html` , I'm using the online compiler:

```
curl https://api.csswg.org/bikeshed/ -F file=@index.bs -F force=1 > index.html
```

if the produced file has a strange size (i.e. zero, a few KBs), then something went terribly wrong; run instead:

```
curl https://api.csswg.org/bikeshed/ -F file=@index.bs -F output=err
```

and try to figure out why `bikeshed` did not like the `.bs` :'(
