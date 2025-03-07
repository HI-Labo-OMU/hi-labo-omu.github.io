---
layout: page
title: 学生の研究➀
permalink: /student-research1/
---

<style>
  .research-content {
    padding-top: 10px;
    padding-bottom: 10px;
  }

  /*スマホ用のスタイル*/
  @media (max-width: 768px) {
    .student-research-img {
      width: 100%;
      height: auto;
    }
  }

  /*タブレット用のスタイル*/
  @media (max-width: 1024px) {
    .student-research-img {
      width: 75%;
      height: auto;
    }
  }
</style>

<h1>
効率よく推薦を行うことができる推薦システムの研究をしています
</h1>
<p class="research-content">
YouTubeの「あなたへのおすすめ」、Amazonの「この商品を買った人はこんな商品も買っています」などの機能には、推薦システムが用いられています。複数の候補となるコンテンツから、ユーザにとって価値のあるものを推薦するシステムのことを、推薦システムと呼びます。より良質なコンテンツを、より早い時間で提供する推薦システムについての研究をしています。具体的には、推薦システムの1種である協調フィルタリングという技術と、教師なし学習のクラスタリングを組み合わせた手法を研究しています。
</p>

{: align="center"}
<img class="student-research-img" src="/public/img/Amazon&YouTube.png" width="50%">

<h1>
協調フィルタリングとは
</h1>
<p class="research-content">
協調フィルタリングとは、類似したユーザを探し出し、そのユーザの購買履歴（視聴履歴）等を参考にして、推薦を行う推薦システムです。下記の図のように、ユーザA～Dの、商品A～Eに対する購入履歴を考えます。ここで、〇は購入済み、×は未購入の商品であるとします。ここで、ユーザAはまだ商品Eを購入しておらず、ユーザAに商品Eを推薦するべきかどうかを考えます。他のユーザを見ると、ユーザAとユーザDは、商品A～Dの購入履歴が全く同じになっています。そして、ユーザDは商品Eを購入したことがあります。つまり、ユーザAに商品Eを推薦すれば、購入する可能性が高いと考え、ここではユーザAに商品Eを推薦します。このように、ユーザ間の嗜好の類似性に基づいて推薦を行うのが、協調フィルタリングという技術です。
</p>

{: align="center"}
<img class="student-research-img" src="/public/img/CF.png" width="40%">

<h1>
クラスタリングとは
</h1>
<p class="research-content">
クラスタリングとは、データを自動的に分類する技術で、特徴が似ているデータから成るグループ（クラスター）の構造や特徴を解析します。例えば、下記の左図のような2次元のデータ点を分類するとしたら、どのように分類すべきでしょうか。人間が見れば、右図のように3つのクラスターがあると一目でわかりますが、コンピュータにはそれが可能でしょうか。クラスタリングでは、コンピュータにアルゴリズムによってクラスター構造を発見させることを目的としています。
</p>

{: align="center"}
<img class="student-research-img" src="/public/img/Clustering.png" width="50%">

<h1>
協調フィルタリングとクラスタリングを組み合わせて、推薦精度の向上を目指す
</h1>
<p class="research-content">
研究では、上記の協調フィルタリングとクラスタリングを組み合わせて、より推薦精度の高い推薦システムの構築を目指しています。YoutubeやAmazonのユーザは、全員が同じような嗜好を持っているわけではありません。従来の協調フィルタリングのモデルでは、全てのユーザに対して同じモデルを考えていました。これを受けて研究では、まずユーザを、嗜好が似ているクラスターに分類します。そして、クラスターごとに協調フィルタリングのモデルを考えます。これにより、クラスターごとの嗜好に特化したモデルを考えることができ、より良質なコンテンツをユーザに提供することができます。
</p>

<h1>
論文はこちら
</h1>
[＞＞k-Means型スイッチングFactorization Machineの一検討](https://www.jstage.jst.go.jp/article/jacc/65/0/65_1494/_article/-char/ja/)  
[＞＞FCM-Induced Switching Fuzzy Factorization Machine for Collaborative Filtering](https://ieeexplore.ieee.org/document/10309695)