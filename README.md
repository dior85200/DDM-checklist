<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <title>法鼓山 11408 台中福田班｜行前確認清單</title>
  <style>
    body {
      font-family: "Noto Sans TC", "Microsoft JhengHei", sans-serif;
      background-color: #f7f7f7;
      padding: 20px;
      line-height: 1.8;
    }
    h1 {
      text-align: center;
    }
    .section {
      background: #ffffff;
      padding: 16px;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    li {
      margin-bottom: 8px;
    }
    input[type="checkbox"] {
      margin-right: 8px;
      transform: scale(1.2);
    }
    .checked {
      text-decoration: line-through;
      color: #999;
    }
  </style>
</head>
<body>

<h1>法鼓山 11408 台中福田班<br>第 6 堂「體驗法鼓山」行前確認清單</h1>

<div class="section">
  <h2>📌 重要提醒</h2>
  <ul>
    <li><label><input type="checkbox">務必於 1/5（一）18:00 前於 Line 群組回報</label></li>
    <li><label><input type="checkbox">取消上山學員，費用轉為護持寶雲寺基金，不另行退費</label></li>
    <li><label><input type="checkbox">集合時間：AM 5:20 寶雲寺對面慢車道上車</label></li>
  </ul>
</div>

<div class="section">
  <h2>🍱 課程提供</h2>
  <ul>
    <li><label><input type="checkbox">早餐</label></li>
    <li><label><input type="checkbox">午齋</label></li>
    <li><label><input type="checkbox">藥石用便當盒（有蓋可扣緊，貼組別姓名）</label></li>
  </ul>
</div>

<div class="section">
  <h2>👕 服裝準備</h2>
  <ul>
    <li><label><input type="checkbox">平底鞋</label></li>
    <li><label><input type="checkbox">後背式背包</label></li>
  </ul>
</div>

<div class="section">
  <h2>🎒 學員自備物品</h2>
  <ul>
    <li><label><input type="checkbox">文具用品</label></li>
    <li><label><input type="checkbox">綠色學員手冊</label></li>
    <li><label><input type="checkbox">水杯</label></li>
    <li><label><input type="checkbox">環保餐具（午餐用）</label></li>
    <li><label><input type="checkbox">藥石空便當盒（有蓋可扣緊，貼組別姓名）</label></li>
    <li><label><input type="checkbox">輕便雨衣</label></li>
    <li><label><input type="checkbox">遮陽帽（不用雨傘）</label></li>
    <li><label><input type="checkbox">外套</label></li>
    <li><label><input type="checkbox">健保卡</label></li>
    <li><label><input type="checkbox">個人用藥</label></li>
  </ul>
</div>

<div class="section">
  <h2>🚌 車資</h2>
  <ul>
    <li><label><input type="checkbox">車上繳交車資 800 元（未交者）</label></li>
  </ul>
</div>

<div class="section">
  <h2>🚗 私人車輛停放處</h2>
  <ul>
    <li><label><input type="checkbox">寶雲寺（自行處理）</label></li>
    <li><label><input type="checkbox">豐原全國加油站（自行處理）</label></li>
  </ul>
</div>

<script>
  const checkboxes = document.querySelectorAll("input[type='checkbox']");
  checkboxes.forEach(cb => {
    cb.addEventListener("change", function () {
      if (this.checked) {
        this.parentElement.classList.add("checked");
      } else {
        this.parentElement.classList.remove("checked");
      }
    });
  });
</script>

</body>
</html>
