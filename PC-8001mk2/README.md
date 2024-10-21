# PC-8001mk2用 MP3プレーヤー

![写真1](https://github.com/chiqlappe/mp3_player/blob/main/PC-8001mk2/images/IMG_2406.JPG)

## 概要
- PC-8001mk2のシリアルポートからMP3プレーヤーをコントロールできます

## 仕様

|項目|仕様|
|:-|:-|
|対応メディア|USBメモリスティック,microSD|
|通信速度|9600bps|
|シリアルポート設定|ボーレート=x1,キャラクタ長=8ビット,ストップビット=1ビット|


## 部品表
|名称|値|数量|メモ|
|:-|:-|:-:|:-|
|カーボン抵抗|1KΩ|1| |
|セラミックコンデンサ|0.01u|1| |
|セラミックコンデンサ|100u|1| |
|LED|3mm|1| |
|MP3 Player|DFPlayer mini|1|[秋月電子](https://akizukidenshi.com/catalog/g/g112544/)|
|USBコネクタ|Aタイプ メス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g111551/)|
|ステレオミニジャック|3.5mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g109060/)|
|標準DCジャック|2.1mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g106568/)|
|Dサブコネクタ|25P オス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g100164/)|
|RS232CインターフェイスIC|SP233ACP|1|[秋月電子](https://akizukidenshi.com/catalog/g/g100197/)|
|スライドスイッチ|DPDT|1|[秋月電子](https://akizukidenshi.com/catalog/g/g102627/)|

- この他に5VのACアダプタが必要です [参考](https://akizukidenshi.com/catalog/g/g111996/)

## 本体との接続
1. 本体の電源を切ります
2. MP3プレーヤーをシリアルポートに接続します
3. ACアダプタをDCジャックに挿入します
4. 本体の電源を入れます
5. [デモプログラム](https://github.com/chiqlappe/mp3_player/tree/main/PROGRAMS)を実行して動作を確認して下さい
   
![写真2](https://github.com/chiqlappe/mp3_player/blob/main/PC-8001mk2/images/IMG_2417.JPG)

