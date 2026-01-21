<!-- 上課你準備好了嗎? -->
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <title>法鼓山體驗法鼓山－行前確認清單</title>
  <style>
    body {
      font-family: "Noto Sans TC", Arial, sans-serif;
      background-color: #f5f5f5;
      padding: 20px;
      line-height: 1.8;
    }

    h1, h2 {
      color: #3a3a3a;
    }

    .card {
      background: #ffffff;
      border-radius: 10px;
      padding: 20px;
      max-width: 800px;
      margin: auto;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    li {
      margin-bottom: 10px;
    }

    label {
      cursor: pointer;
    }

    input[type="checkbox"] {
      margin-right: 10px;
      transform: scale(1.2);
    }

    input[type="checkbox"]:checked + span {
      text-decoration: line-through;
      color: gray;
      opacity: 0.7;
    }

    .note {
      color: #b00020;
      font-weight: bold;
    }
  </style>
</head>

<body>
<div class="card">
  <h1>法鼓山 11408 台中福田班</h1>
  <h2>第6堂「體驗法鼓山」行前確認清單</h2>

  <h3>📌 課程提醒事項</h3>
  <ol>   
    <li>取消上山者，費用將轉為護持寶雲寺護持功德金</li>
    <li>
<ul>
  <li>
    <strong>集合時間：</strong>
    <ul>
      <li><strong>第 1、3、4 車</strong>：AM 5:20（寶雲寺對面慢車道）</li>
      <li>
        <strong style="color:red;">第 2 車</strong>（寶雲寺）：
        AM 5:10（<strong style="color:red;">寶雲寺對面慢車道→出發前往豐原</strong>）
      </li>
      <li>
        <strong style="color:red;">第 2 車</strong>（豐 原）：
        AM 5:40（<strong style="color:red;">豐原全國加油站出發</strong>）
      </li>
    </ul>
  </li>
  <li>
    <strong>用餐資訊：</strong>
    <ul>
      <li>提供早餐（海苔飯捲）、午齋（好收納即可）、藥石（有蓋可扣緊）</li>
      <li>
        <span style="color: #555;">藥石容器規範請注意：</span>
        <ul>
          <li>請貼上「組別＋姓名」</li>
          <li><strong>請勿使用雙層、有內層、玻璃材質</strong></li>
        </ul>
      </li>
    </ul>
  </li>
</ul>


  <h3>👕 服裝準備</h3>
  <ul>
    <li><label><input type="checkbox"><span>好走路鞋子（一定要好走的鞋，會讓菩薩們參觀總本山）</span></label></li>
    <li><label><input type="checkbox"><span>後背式背包（避免大包小包，一個包包拎了就走）</span></label></li>
    <li><label><input type="checkbox"><span>保暖小物（毛帽、圍巾、手套、暖暖包）</span></label></li>
  </ul>

  <h3>🎒 學員自備物品</h3>
  <ul>
    <li><label><input type="checkbox"><span>文具用品</span></label></li>
    <li><label><input type="checkbox"><span>綠色學員手冊</span></label></li>
    <li><label><input type="checkbox"><span>水杯</span></label></li>
    <li><label><input type="checkbox"><span>環保餐具（午餐用）</span></label></li>
    <li>
      <label>
        <input type="checkbox">
        <span>藥石空便當盒（上車時統一收進整理箱，需可堆疊勿用矽膠，勿用雙層、有內層、玻璃材質）</span>
      </label>
    </li>
    <li><label><input type="checkbox"><span>遮陽帽／輕便雨衣（為方便行動，不用傘）</span></label></li>
    <li><label><input type="checkbox"><span>外套</span></label></li>
    <li><label><input type="checkbox"><span>健保卡</span></label></li>
    <li><label><input type="checkbox"><span>個人用藥（含暈車藥）</span></label></li>
  </ul>

  <h3>🚌 交通費用與私人車輛停放</h3>
  <ul>
    <li><label><input type="checkbox"><span>未繳車資者，車上收取 800 元包含：車資、保險、飯捲及護持道場（總本山及寶雲寺）</span></label></li>
    <li><label><input type="checkbox"><span>寶雲寺（自行處理）</span></label></li>
    <li><label><input type="checkbox"><span>豐原全國加油站（自行處理）</span></label></li>
  </ul>

  <button onclick="document.querySelectorAll('input[type=checkbox]').forEach(cb => cb.checked=false)">
    清除所有勾選
  </button>
</div>
</body>
</html>
