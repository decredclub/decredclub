

# **欢迎来到德信俱乐部（Welcome to decred club！）**


<h3 class="txt2">本网站由decred社区开发与维护</h3>
<h3 class="txt2">网站主要分为3大块内容，dcr资讯信息，中文文档，应用中心</h3>
<p class="txt2">dcr资讯信息：decred行情，decred最新的开发进展、及其加密货币相关的资讯信息</p>
<p class="txt2">中文文档：为方便中文读者更好的阅读decred文档和交流，对于英文基础好的朋友可以直接查看原版文档，如果有任何错误欢迎大家提出，我们一起改正！</p>
<p class="txt2">应用中心：主要方便中文环境下载decred的相关软件和使用软件</p>
<!DOCTYPE html>
<html>
<head>
  <title>网页标题</title>
  <style>
/* 设置格子的样式 */
.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
}

/* 设置格子的共同样式 */
.grid-item {
  height: 200px;
  text-align: center;
  font-size: 45px;
  color: white;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 10px; /* 添加圆角效果 */
  box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1); /* 添加阴影效果 */
}
/* 定义风险揭示的颜色的样式 */
.txt1 {
  color: red;
}

/* 定义不同格子颜色的样式 */
.red {
  background-color: blue;
}

.blue {
  background-color: blue;
}

.green {
  background-color: blue;
}

.yellow {
  background-color: blue;
}

.purple {
  background-color: purple;
}

.orange {
  background-color: orange;
}

/* 设置行情容器的样式 */
.container {
  width: 100%;
  height: 100%;
}

  </style>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
</head>
</head>
<body>
  <div class="grid">
    <div class="grid-item red" onclick="joinTelegramGroup()">
      加入电报群
    </div>
    <div class="grid-item blue" onclick="location.href='newsletter.html'">
      加入微信群
    </div>
    <div class="grid-item green" onclick="location.href='market.html'">
      分享到推特
    </div>
    <div class="grid-item yellow" onclick="location.href='docs.html'">
      官方文档
    </div>
    <div class="grid-item purple" onclick="location.href='community.html'">
      加入社区
    </div>
    <div class="grid-item orange" onclick="location.href='another-page.html'">
      另一个页面
    </div>
   </div> 
<!-- 创建一个容器用于显示行情图 -->   
<h2 id="__comments">decred行情信息</h2>
<div class="container">
    <H3>DCR-USDT</H3>
    <div id="tradingview-widget-container2" style="width: 100%; height: 100%;"></div>
	<H3>DCR-BTC</H3>
    <div id="tradingview-widget-container1" style="width: 100%; height: 100%;"></div>
</div>

<script >
function joinTelegramGroup() {
  window.location.href = 'https://t.me/decredzh';  // 替换为电报群的URL
}
</script>

<script type="text/javascript">
    new TradingView.widget(
      {
        "width": "100%",
        "height": "300px",
        "symbol": "BINANCE:DCRBTC", // 设置行情图的交易对
        "interval": "1D", // 设置时间间隔，例如日线 ("D")
        "timezone": "Asia/Taipei",
        "theme": "light",
        "style": "1",
        "locale": "zh",
        "toolbar_bg": "#f1f3f6",
        "enable_publishing": false,
        "allow_symbol_change": true,
        "container_id": "tradingview-widget-container1"
        }
      );
</script>
 
<script type="text/javascript">
    new TradingView.widget(
      {
        "width": "100%",
        "height": "400px",
        "symbol": "BINANCE:DCRUSDT", // 设置行情图的交易对
        "interval": "1D", // 设置时间间隔，例如日线 ("D")
        "timezone": "Asia/Taipei",
        "theme": "light",
        "style": "1",
        "locale": "zh",
        "toolbar_bg": "#f1f3f6",
        "enable_publishing": false,
        "allow_symbol_change": true,
        "container_id": "tradingview-widget-container2"
        }
      );
</script>




</body>
</html>
<h3 class="txt1">备注：本网站仅用于客观信息的集中展示，不提供任何投资指导。所有的投资决策和风险由个人自行承担。</h3>
<h3 id="__comments">欢迎对Decred德信俱乐部做出评论和提出宝贵建议！</h3>
<h3 id="__comments">可通过授权github登陆进行评论。</h3>
<br>
<!-- Insert generated snippet here -->
<script src="https://giscus.app/client.js"
        data-repo="Cagedbird1/decred-giscus"
        data-repo-id="R_kgDOJjLJEg"
        data-category="Announcements"
        data-category-id="DIC_kwDOJjLJEs4CWfeh"
        data-mapping="url"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>
<script>
    var giscus = document.querySelector("script[src*=giscus]")
    /* Set palette on initial load */
    var palette = __md_get("__palette")
    if (palette && typeof palette.color === "object") {
      var theme = palette.color.scheme === "slate" ? "dark" : "light"
      giscus.setAttribute("data-theme", theme) 
    }

    /* Register event handlers after documented loaded */
    document.addEventListener("DOMContentLoaded", function() {
      var ref = document.querySelector("[data-md-component=palette]")
      ref.addEventListener("change", function() {
        var palette = __md_get("__palette")
        if (palette && typeof palette.color === "object") {
          var theme = palette.color.scheme === "slate" ? "dark" : "light"

          /* Instruct Giscus to change theme */
          var frame = document.querySelector(".giscus-frame")
          frame.contentWindow.postMessage(
            { giscus: { setConfig: { theme } } },
            "https://giscus.app"
          )
        }
      })
    })
  </script>

