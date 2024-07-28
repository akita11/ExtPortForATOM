# ExtPortForATOM

<img src="https://github.com/akita11/ExtPortForATOM/blob/main/ExtPortForATOM.jpg" width="240px">

M5stackのATOMシリーズ ([Lite](https://www.switch-science.com/products/6262) / [Matrix](https://www.switch-science.com/products/6260)に3つのGroveポートを拡張します。Groveポートへの給電はATOMから、またはUSB Type-Cコネクタからを選択できます。

※M5Stack純正の[ATOM PortABC](https://www.switch-science.com/products/9198)とピン配置・コネクタの色は同一ですが、Portの名称が異なります(本品=B/C/D、ATOM PortABC=A/B/C)

## 使い方

<img src="https://github.com/akita11/ExtPortForATOM/blob/main/withATOM.jpg" width="240px">

ATOMを上図のように取り付けて使います。

<img src="https://github.com/akita11/ExtPortForATOM/blob/main/jumper.jpg" width="240px">

GroveポートのVDD(+5V)への給電は、ボード上のショートピンで切り替えることができます。

- ”ATOM"側 : ATOMの+5V端子から給電（デフォルト）
- ”USB"側 : USB Type-C端子から給電（別途、USB ACアダプタやモバイルバッテリ等から給電してください）

## ピン配置

各ポートはATOMの以下のIOピンに接続されています。UIFlowからも利用可能となる予定です。

- PortB（赤色） : IO21/IO25/VDD/GND
- PortC（黒色） : IO33/IO23/VDD/GND
- PortD（青色） : IO19/IO22/VDD/GND

※ATOM-S3の場合は以下のようになります。

- PortB（赤色） : IO39/IO38/VDD/GND
- PortC（黒色） : IO8/IO7/VDD/GND
- PortD（青色） : IO6/IO5/VDD/GND



<img src="https://github.com/akita11/ExtPortForATOM/blob/main/silk.jpg" width="240px">

※初期ロットでは裏面シルクに間違いがあります。PortBとPortCの表記が逆になっていますのでご注意ください。（コネクタの色で各Portの名称を確認してください）

## Author

Junichi Akita (akita@ifdl.jp, @akita11)
