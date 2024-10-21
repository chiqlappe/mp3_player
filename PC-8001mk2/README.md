# PC-8001mk2用 MP3プレーヤー

![写真1](https://github.com/chiqlappe/mp3_player/blob/main/PC-8001mk2/images/pcb_rev4.png)

## 概要
- PC-8001mk2のシリアルポートからMP3プレーヤーをコントロールできます

## 仕様

|項目|仕様|
|:-|:-|
|対応メディア|USBメモリスティック,microSDカード|
|通信速度|9600bps|
|シリアルポート設定|ボーレート=x1,キャラクタ長=8,ストップビット=1,パリティビット=なし,フロー制御=なし|

## 部品表
|名称|値|数量|メモ|
|:-|:-|:-:|:-|
|カーボン抵抗|1KΩ|1| |
|セラミックコンデンサ|0.01u|1| |
|電解コンデンサ|100u|1| |
|LED|3mm|1| |
|MP3 Player|DFPlayer mini|1|[秋月電子](https://akizukidenshi.com/catalog/g/g112544/)|
|USBコネクタ|Aタイプ メス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g111551/)|
|ステレオミニジャック|3.5mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g109060/)|
|標準DCジャック|2.1mm|1|[秋月電子](https://akizukidenshi.com/catalog/g/g106568/)|
|Dサブコネクタ|25P オス|1|[秋月電子](https://akizukidenshi.com/catalog/g/g100164/)|
|RS232CインターフェイスIC|SP233ACP|1|[秋月電子](https://akizukidenshi.com/catalog/g/g100197/)|
|スライドスイッチ|DPDT|1|[秋月電子](https://akizukidenshi.com/catalog/g/g102627/)|

- この他に[5VのACアダプタ](https://akizukidenshi.com/catalog/g/g111996/)と外部スピーカーが必要です
- Dサブコネクタの金属部分は不要ですので取り外して下さい

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
   

