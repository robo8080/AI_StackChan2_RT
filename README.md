# AI_StackChan2_RT
”ｽﾀｯｸﾁｬﾝ アールティVer.β版”用 AIｽﾀｯｸﾁｬﾝ2です。<br>
(M5Stack BasicとCore2のみ対応しています。)
<br><br>

![画像1](images/image1.jpg)<br><br>

AIｽﾀｯｸﾁｬﾝ2 RTの特徴<br>

* 音声合成にWeb版 VOICEVOXを使います。
* 音声認識に"Google Cloud STT"か"OpenAI Whisper"のどちらかを選択できます。
<br>


Google Cloud STTは、”MhageGH”さんの [esp32_CloudSpeech](https://github.com/MhageGH/esp32_CloudSpeech/ "Title") を参考にさせて頂きました。ありがとうございました。<br>
"OpenAI Whisper"が使えるようにするにあたって、多大なご助言を頂いた”イナバ”さん、”kobatan”さんに感謝致します。<br>
ウェイクワードには、”MechaUma”さんの[SimpleVox](https://github.com/MechaUma/SimpleVox/ "Title")ライブラリを使わせていただきました。

---


### 必要な物 ###

以下のどちらか。<br>

* [ｽﾀｯｸﾁｬﾝ アールティVer. β版 (フルキット)](https://www.rt-shop.jp/index.php?main_page=product_info&products_id=4143/ "Title")<br>
* [ｽﾀｯｸﾁｬﾝ アールティVer. β版 (M5なし)](https://www.rt-shop.jp/index.php?main_page=product_info&products_id=4144/ "Title")<br>

* M5なしの場合別途、M5Stack BasicかCore2<br>
* [M5Stack用PDMマイクユニット](https://www.switch-science.com/products/6620?_pos=2&_sid=38aeec5c3&_ss=r/ "Title")（ｽﾀｯｸﾁｬﾝと音声で会話する場合）<br>
<br>

### プログラムをビルドするのに必要な物 ###
* VSCode<br>
* PlatformIO<br>

使用しているライブラリ等は"platformio.ini"を参照してください。<br>

---

* 【注意】
ｽﾀｯｸﾁｬﾝと音声で会話する場合は、PORT.Aに[M5Stack用PDMマイクユニット](https://www.switch-science.com/products/6620?_pos=2&_sid=38aeec5c3&_ss=r/ "Title")を接続しておく必要があります。<br>

---

### 使い方 ###

こちらを参照してください。<br>

* [AI_StackChan2_RT_README](https://github.com/robo8080/AI_StackChan2_RT_README "Title")<br>
<br>
<br>
<br>

