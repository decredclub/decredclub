

# **DCR-USDT行情走势图**

<h3 class="txt2">本网站由decred社区开发与维护，可在屏幕下方对行情做出评论与留言！</h3>


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
    /* 在这里添加上述样式代码 */
    .grid-item {
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
      text-align: center;
    }

    .grid-item.red {
      background-color: #ffcccc;
    }

/* 定义风险揭示的颜色的样式 */
.txt1 {
  color: red;
}

/* 设置行情容器的样式 */
.container {
  width: 100%;
  height: 100%;
}
</style>

<script type="text/javascript" src="../js/tv.js"></script>

</head>
<body>
<!-- 创建一个容器用于显示行情图 -->   
<div class="container">
    <div id="tradingview-widget-container2" style="width: 100%; height: 100%;">查看行情需要登陆VPN</div>
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
<br>
<script>
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

