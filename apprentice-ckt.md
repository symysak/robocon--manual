# かけだしロボコニスト　～回路編～

基礎を中心に実用的なプログラミングを学びます  

* [苦しんで覚えるC言語(苦C)](#kairo1)
* [Ardino](#kairo2)
  1. [Aruduino IDEをダウンロード](#kairo3)
  2. [Aruduinoが生きているのか確認する](#kairo4)
  3. [LEDをチカチカ光らせてみる](#kairo5)
  4. [LEDの光の強さを調節してみる](#kairo6)
  5. [【コラム】デジタルとアナログの違い](#kairo7)
  6. [LEDをゆっくり明るくしてみる](#kairo8)
  7. [モータを動かしてみる](#kairo9)
  8. [シリアル通信してみる](#kairo10)
  9. [I2Cしてみる](#kairo11)
   
---
## <a id="kairo1">苦しんで覚えるC言語</a>
[苦しんで覚えるC言語](https://9cguide.appspot.com/)  
13章まで（ポインタの手前）までが理解できれば完璧だと思います  
そこまで出来たら、ポインタについて調べてみるといいかも…？  

---
## <a id="kairo2">Ardiuino</a>
Aruduino（アルディーノ）とは、マイコンの一種。
C言語風の「Arduino言語」によってプログラムを制作・コンパイル・デバッグ等し、それをArduino IDEによってArduinoボードに転送することで使用できる。

緑のボードがAruduino本体  
繋いでいる線が「ジャンパ線」  
白いボードが「ブレッドボード」  
![image](/image/ckt-1.png)  
部室のどこにあるか確認しておこう！

### <a id="kairo3">Aruduino IDEをダウンロード</a>
[Arduino IDE](https://www.arduino.cc/en/software)にアクセスして自分の使用しているPC（OS）に適切なものをダウンロードしてください。  
最新のバージョン（サイトの一番上）のものをおすすめします。  
![image](/image/ckt-2.png)  
※ArduinoIDEの日本語はファイル＞環境設定＞Language＞Japaneseで設定できます

ArduinoはArduino言語を使用するので[Arduino 日本語リファレンス](http://www.musashinodenpa.com/arduino/ref/)を見ながらプログラムします。
ブックマークしておきましょう！  

まず、AruduinoIDEを開いてみましょう  
#### コードの意味
> void setup() {  
> //電源が入って一回しか実行しない内容  
>  }  
>   
> void loop() {  
> //setupを実行した後に無限に繰り返す内容  
> }  






