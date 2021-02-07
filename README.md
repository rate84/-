# 2020　ロボットシステム学　課題１
 
提出版になります．宜しくお願い致します．
 
# 準備するもの
 
 * Raspberry Pi3 Model B ×1
 * LANケーブル ×1
 * Wifiルータ ×1
 * microSD ×1
 * USB電源ケーブル(TypeA-MicroB) ×1
 * ノートPC　又は　モニター ×1
 * LED ×1
 * 220Ωの抵抗 ×1
 * ジャンプワイヤー ×2
 
# 事前準備
 
 * ubuntuのセットアップは以下を参考にした．
 * https://ryuichiueda.github.io/robosys2020/lesson1_introduction.html
 
# デバイスの作成
 
 * LEDを点灯させるためのデバイスを作成する．点灯と消灯を行うデバイスは以下を参考にする．
 * https://ryuichiueda.github.io/robosys2020/lesson7_device_driver.html
 
# コマンドの操作手順
 
 * echo 1 > /dev/myled0(LEDが点灯)
 * echo 2 > /dev/myled0(LEDが点滅)
 * echo 0 > /dev/myled0(LEDが消灯)　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
 
# 作成した回路
 
![C88E937D-19FA-4A39-8389-71434AAAFD01](https://user-images.githubusercontent.com/75563494/107159020-f20d3d00-69d0-11eb-8e38-10377c039d4b.jpg)
 
# 実際の動作の様子

