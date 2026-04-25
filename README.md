# simpleImageMeta
Simply javascript library for get major image meta data 

JPEG/PNG画像に含まれるExifメタ情報を取得確認できます。

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

## referance documents 
[カメラ映像機器工業会　CIPA規格類](https://www.cipa.jp/j/std/std-sec.html)

CIPA DC-008-Translation-2016 Exchangeable image file format for digital still cameras : Exif Version 2.31

[Exif Update History](https://www.cipa.jp/e/news/index.html)

[DC-008-2012_J.pdf](http://www.cipa.jp/std/documents/j/DC-008-2012_J.pdf)
