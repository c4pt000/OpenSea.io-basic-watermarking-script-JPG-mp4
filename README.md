# OpenSea.io-basic-watermarking-script-JPG

replace liberty.jpg file with original file to watermark
<br>
this script uses the original JPG as an initial watermark by pixelating the original photo with the original photo
<br>
then the script uses a semi transparent "opensea.io" logo and places in the lower right hand corner of the watermarked photo
<br>
the script only does this on the client side of the browser (the actual file never physically changes preserving the original file from any changes it only makes the changes as the browser views it)
<br>

change index.html accordingly
```
change from:
<img src="watermark.php?file=liberty.jpg"></img>

change to:
<img src="watermark.php?file=file_you_want_to_watermark.jpg"></img>

```
firefox 127.0.0.1/index.html
