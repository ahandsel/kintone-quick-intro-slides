---
theme: /
favicon: ./kintone-graphics/KDP_favicon.png
layout: image
image: ./kintone-graphics/kintone-background-v2.svg
title: kintone Web データベースとは
exportFilename: kintone-quick-intro-slides
export:
  format: pdf
  timeout: 30000
  withToc: true
presenter: true
download: true
highlighter: prism
lineNumbers: false
monaco: dev
remoteAssets: true
selectable: true
record: true
routerMode: history
aspectRatio: 16/9
canvasWidth: 980
themeConfig:
  primary: '#008080'
  dark: '#038378'
  darker: '#076E65'
  darkest: '#065A53'
  light: '#10B5A7'
  lighter: '#0CCABA'
  lightest: '#06E5D2'
fonts:
  sans: Raleway
  serif: Raleway
  mono: Raleway
hideInToc: true
addons:
  - '@katzumi/slidev-addon-qrcode'
---

<div class="mb-4 top-15 left-45" style="text-align: right">
  <div class="text-6xl text-white text-opacity-100" style="font-weight: 600">
    kintone Web データベース
  </div>
  <div><br/></div>
  <div class="text-4xl text-white text-opacity-100" style="font-weight: 600">
    あなたのプロジェクトのバックエンド <mdi-database-cog/>
  </div>
  <div><br/></div>
  <div
    class="text-2xl text-white text-opacity-100"
    style="font-weight: 600; line-height: 2"
  >
    <a href="https://kintone.dev/">kintone開発者プログラム<mdi-book/></a>
  <br>
  </div>
  <div
    class="text-2xl text-white text-opacity-100"
    style="font-weight: 450; line-height: 2"
  >
    <a href="https://ahandsel.github.io/kintone-quick-intro-slides/">スライド<mdi-presentation-play/></a>
    <br>
    <a href="https://github.com/ahandsel/kintone-quick-intro-slides ">コード<mdi-language-markdown/></a>
  </div>
</div>

<div
  class="absolute bottom-13 right-9"
  style="
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  "
>
  <div>
    <a
      href="https://ahandsel.github.io/kintone-quick-intro-slides/"
      target="_blank"
      alt="kintoneへのイントロスライド"
    >
    <QRCode
      value="https://ahandsel.github.io/kintone-quick-intro-slides/"
      width="100"
      height="100"
    />
    </a>
  </div>
</div>
<div class="absolute bottom-7 right-12">
  <div
    @click="$slidev.nav.next"
    class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center"
  >
    次のページへ進むにはスペースキーを押してください →
  </div>
</div>


---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
title: 概要 <tabler-color-swatch/>
---

# 概要 <tabler-color-swatch/>

<br>

### ① kintoneとは？ <mdi-database-cog/>

‣ kintoneの特徴

### ② kintoneの使い方は？ <mdi-school-outline/>

‣ 例のプロジェクト

### ③ どうやって始めるか？ <mdi-pencil/>

‣ 楽しさが始まるとき


---
layout: my-two-columns
title: kintoneとは？ <mdi-database-cog/>
---

# kintoneとは？ <mdi-database-cog/>

<br>

::left::

<div class="text-4xl top-1" style="font-weight:500;user-select:text;line-height: 1.6;" >
  kintoneは<strong>ローコード</strong>プラットフォームで、簡単かつ迅速に<strong>ウェブデータベースを構築できます</strong>！ <mdi-tools/>
</div>


::right::

![スマートフォンからデータを交換するkintone](/kintone-graphics/Fast_Database.png)


---
layout: my-two-columns
title: あなたのプロジェクトのウェブデータベース <mdi-sitemap/>
---

# あなたのプロジェクトのウェブデータベース <mdi-sitemap/>

<br>

::left::

<div class="text-4xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
  kintoneを使用して、データの<strong>保存</strong>や<strong>管理</strong>を行います！
</div>


::right::

![スマートフォンからデータを交換するkintone](/kintone-graphics/Kintone_DataExchange.png)


---
layout: image-right
image: ./kintone-graphics/Traditional_Database.png
equal: true
---

# 伝統的なデータベース <bx-sad/>

<br>

<div class="text-2xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
  データベースについての<strong>高度な理解が必要です</strong>
  <br><br>
  <strong>サーバー</strong>は<strong>常時稼働</strong>し、アクセスするためには維持が必要です
</div>


---
layout: image-right
image: ./kintone-graphics/Build_App_Demo.gif
equal: true
---

# kintoneデータベース <bx-happy />

<br>

<div class="text-2xl" style="font-weight:500;user-select:text;line-height: 1.6;" >
直感的な<strong>ドラッグ・アンド・ドロップ</strong>のGUIでデータベースが作成されます
<br><br>
<strong>ユーザーによるサーバー設定</strong>の必要はありません
</div>


---
layout: image-right-bar
image: ./kintone-graphics/Animal_6_flip.png
---

# kintoneの使い方は？ <mdi-school-outline/>

<br>

## kintoneデータベースデータへのアクセス方法

<br>

## ‣ ウェブブラウザ <gg-browser/>

<br>

## ‣ REST API <gg-database/>


---
layout: my-two-columns
title: ブラウザを通じてkintoneDBにアクセス <gg-browser/>
---

# ブラウザを通じてkintoneDBにアクセス <gg-browser/>

<br>

::left::

## GUIを使用して:

<br>

* #### データベースの作成と編集 <mdi-database/>

<br>

* #### レコードの表示/追加/編集 <mdi-folders/>

<br>

* #### JSカスタマイズの追加 <mdi-code/>

::right::

![YOUR_SUBDOMAIN.kintone.com からkintoneアプリを構築](/kintone-graphics/Kintone_From_Browser.png)


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Request.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  REST APIを通じてkintoneDBにアクセス <mdi-exchange/>
  <br><br>
</div>


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Response.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  REST APIを介したKintone DBへのアクセス <mdi-exchange/>
  <br><br>
</div>


---
layout: image-center
image: ./kintone-graphics/Kintone_REST_API_Flow.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  REST APIを介したKintone DBへのアクセス <mdi-exchange/>
  <br><br>
</div>

<!--
Kintoneでいくつかのデータベースを作成し、データを追加したとしましょう。
あなたのアプリから、あなたのKintone環境、アクセスしたいデータベースID、認証のためのAPIトークンを指定してREST APIを呼び出し、結果を取得することができます。
ほとんどの言語、例えばnode.js、python、php、RubyなどからREST APIを呼び出すことができます。
-->

---
layout: image-right
image: ./kintone-graphics/Example_Samurai.gif
equal: true
title: 例 - IoT侍の剣 <tabler-slice />
---

## IoT侍の剣 <tabler-slice />
[@RyBB](https://github.com/RyBB)によって作成 - [記事](https://dev.to/will_yama/kintone-at-maker-faire-tokyo-2020-215k)

侍の剣を使って、できるだけ早く敵を切り倒すことに挑戦！

* センサーが剣の動作スピードを記録
* Kintoneはゲーム、スコアボード、IoTデータをホスト
* ユーザーが勝つと、人形の磁気ヘッドが落ちる


---
layout: image-right-bar
image: ./kintone-graphics/Example_flowerpot-bar.gif
title: 例 - ヒボタン / 花瓶プロジェクト <mdi-robot-outline />
---

## ヒボタン / 花瓶プロジェクト <mdi-robot-outline />
[野武幸之介](https://protopedia.net/prototyper/nobuyukifurukawa)によって作成 - [ヒボたん](https://peraichi.com/landing_pages/view/hibotan)

* **Kintoneをバックエンドとして使用**して、センサーデータを保存する動く花瓶。
* センサーは[mbedマイクロコントローラー](https://os.mbed.com/handbook/mbed-Microcontrollers)に取り付けられ、定期的にNode.jsを介してKintoneにデータを送信。
* Node.jsは時間をかけてKintoneのセンサー値をチェックし、花瓶のモーターを制御。
* 花瓶はより日当たりの良い場所へ移動。

<!--
* 目的: 参加者が超高速のアニメ侍のように感じさせる
* 剣: 出し入れの動きの速度を検出する磁石センサー
* 電磁石を備えた人形で、その頭が落ちる
* 剣と人形用に2つのM5Stickマイクロコントローラーを使用
* スコアランキングはKintoneアプリに保存された情報を表示し、ゲームを終了した参加者のスコアは自動的にREST APIを介して記録された。
-->

---
layout: image-right
image: ./kintone-graphics/Example_SpaceInvaders.gif
equal: true
title: 例 - スペースインベーダー <mdi-space-invaders />
---

## スペースインベーダー <mdi-space-invaders />

[@will_yama](https://twitter.com/will_yama) と [@ahandsel](https://github.com/ahandsel/) によって作成 - [記事](https://dev.to/will_yama/having-fun-with-phaser-io-games-web-databases-4f08)

Kintoneアプリ上で[スペースインベーダーゲーム](https://phaser.io/examples/v2/games/invaders)を実行！

ゲームの仕様（エイリアンの数、エイリアンの体力など）はKintoneのレコードとして指定されます。

高得点もKintoneに保存可能。


---
layout: image-right
equal: true
image: ./kintone-graphics/Kintone_New.png
title: あなたのKintoneを手に入れよう <mdi-server />
---

## 無料のKintoneウェブデータベースを手に入れよう <mdi-server />

<br>

#### [Kintone.dev/new](https://Kintone.dev/new)にアクセス！

開発者ライセンス登録フォームに記入して、無料のKintoneサブドメインを取得しよう！

* ✅ ChromeかFirefoxを使用（_Safariは不可_）
* ⚡ クッキーを先に受け入れる
* 🚧 サブドメイン名には小文字、数字、ハイフン(-)のみ使用
* 例: `weekend-hacker4life`


---
layout: image-right-bar
image: ./kintone-graphics/Animal_3_flip.png
title: 助けを得るには？ <mdi-help-circle/>
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  助けを得るには？ <mdi-help-circle/>
</div>

<br>

Kintoneをプロジェクトのデータベースとして使用するためのリソースはこちら！

| <mdi-home/>     | [kintone.dev](https://kintone.dev/)                                          | APIドキュメントとチュートリアルを読む |
| --------------- | ---------------------------------------------------------------------------- | ------------------------- |
| <mdi-lifebuoy/> | [forum.kintone.dev](https://forum.kintone.dev/)                              | 質問を投稿する            |
| <mdi-youtube/>  | [@KintoneDeveloperProgram](https://www.youtube.com/@KintoneDeveloperProgram) | チュートリアルを見る           |


---
layout: image-right-bar
image: ./kintone-graphics/Animal_10_flip.png
---

# お礼のギフト！ <mdi-rocket/>

<br>

### Kintoneをプロジェクトに使用していただいたお礼として、Kintoneグッズをプレゼントします！

<br><br>

<img src="/kintone-graphics/KDP_Swag.png" alt="ボトル、バックパック、PopSocketsなど！" style="width: 60%;">
