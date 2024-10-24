# PC-8001用 MP3プレーヤー

![写真1](images/pcb_8001_rev5.png)

## 概要
- PC-8001用[シンプルシリアルポート](https://github.com/chiqlappe/simple_serial_port/tree/main)からMP3プレーヤーをコントロールできます

## 部品表
|名称|値|数量|メモ|
|:-|:-|:-:|:-|
|カーボン抵抗|1KΩ|1| |
|電解コンデンサ|100u|1| |
|LED|3mm|1| |
|MP3プレーヤーモジュール|DFPlayer mini|1|[秋月電子](https://akizukidenshi.com/catalog/g/g112544/)|
|USBコネクタ|Aタイプ メス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g111551/)|
|ステレオミニジャック|3.5mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g109060/)|
|スライドスイッチ|DPDT|1|[秋月電子](https://akizukidenshi.com/catalog/g/g102627/)|
|ピンヘッダ|オスL型 1x4(4p)|1| |

## 本体との接続
1. 本体の電源を切ります
2. 本体内部のジャンパを1-5にします。ソケット部分を持ち上げるとロックが外れます
![写真](images/0522b.png)
4. SIOソケットにシンプルシリアルポートを接続します
![写真](images/IMG_2767.JPG)
5. MP3プレーヤーとシンプルシリアルポートを接続ケーブルで接続します。基板の+5Vのマークを目印にしてケーブルの色を写真のように揃えて下さい
![写真](images/IMG_2768.JPG)
6. MP3ファイルの入ったUSBメモリスティック、またはmicroSDカードを挿入します
7. ステレオミニジャックに外部スピーカーを接続します
8. 本体の電源を入れます
9. MP3プレーヤーのスイッチをONにします(LEDが点灯します)
10. [デモプログラム](https://github.com/chiqlappe/mp3_player/tree/main/PROGRAMS)を実行して動作を確認して下さい
   


