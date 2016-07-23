# simpleImageMeta
Simply javascript library for get major image meta data 

## How to use
```
<!DOCTYPE html>
<html>
<head>
<script type="text/javascript" src="js/simeta.js"></script>
</head>

<body>
<input id="file-input" type="file" />

<script>
document.getElementById("file-input").onchange = function(e) {
  var meta = new SimpleImageMeta(e.target.files[0].src);
  var info = meta.readInfo();
  ........
}
</body>
</html>
```

## reference projects
exif-js

## referance documents 
CIPA DC-008-Translation-2016 Exchangeable image file format for digital still cameras : Exif Version 2.31
http://www.cipa.jp/std/documents/e/DC-008-Translation-2016-E.pdf

http://www.cipa.jp/std/documents/j/DC-008-2012_J.pdf
