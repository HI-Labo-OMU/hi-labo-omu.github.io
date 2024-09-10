---
layout: page
title: Q & A
permalink: /qa/
---

<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #B0D7D5; /* 全体背景色を淡い色に */
  }
  
  .qa-item {
    background-color: #FFFFFF; /* 各QAの背景色は白に設定 */
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .qa-question {
    color: #4790BB; /* 質問部分に濃い青色を設定 */
    font-weight: bold;
    cursor: pointer;
    margin: 0;
    padding: 10px 0;
    background-color: #2A5772; /* 質問部分の背景に濃い色を */
    padding: 15px;
    border-radius: 5px;
    color: #FFFFFF; /* 質問部分の文字色は白に */
  }

  .qa-answer {
    display: none;
    color: #333;
    background-color: #B0D7D5; /* 回答部分に淡い背景色を適用 */
    padding: 15px;
    border-radius: 5px;
  }

  .qa-item:hover {
    border-color: #4790BB; /* ホバー時に枠の色を変更 */
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    var questions = document.querySelectorAll('.qa-question');
    questions.forEach(function(question) {
      question.addEventListener('click', function() {
        var answer = this.nextElementSibling;
        if (answer.style.display === "block") {
          answer.style.display = "none";
        } else {
          answer.style.display = "block";
        }
      });
    });
  });
</script>

<div class="qa-item">
  <h3 class="qa-question">Q: コアタイムはありますか？</h3>
  <div class="qa-answer">
    <p>基本的にコアタイムはありません．プライベートと研究のスケジュールは各々が自主的に管理します．</p>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 研究とアルバイトは両立できますか？</h3>
  <div class="qa-answer">
    <p>コアタイムがないため，他の研究室と比較してもアルバイトは可能な環境です．</p>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 研究は大変ですか？</h3>
  <div class="qa-answer">
    <p>研究が行き詰まった場合でも，先生方が手厚くサポートしてくださります．卒論，修論発表や学会発表がある場合は，論文やスライドを完成させなければいけないため，少し大変かもしれません．</p>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: ゼミについて教えてください</h3>
  <div class="qa-answer">
    <p>基本的に1コマ分の時間で週に2回行われます．</p>
    <p>内容としては以下のようになります．</p>
    <p><strong>前期</strong></p>
    <ul>
      <li>教授による「ファジィクラスタリング」の概説</li>
      <li>B4による英語文献の輪講</li>
      <li>研究の中間報告</li>
    </ul>
    <p><strong>後期</strong></p>
    <ul>
      <li>研究の中間報告</li>
      <li>卒論・修論の発表練習</li>
    </ul>
    <p><strong>不定期</strong></p>
    <ul>
      <li>学会の発表練習</li>
    </ul>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 学会発表の機会はありますか？</h3>
  <div class="qa-answer">
    <p>あります．基本的にHI研究室の学生は，修士課程を修了するまでに国内学会と国際学会を1回ずつ発表する機会があります．以下は学会での発表スケジュールの一例です．</p>
    <p><strong>B4: 秋～冬</strong></p>
    <ul>
      <li>国内学会</li>
    </ul>
    <p><strong>M1: 春～夏</strong></p>
    <ul>
      <li>国際学会</li>
    </ul>
    <p><strong>M1: 夏～秋</strong></p>
    <ul>
      <li>国際学会</li>
    </ul>
    <p><strong>M2: 夏～秋</strong></p>
    <ul>
      <li>国内・国際学会</li>
    </ul>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 研究環境について教えてください</h3>
  <div class="qa-answer">
    <p>配属された際には，1人1台のデスクトップパソコンと2台のモニターが貸し与えられます．</p>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 研究室配属について教えてください</h3>
  <div class="qa-answer">
    <p>情報工学科では学生が各研究室の希望順位を提出し，成績順で研究室に配属されます．そのため，年によって研究室の人気順は異なります．</p>
    <p>具体的なGPAの数値をお教えすることはできませんが，HI研究室に関しては毎年人気の研究室なので，成績が高くないと入れないかもしれません．</p>
    <p>自分の第一希望の研究室に入れるように，1年生の頃からしっかり勉強しておきましょう．</p>
  </div>
</div>

<div class="qa-item">
  <h3 class="qa-question">Q: 院試勉強は大変ですか？</h3>
  <div class="qa-answer">
    <p>院試の１ヶ月前には前期のゼミが終了するため，余裕をもって院試勉強に取り組むことができます．勉強をする中でわからないことがあったらいつでも研究室の先輩に相談してください．</p>
  </div>
</div>


