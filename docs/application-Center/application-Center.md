
# **下载中心**

## 点击卡片可以跳转到相关钱包下载地址下载钱包
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

/* 定义不同格子颜色的样式 */
.decred {
  background-color: #0A1A4B;
}

.BTC {
  background-color: #FF9500;
}

.ml {
  background-color: #4C4C4C;
}

.eth {
  background-color: #9ABAFB;
}

.ltc {
  background-color: #335794;
}

.dex {
  background-color: #3637C3;
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
    <div class="grid-item decred" onclick="location.href='https://decred.org/zh/wallets/'">
      decred德信钱包
    </div>
    <div class="grid-item dex" onclick="location.href='https://dex.decred.org/'">
    DCRDEX原子交换
    </div> 
    <div class="grid-item BTC" onclick="location.href='https://bitcoin.org/zh_CN/choose-your-wallet'">
      比特币钱包
    </div>
    <div class="grid-item ml" onclick="location.href='https://web.getmonero.org/zh-cn/downloads/'">
      门罗币钱包
    </div>
    <div class="grid-item eth" onclick="location.href='https://ethereum.org/zh/wallets/'">
      以太坊钱包
    </div>
    <div class="grid-item ltc" onclick="location.href='https://litewallet.io/#zhCN'"> 
      莱特币钱包
    </div>
   </div> 
<!-- 创建一个容器用于显示行情图 -->   

<div class="container">
</div>
<h3 class="txt1">备注：本网站仅用于客观信息的集中展示，不提供任何投资指导。所有的投资决策和风险由个人自行承担。</h3>
<br>

</body>
</html>

<!-- Insert generated snippet here -->
<script src="https://giscus.app/client.js"
        data-repo="decredclub/decredclub-giscus"
        data-repo-id="R_kgDOJlFlxA"
        data-category="Announcements"
        data-category-id="DIC_kwDOJlFlxM4CWmoo"
        data-mapping="pathname"
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


