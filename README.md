# QRlib

QRlib is an pure python qr code generator which can be used to create simple QR code , designer QR code or trackable QR codes


## What is a QR Code?


A Quick Response code is a two-dimensional pictographic code used for its fast readability and comparatively large storage capacity. The basic QR code consists of black modules arranged in a square pattern on a white background. The information encoded can be made up of any kind of data (e.g., binary, alphanumeric, or Kanji symbols).


## Installation


you can install QRlib with pip command
```bash
pip install QRlib
```
or with pip3
```bash
pip3 install QRlib
```

## Requirements


* python 3.4 or above
* [requests module](https://pypi.org/project/requests/)
* [tqdm module](https://pypi.org/project/tqdm/)
* [svglib module](https://pypi.org/project/svglib/)
* [reportlab module](https://pypi.org/project/reportlab/)
* [urllib module](https://pypi.org/project/urllib3/)


## Importing QRlib


import QRlib with command
```python
from QRlib.QRlib import *
```

## Generating QR codes

###### *Classic QR*
![Classic QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Classic.png "By Himanshu" )
```python
from QRlib.QRlib import *

img_name = "ClassicQR" # name of Qr without extension of image ( default to png )
qr_data = "this is an classic qr" # content of qr
size = 200 # size in pixal ( optional )

qr.classic(qr_data, img_name, size=size)
```

 ___
###### *Tansparent QR*
![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/transparentQR.png "Transparent QR" )

```python
from QRlib.QRlib import *

img_name = "TransparentQR" # name of Qr without extension of image ( default to png )
qr_data = "this is an Transparent qr" # content of qr
img_url = "https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/transtest.png" # url for the image ( optional )
size = 200 # size in pixal ( optional )

qr.transparent(qr_data, img_name, img=img_url, size=size)
```

-------


###### *Clear QR*
![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/clearQR.png "Clear QR" )
```python
from QRlib.QRlib import *

img_name = "ClearQR" # name of Qr without extension of image ( default to png )
qr_data = "this is an Clear qr" # content of qr
size = 200 # size in pixal ( optional )

qr.clear(qr_data, qr_name, size=size)
```
-------
###### *Custom QR*

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom1.png "Custom QR" ) |
|:------:|
|    ```Custom_1```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom2.png "Custom QR" ) |
|:------:|
|    ```Custom_2```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom3.png "Custom QR" ) |
|:------:|
|    ```Custom_3```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom4.png "Custom QR" ) |
|:------:|
|    ```Custom_4```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom5.png "Custom QR" ) |
|:------:|
|    ```Custom_5```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom6.png "Custom QR" ) |
|:------:|
|    ```Custom_6```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom7.png "Custom QR" ) |
|:------:|
|    ```Custom_7```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom8.png "Custom QR" ) |
|:------:|
|    ```Custom_8```    |

| ![Transparent QR](https://9p933al7lphdqzqhwh4gbg-on.drv.tw/QRlib/Custom9.png "Custom QR" ) |
|:------:|
|    ```Custom_9```    |



















