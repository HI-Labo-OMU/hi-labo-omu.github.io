---
layout: page
title: 大学院生の就職先
permalink: /jobhunting/
---
<style>
/* 全体の背景と文字色 */
/* 見出しスタイル */
h1 {
  padding-bottom: 10px;
  margin-top: 10px;
}
h2 {
  margin-top: 10px;
}
h3 {
  margin-top: 10px;
}
section.job-year h2 {
  color: #2a5772;
  font-size: 1.5em;
  margin-bottom: 10px;
  text-align: center; /* 中央揃えにして視覚的に目立たせる */
}
/* セクション全体に枠と背景色を追加 */
section.job-year {
  background-color: #f8f9fa; /* 背景色を淡いグレーに */
  border: 2px solid #b0d7d5; /* 淡い色で枠を設定 */
  padding: 20px; /* 内側の余白 */
  margin-bottom: 20px; /* セクションごとの間隔 */
  border-radius: 10px; /* 角を丸くする */
}

/* 見出し（年度）を強調 */
/* リストアイテムを3列に並べる */
ul.job-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0px; /* 各リストアイテム間のスペース */
  padding: 0;
  margin: 0;
  list-style-type: none; /* リストマーカーを消す */
  align-items: stretch; /* アイテムの高さを揃える */
}

ul.job-list li {
  background-color: #b0d7d5;
  color: #2a5772;
  flex: 1 1 calc(33.33% - 20px); /* 3列に並べるための幅を調整 */
  padding: 15px;
  margin: 0 5px 10px 5px; /* 左右に少し余白を追加 */
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease;
  display: block;
  box-sizing: border-box; /* パディングを含めてサイズ計算 */
  min-height: 50px; /* アイテムの最小高さを設定して揃える */
}

ul.job-list li.dummy {
  visibility: hidden;
  padding: 15px;
  margin: 0 5px 10px 5px;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease;
  display: block;
  box-sizing: border-box; /* パディングを含めてサイズ計算 */
}

/* PC用のスタイル */
@media (min-width: 1024px) {
  ul.job-list li.dummy {
    flex: 1 1 calc(33.33% - 20px); /* 3列表示用の幅 */
  }
}

/* タブレット用のスタイル */
@media (max-width: 1023px) {
  ul.job-list li.dummy {
    flex: 1 1 calc(50% - 20px); /* 2列表示用の幅 */
  }
}

.dummy {
  visibility: hidden;
}

.intro {
    margin-top: 20px; /* 上に20pxのマージンを追加 */
    margin-bottom: 20px; /* 下に20pxのマージンを追加 */
}

@media screen and (max-width: 600px) {
  ul.job-list li {
    flex: 1 1 100%; /* 1列表示 */
  }
}

/* タブレット対応: 幅が900px以下の場合 */
@media screen and (max-width: 900px) {
  ul.job-list li {
    flex: 1 1 calc(50% - 20px); /* 2列表示 */
  }
}
ul.job-list li {
  word-wrap: break-word; /* 単語全体で改行を行う */
  word-break: keep-all;  /* 日本語のような全角文字は単語の途中で改行しない */
  hyphens: auto;         /* 必要に応じてハイフンを追加して改行を整える（ブラウザ依存） */
}

ul.job-list {
  display: flex; /* GridからFlexに変更 */
  flex-wrap: wrap; /* 複数行に折り返し */
  gap: 10px; /* 各リストアイテム間のスペース */
}

ul.job-list li {
  flex: 1 1 calc(33.33% - 20px); /* PC向けに3列の幅を設定 */
}

/* PC用のスタイル */
@media (min-width: 1024px) {
  ul.job-list li {
    flex: 1 1 calc(33.33% - 20px); /* 3列に並べる */
  }
}

/* タブレット用のスタイル */
@media (max-width: 1023px) {
  ul.job-list li {
    flex: 1 1 calc(50% - 20px); /* 2列に並べる */
  }
}

/* スマートフォン用のスタイル */


</style>


# 大学院生の就職活動スケジュール

<p class="intro">当研究室では研究だけでなく就職活動にも力を入れています。<br>以下は学生が修士1年次から修士2年次にかけての就活スケジュールです。</p>

<div style="text-align: center;">
<img src="/public/img/schedules.png" alt="就職活動スケジュール" style="width: 100%; max-width: 600px;">
</div>

<p class="intro">学生たちはこのスケジュールに従い、就職活動、授業、研究を両立しています。<br>
また研究室内ではエントリーシート添削などのサポートも受けられます。
</p>
# 大学院生の就職先

<p class="intro">次に当研究室の大学院生の就職先を紹介します。</p>

<section class="job-year">
  <h2>2023年度</h2>
  <ul class="job-list">
    <li>ディー・エヌ・エー</li>
    <li>シャープ</li>
    <li>パナソニックコネクト</li>
    <li>日鉄ソリューションズ</li>
    <li>NTTデータ関西</li>
    <li>朝日ネット</li>
  </ul>
</section>

<section class="job-year">
  <h2>2022年度</h2>
  <ul class="job-list">
    <li>ソフトバンク</li>
    <li>ヤフー</li>
    <li>日本電気</li>
    <li>KDDI</li>
    <li>SMBC日興証券</li>
    <li>オプテージ</li>
    <li>レンゴー</li>
    <li>MonotaRO</li>
  </ul>
</section>

<section class="job-year">
  <h2>2021年度</h2>
  <ul class="job-list">
    <li>パナソニック</li>
    <li>ダイキン工業</li>
    <li>ヤフー</li>
    <li>サイバーエージェント (2)</li>
    <li>京セラドキュメントソリューションズ</li>
  </ul>
</section>

<section class="job-year">
  <h2>2020年度</h2>
  <ul class="job-list">
    <li>NTT西日本 (2)</li>
    <li>パナソニック</li>
    <li>シャープ (2)</li>
    <li>イーソル</li>

  </ul>
</section>

<section class="job-year">
  <h2>2019年度</h2>
  <ul class="job-list">
    <li>ヤフー</li>
    <li>NTT西日本 (2)</li>
    <li>パナソニック (2)</li>
    <li>ダイキン工業</li>
  </ul>
</section>

<section class="job-year">
  <h2>2018年度</h2>
  <ul class="job-list">
    <li>トヨタ自動車</li>
    <li>ダイキン工業</li>
    <li>住友電気工業 (2)</li>
    <li>シャープ</li>

  </ul>
</section>

<section class="job-year">
  <h2>2017年度</h2>
  <ul class="job-list">
    <li>三菱電機</li>
    <li>本田技研工業</li>
    <li>ダイキン工業</li>
    <li>シンプレクス</li>
  </ul>
</section>

<section class="job-year">
  <h2>2016年度</h2>
  <ul class="job-list">
    <li>三菱電機</li>
    <li>長谷川鉄工</li>
  </ul>
</section>

<section class="job-year">
  <h2>2015年度</h2>
  <ul class="job-list">
    <li>日立製作所 (2)</li>
    <li>NTT西日本</li>
    <li>日本電気</li>
    <li>野村総合研究所</li>
  </ul>
</section>

<section class="job-year">
  <h2>2014年度</h2>
  <ul class="job-list">
    <li>トヨタ自動車 (2)</li>
    <li>大和総研</li>
    <li>日立製作所</li>
    <li>日興システムソリューションズ</li>
    <li>三菱自動車工業</li>
    <li>住友電気工業</li>
  </ul>
</section>

<section class="job-year">
  <h2>2013年度</h2>
  <ul class="job-list">
    <li>日立製作所 (2)</li>
    <li>楽天</li>
    <li>阪急電鉄</li>
    <li>ダイキン工業</li>
    <li>野村総合研究所</li>
    <li>沖アドバンストコミュニケーションズ</li>
  </ul>
</section>

<section class="job-year">
  <h2>2012年度</h2>
  <ul class="job-list">
    <li>関西電力</li>
    <li>日立製作所</li>
    <li>三菱東京UFJ</li>
    <li>ダイキン工業</li>
    <li>データスタジアム</li>
  </ul>
</section>

<section class="job-year">
  <h2>2011年度</h2>
  <ul class="job-list">
    <li>朝日新聞社</li>
    <li>NTTコミュニケーションズ</li>
  </ul>
</section>

<section class="job-year">
  <h2>2010年度</h2>
  <ul class="job-list">
    <li>パナソニック</li>
    <li>シャープ</li>

  </ul>
</section>

<section class="job-year">
  <h2>2009年度</h2>
  <ul class="job-list">
    <li>関西電力</li>
    <li>シャープ (2)</li>
    <li>キーエンス</li>
  </ul>
</section>

<section class="job-year">
  <h2>2008年度</h2>
  <ul class="job-list">
    <li>松下電器 (2)</li>
    <li>松下電工</li>
    <li>シャープ</li>
    <li>日本電気</li>
    <li>デンソー</li>
  </ul>
</section>

<section class="job-year">
  <h2>2007年度</h2>
  <ul class="job-list">
    <li>デンソー</li>
    <li>シャープ</li>
    <li>三菱電機</li>
  </ul>
</section>

<section class="job-year">
  <h2>2006年度</h2>
  <ul class="job-list">
    <li>シャープ</li>
    <li>関西電力</li>
    <li>大和証券SMBC</li>
    <li>オリエンタルランド</li>
  </ul>
</section>

<section class="job-year">
  <h2>2005年度</h2>
  <ul class="job-list">
    <li>松下電器</li>
    <li>日本電気</li>
    <li>東レ</li>
  </ul>
</section>

<section class="job-year">
  <h2>2004年度</h2>
  <ul class="job-list">
    <li>松下電器</li>
    <li>西日本電信電話</li>
    <li>住友信託銀行</li>
    <li>日本総研</li>
    <li>日本電気</li>
    <li>三菱商事</li>
  </ul>
</section>

<section class="job-year">
  <h2>2003年度</h2>
  <ul class="job-list">
    <li>シャープ</li>
    <li>住友電気工業</li>
    <li>三井住友海上火災</li>
    <li>日本IBM</li>
    <li>KDDI</li>
  </ul>
</section>

<section class="job-year">
  <h2>2002年度</h2>
  <ul class="job-list">
    <li>日本生命</li>
    <li>富士通</li>
    <li>三菱電機</li>
    <li>松下電器</li>
    <li>日本総研</li>
    <li>日本電気</li>
  </ul>
</section>

<script>
function addDummies() {
  const jobLists = document.querySelectorAll('.job-year'); // すべてのjob-yearセクションを取得

  jobLists.forEach(jobYear => {
    const yearHeading = jobYear.querySelector('h2').innerText; // 年度を取得
    const jobList = jobYear.querySelector('.job-list'); // リストを取得
    const items = jobList.querySelectorAll('li:not(.dummy)'); // ダミーを除いたリスト項目を取得
    if (items.length === 0) return; // アイテムがない場合はスキップ

    const screenWidth = window.innerWidth;
    const jobListWidth = jobList.offsetWidth;

    // 2021年度の場合はダミーを追加しない
    if (yearHeading.includes('2021年度')) {
      console.log('2021年度なのでダミーを追加しません');
      return;
    }

    // 最初のアイテムの幅を取得
    const firstItem = items[0];
    const itemWidth = firstItem.offsetWidth;

    // アイテムの幅に基づき、1行に収まるアイテム数（列数）を計算
    const itemsPerRow = Math.floor(jobListWidth / itemWidth);

    if (itemsPerRow < 1) return; // 列数が1未満なら処理しない

    // 各行ごとのアイテムの高さを確認し、行数を計算
    let currentTop = items[0].getBoundingClientRect().top;
    let rowsNeeded = 1;

    items.forEach(item => {
      const itemTop = item.getBoundingClientRect().top;

      // アイテムが新しい行に移動した場合
      if (itemTop !== currentTop) {
        rowsNeeded++; // 行数を増やす
        currentTop = itemTop; // 新しい行の高さに更新
      }
    });

    // 最後の行のアイテム数を確認
    const remainingItemsInLastRow = items.length % itemsPerRow;
    const dummyCount = remainingItemsInLastRow === 0 ? 0 : itemsPerRow - remainingItemsInLastRow;

    // 既存のダミー項目を削除
    jobList.querySelectorAll('.dummy').forEach(dummy => dummy.remove());

    // 必要な数だけダミー項目を追加
    if (dummyCount > 0 && dummyCount < itemsPerRow) { // ダミーが行に収まるように制限
      for (let i = 0; i < dummyCount; i++) {
        const dummyItem = document.createElement('li');
        dummyItem.classList.add('dummy');
        dummyItem.style.width = itemWidth + 'px'; // ダミーの幅を他のアイテムと揃える
        dummyItem.style.visibility = 'hidden'; // ダミーを隠してレイアウトのためだけに追加
        jobList.appendChild(dummyItem);
      }
    }

    console.log(`スクリーン幅: ${screenWidth}, リスト項目数: ${items.length}, 列数: ${itemsPerRow}, 行数: ${rowsNeeded}, ダミー数: ${dummyCount}`);
  });
}

// ウィンドウリサイズ時にダミー項目を調整
window.addEventListener('resize', addDummies);

// ページロード時にダミー項目を調整
document.addEventListener('DOMContentLoaded', addDummies);

</script>
