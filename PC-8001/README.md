# PC-8001用 MP3プレーヤー

![写真1](images/pcb_8001_rev5.png)

## 概要
- PC-8001用[シンプルシリアルポート]()からMP3プレーヤーをコントロールできます

## 部品表
|名称|値|数量|メモ|
|:-|:-|:-:|:-|
|カーボン抵抗|1KΩ|1| |
|電解コンデンサ|100u|1| |
|LED|3mm|1| |
|MP3プレーヤー|DFPlayer mini|1|[秋月電子](https://akizukidenshi.com/catalog/g/g112544/)|
|USBコネクタ|Aタイプ メス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g111551/)|
|ステレオミニジャック|3.5mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g109060/)|
|スライドスイッチ|DPDT|1|[秋月電子](https://akizukidenshi.com/catalog/g/g102627/)|

## 本体との接続
1. 本体の電源を切ります
2. 本体背面のジャンパスイッチを４にします
3. MP3プレーヤーをシリアルポートに接続します
4. MP3ファイルの入ったUSBメモリスティック、またはmicroSDカードを挿入します
5. DCジャックにACアダプタを接続します
6. ステレオミニジャックに外部スピーカーを接続します
7. MP3プレーヤーのスイッチをONにします(LEDが点灯します)
8. 本体の電源を入れます
9. [デモプログラム](https://github.com/chiqlappe/mp3_player/tree/main/PROGRAMS)を実行して動作を確認して下さい
   


