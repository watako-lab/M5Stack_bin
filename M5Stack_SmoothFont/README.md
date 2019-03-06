# About
こちらの[TFT_eSPIライブラリ](https://github.com/Bodmer/TFT_eSPI)を使って、M5Stackでスムースフォントを表示してみたテストバイナリです。詳細記事は[こちらのブログ](http://watako-lab.com/2018/10/31/m5_font/)にて。

# How to use
1. sd_card下にあるフォントファイルをmicroSDのルートディレクトリにコピー。
2. bin下にあるバイナリファイル群をFlash Downloaderを使ってM5Stackに焼く。以下の画像を参考に設定し、「Start」で焼き開始。

![ToolSetting](https://github.com/watako-lab/M5Stack_bin/blob/master/M5Stack_SmoothFont/img/ToolSetting.png)

3. 焼き終わったら、M5Stackのリセットボタンを押すと、焼いたファームが起動。今回のファームは以下のような感じ。

![SmoothFontDemo](https://github.com/watako-lab/M5Stack_bin/blob/master/M5Stack_SmoothFont/img/SmoothFontDemo.jpg)

