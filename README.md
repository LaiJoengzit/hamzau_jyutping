# 欽州粵拼

[![exe](https://img.shields.io/badge/exe%E4%B8%8B%E8%BC%89-windows-blue?style=for-the-badge&logo=windows)](https://github.com/LaiJoengzit/hamzau_jyutping/releases/download/2.0/HamzaujyutpingforPC.exe)
[![apk](https://img.shields.io/badge/apk%E4%B8%8B%E8%BC%89-Android-brightgreen?style=for-the-badge&logo=android)](https://github.com/LaiJoengzit/hamzau_jyutping/releases/download/2.0/HamzaujyutpingforAndroid.apk)

配方 Recipe： ℞ `LaiJoengzit/hamzau_jyutping`

一份修減自《欽州白話》（現[欽州白話網](https://hamzau.com/)）數據、聽在Rime使得噶字詞庫碼表文件<br>
A dict file revised and reduced from the data of *Hamchow Cantonese* (now [Hamzau.com](https://hamzau.com/)) for use in rimes

一份戥佢配套噶輸入方案<br>
A schema coming with the dict

同埋包好欽拼噶小狼毫、同文包<br>
And packages for Weasel and Trime with this Hamping. 

- 貼士：<br>
Tips: <br>
電腦直接<kbd>‵</kbd>鍵、安卓長撳<kbd>z</kbd>鍵出"‵"可以使汉语拼音方案反查對應噶欽州音，但要注意多音字<br>
You can reversely look up Hamping with Hanyu Pinyin by clicking <kbd>‵</kbd> on PC or by long_clicking the <kbd>z</kbd> button calling "‵" on Android, but be aware of homographs. 

- 貼士2：<br>
Tips2: <br>
關於<kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd>簡拼：可以使<kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd>鍵分別輸入「aa」「nj」「ng」「sl」「oe」；使了<kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd>簡拼可以聽輸入等同於三拼。有心機噶話，你又可以自己定義啱自己噶<kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd>方案。<br>
About the abbreviation using <kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd>: you may use <kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd> to replace "aa" "nj" "ng" "sl" "oe" respectively, which can make it identical to "trible-ping". You can also define your own <kbd>q</kbd><kbd>r</kbd><kbd>v</kbd><kbd>x</kbd><kbd>y</kbd> method if you want. <br>

- 注意：<br>
Note: <br>
建議在設置裏頭設同文鍵盤主題成tongwenfenggoi（同文風改），來方便九宮輸入、聲調輸入等等。在PC上可以使上檔鍵<kbd>Shift</kbd>加<kbd>Z</kbd><kbd>R</kbd><kbd>S</kbd><kbd>F</kbd>輸入1234聲調；在安卓同文上需要使tongwenfenggoi、<kbd>z</kbd><kbd>r</kbd><kbd>s</kbd><kbd>f</kbd>鍵「上劃」輸入1234聲調。關於tongwenfenggoi其他噶多種功能請參睇下低鏈接到噶文檔<br>
It is recommended to change the theme into "tongwenfenggoi"("Trime Style (Modified)") for Trime in Settings to make it easier to input the tones and to input in T9 mode. On PC, you can hold the Shift key <kbd>Shift</kbd> and plus <kbd>Z</kbd><kbd>R</kbd><kbd>S</kbd><kbd>F</kbd> to input tone 1 - tone 4; on Android Trime, you may need to use the theme "tongwenfenggoi" and swipe up on keys <kbd>z</kbd><kbd>r</kbd><kbd>s</kbd><kbd>f</kbd> to input tone 1 - tone 4. For other functions of tongwenfenggoi please see the introduction in following link. <br>
<br>⇨[關於使用「同文風（改）」主題啲另類鍵功能噶貼士](https://github.com/LaiJoengzit/hamzau_jyutping/blob/master/themetips.md)<br>
<br>你又可以單獨使用tongwenfenggoi主題，衹要下載[tongwenfenggoi.trime.yaml](https://github.com/LaiJoengzit/hamzau_jyutping/blob/master/tongwenfenggoi.trime.yaml)並按下低「Android同文手動更新文件方法」來裝並在設置裏頭揀過主題就得<br>
You can also use the tongwenfenggoi theme alone, just download [tongwenfenggoi.trime.yaml](https://github.com/LaiJoengzit/hamzau_jyutping/blob/master/tongwenfenggoi.trime.yaml), follow the steps in "To manually update the files of Trime for Android" below to install and change the theme in settings.

- 注意2：<br>
Note2: <br>
想使tongwenfenggoi噶日文韓文鍵盤，Trime要裝有對應噶日文韓文思機碼、為之你可以諮詢啲相關人士，𠹲純假名鍵盤就冇使<br>
To use the keyboards for Japanese or Korean, it is required to have corresponding Japanese or Korean schemata installed in Trime, for which you may refer to the relevant people, while it is unnecessary for the keyboard of pure kana.

#### Android同文手動更新文件方法：<br>To manually update the files of Trime for Android:

1. 捉`hamzau_jyutping.dict`同埋`hamzau_jyutping.schema`挃落`/Rime`文件夾來替換啲舊噶；<br>
Put `hamzau_jyutping.dict` and `hamzau_jyutping.schema` into `/Rime` and replace the old ones; <br>
2. 入同文設置；<br>
Go to the Settings of Trime;<br> 
3. 撳“部署”（正常跳出冇關事）；<br>
Press "部署" (Deploy) (it will jump out but it's fine); <br>
4. 使。<br>
Use it.

#### 對於iOS使用者：<br>For iOS users:

多煩自己下載iRime並學習安裝方法（見圖自隻iRime羣）<br>
Please download iRime and learn how to install with the picture from the group of iRime below, on your own: <br>
<img src="./iRime.JPG" width="200"/>

- 而今項工：冇有嘢要做。<br>
TODO: Nothing.
