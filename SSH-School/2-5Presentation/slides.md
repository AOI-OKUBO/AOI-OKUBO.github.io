---
aspectRatio: '4/3'
theme: seriph
highlighter: shiki
titleTemplate: '%s - Slidev'
download: https://AOI-OKUBO.github.io/SSH-Nichidai/2-5Presentation.pdf
---

<img src="https://drive.google.com/uc?export=view&id=102SHQFN1aZ_-oc3McEby1cbJldoYjN9Q" width=200>

<div class="text-right">

  # テスラコイルってな〜に
  ## 〜繊細な音を奏でるテスラコイルを作る〜

  発表者：大久保　碧

  担当教員：堀　輝一郎

</div>

---
layout: full
---

# 目次

<div class="text-5xl">

1. テスラコイルとは
1. 仕組み
1. 問題
1. リサーチクエスチョン
1. これからの予定

</div>

<!--
この流れで発表していきます
まずテスラコイルとはなにかです
こちらです
-->

---

# これです

<iframe class="w-full h-5/6" src="https://www.youtube.com/embed/Ia_GzEewIZQ?t=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--
まず見てください
-->

---
layout: image-right
image: >-
  https://upload.wikimedia.org/wikipedia/commons/4/4a/OneTeslaTS_DRSSTC_Tesla_Coil_closeup.jpg
---

# テスラコイルとは

<br>

## こんなの
<arrow x1="200" y1="140" x2="500" y2="250" color="#564" width="3" arrowSize="1" />

<br>
<br>

<v-clicks class="text-2xl">

  * 変圧器

  * ニコラ・テスラが開発

  * 鉄芯がない

  * 高い効率

  * ワイヤレス給電の元祖(諸説)

  * 様々な利用

</v-clicks>

<div class="absolute right-5 bottom-0 h-5">
Wikimedia Commons
</div>

<!--
とは変圧器で
ニコラテスラが開発したもの
特徴として一般的な変圧器に使われる鉄心がないこと
電源を入力する1次コイルと出力に用いられる2次コイルとの巻線比が大きいこと
効率が高いこと
現在主流なワイヤレス給電の元祖という説がありまする
他にもいろいろな利用方法として
画面のバックライトの電源
放電実験の教材
がありまする
-->

---

# テスラコイルってどんな仕組み？

<img class="absolute inset-x-0 bottom-0" src="https://i.makeagif.com/media/11-12-2015/VLch1u.gif">

<div class="absolute left-20 top-70 z-20">
  
  

</div>

<!--
初期のテスラコイルとも言えるスパークギャップ式テスラコイルの仕組み

各部の役割説明

交流電源
トランス
コンデンサ
スパークギャップと呼ばれる１対の電極を間を空けて固定したもの
テスラコイル本体の１次コイル
二次コイル
テスラコイルの先端についているドーナッツ上の電極とロイド


交流電源を入力して

コンデンサに充電

スパークギャップで放電してこの回路が出来上がります

コンデンサとコイルでLC共振が発生して
二次コイルに電流が発生し放電

参考
放電距離は
１０KV で１cｍ
-->

---
layout: fact
---

# なぜ<br>音階を<br>取れるのか?

<!--
なぜ先程の動画のように音階を取ることができたのか
-->

---

<div class="bg-white">

  # スピーカーの仕組み

</div>

<img class="absolute inset-x-0 -bottom-75 -z-50" src="https://animagraffs.com/wp-content/uploads/loudspeaker/sound-waves.gif">


<div class="absolute right-5 bottom-0 h-5">
https://animagraffs.com/
</div>

<!--
一般的なスピーカーはアナログ信号で電磁石を動かして音を出している
-->

---

# テスラコイルで音楽がなる仕組み

<img class="w-full z-10" src="https://upload.wikimedia.org/wikipedia/commons/1/1f/PWM_3L.gif">

<div class="absolute top-120 left-30 z-20 text-2xl">
  
  1. アナログ信号をデジタル信号に
  1. テスラコイルの電源をONとOFF
  1. それに合わせて放電
  1. 稲妻が空気を震わせて音がなる

</div>

<div class="absolute right-5 bottom-0 h-5">
Wikimedia Commons
</div>

<!--
しかし，テスラコイルは音源のアナログ信号をデジタル信号に変換して，テスラコイルをOnOffして音程を作り出している
-->

---

# テスラコイルで音を出すときの問題点

<br>

<v-clicks class="text-5xl">

  * 威圧感がある
  * 電力消費が大きい
  * 高価
  * 電磁波を撒き散らす
  * 荒削りな音

</v-clicks>

<arrow v-click x1="640" y1="640" x2="370" y2="510" color="#564" width="3" arrowSize="1" />

<div v-after class="absolute bottom-10 right-10">

  # これを良くしたい!!

</div>

---
layout: fact
---

# 美しい音色を奏で<br>楽器としての可能性を模索する

<!--
そこで私が導き出したRQはこちら

美しい音色を奏で，楽器としての可能性を模索することです。
-->

---
layout: fact
---

# どのようにすれば<br>美しい音を奏でる<br>ことができるか?

---

# 仮説　-どのようにしたら音が変わるか-

<v-clicks class="absolute top-35 text-3xl">

  * 放電の軌跡を制御する
    + 放電長の制御
    + プラズマの発生を制御
    + 同じ軌跡をたどって放電が発生しないようにする
  * 入力信号の工夫
    + アナログ入力をする
    + 入力電力の制御

</v-clicks>

---

# これからの計画

<div class="text-4xl absolute top-35">

  1. スパークギャップ式テスラコイルの制作
  1. テスラコイルの特性計測
  1. 制御回路の設計・試作
  1. 特性の計測
  1. テスラコイルのモデル化

</div>

---

# 参考文献・挿入画像

<div class="text-4xl">

* 寺口　直希(2018)<br>『パルス繰り返し周波数方式に基づき演奏する半導体式テスラコイルの開発』「電気学会論文誌 A （基礎・材料・共通部門誌）」
* 居村 岳広(2009)<br>『電磁界共振結合を用いたワイヤレス電力伝送に関する研究』「電磁界共振結合を用いたワイヤレス電力伝送に関する研究「居村 岳広」

</div>


---

<div class="z-20">

# 補足説明　PWM

</div>

<img class="h-full" src="https://www.lapis-tech.com/jp/tips/wp-content/uploads/2021/10/9346d62afb6e485b8e457fbaa946e4a2.jpg">


---
layout: end
---
