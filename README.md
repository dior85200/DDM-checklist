<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>法鼓山體驗法鼓山－行前確認清單</title>
  <style>
    body {
      font-family: "Noto Sans TC", "Microsoft JhengHei", Arial, sans-serif;
      /* 背景底圖 */
      background-image: url('https://fagushan.ddm.org.tw/files/file_pool/1/0M029788458513049105/01-P74120160924010001s.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
      margin: 0;
      padding: 20px;
      line-height: 1.8;
    }
    .card {
      background: rgba(255, 255, 255, 0.5);
      backdrop-filter: blur(5px);
      border-radius: 15px;
      padding: 30px;
      max-width: 700px;
      margin: auto;
      box-shadow: 0 8px 32px rgba(0,0,0,0.2);
    }
    h1 { color: #b00020; font-size: 24px; text-align: center; margin-top: 0; }
    h2 { color: #3a3a3a; font-size: 18px; text-align: center; border-bottom: 2px solid #ddd; padding-bottom: 10px; }
    h3 { color: #444; background: #f0f0f0; padding: 5px 15px; border-left: 5px solid #b00020; margin-top: 25px; }
    ul, ol { padding-left: 20px; }
    li { margin-bottom: 12px; }
    label { cursor: pointer; display: flex; align-items: flex-start; }
    input[type="checkbox"] { margin-top: 7px; margin-right: 12px; transform: scale(1.3); }
    input[type="checkbox"]:checked + span { text-decoration: line-through; color: #888; }
    
    .btn-container { text-align: center; margin-top: 30px; margin-bottom: 30px; }
    button { background-color: #b00020; color: white; border: none; padding: 10px 25px; border-radius: 5px; cursor: pointer; font-size: 16px; }
    
    /* 課表圖片樣式 */
    .schedule-img {
      width: 100%;
      max-width: 550px;
      display: block;
      margin: 15px auto;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .footer-note { font-size: 0.8em; color: #888; text-align: center; margin-top: 20px; border-top: 1px dashed #ccc; padding-top: 10px; }
  </style>
</head>

<body>
<div class="card">
  <h1>法鼓山 11408 台中福田班</h1>
  <h2>第6堂「體驗法鼓山」行前確認清單</h2>

  <h3>📌 課程提醒事項</h3>
  <ol>
    <li>取消上山者，費用將轉為護持寶雲寺護持功德金</li>
    <li><strong>集合時間：</strong>
      <ul>
        <li><strong>第 1、3、4 車</strong>：AM 5:20（寶雲寺對面慢車道）</li>
        <li><strong style="color:red;">第 2 車</strong>：AM 5:10（寶雲寺）/ AM 5:40（豐原全國加油站）</li>
      </ul>
    </li>
    <li><strong>用餐資訊：</strong> 提供早餐、午齋、藥石。容器請貼姓名，<strong>嚴禁玻璃/雙層/內層材質</strong>。</li>
  </ol>

  <h3>👕 服裝準備</h3>
  <ul>
    <li><label><input type="checkbox"><span>好走路鞋子（需參觀總本山）</span></label></li>
    <li><label><input type="checkbox"><span>後背式背包（避免大包小包）</span></label></li>
    <li><label><input type="checkbox"><span>保暖小物（毛帽、圍巾、手套、暖暖包）</span></label></li>
  </ul>

  <h3>🎒 學員自備物品</h3>
  <ul>
    <li><label><input type="checkbox"><span>文具用品、綠色學員手冊</span></label></li>
    <li><label><input type="checkbox"><span>水杯、個人環保餐具</span></label></li>
    <li><label><input type="checkbox"><span><strong>藥石空便當盒</strong>（需可堆疊，勿用矽膠/玻璃/雙層）</span></label></li>
    <li><label><input type="checkbox"><span>遮陽帽／輕便雨衣（不用傘）</span></label></li>
    <li><label><input type="checkbox"><span>外套、健保卡、個人用藥</span></label></li>
  </ul>

  <h3>🚌 交通與費用</h3>
  <ul>
    <li><label><input type="checkbox"><span>未繳車資者（800元），請於車上繳交</span></label></li>
    <li><label><input type="checkbox"><span>確認私人車輛停放地點</span></label></li>
  </ul>

  <div class="btn-container">
    <button onclick="document.querySelectorAll('input[type=checkbox]').forEach(cb => cb.checked=false)">
      清除所有勾選重來
    </button>
  </div>

  <hr style="border: 0; border-top: 1px double #ddd;">

  <h3 style="background: #ececec;">📅 附件：當日課程表預覽</h3>
  <img src="11408寶雲班課程表.jpg" alt="11408寶雲班課程表" class="schedule-img">

  <div class="footer-note">
    © 法鼓山聖嚴書院福田班 課程資訊<br>
    底圖來源：台灣旅圖 (taiwantravelmap.com)
  </div>
</div>
</body>
</html>
