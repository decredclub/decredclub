
# **dcr社区下载中心**

## 点击卡片可以跳转到相关地址下载应用
<!DOCTYPE html>
<html>
<head>
  <title>网页标题</title>
  <style>
/* 设置格子的样式 */
/*.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
}*/

/* 设置格子的共同样式 */
.grid-item {
  height: 80px;
  text-align: center;
  font-size: 30px;
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

.br {
  background-color: #E74C00;
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
      Decred钱包
    </div>
    <p>
    Decred官方推荐钱包。  
    </p>
     <br>    
    <div class="grid-item dex" onclick="location.href='https://dex.decred.org/'">
    DCRDEX原子交换
    </div> 
     <br>
    <p>
    Decred 去中心化交易所 (DEX) 是一个系统，可以通过熟悉的基于市场的 API 实现不同类型区块链资产的去信任化交易。DEX是一种基于原子互换技术的跨链交换的非托管解决方案。  
    </p>
         <br>
    <div class="grid-item br" onclick="location.href='https://bisonrelay.org/download/'">
    bison relay 社交平台
    </div> 
    <br>
    <p>
    Bison Relay 是一种基于 Decred 的通信工具，它支持言论自由、自由联想，并且可以作为完全独立的 Web 替代堆栈。Bison Relay 是一种异步客户端-服务器协议，它大量使用 Decred 闪电网络，其中每条消息都经过加密发送，元数据最小化，并通过 LN 小额支付进行支付。Bison Relay 服务器是无账户的，每条消息都是单独处理的，在发送和接收之前都需要付费。Bison Relay 将支付、消息传递和社交媒体紧密集成，并实现了向订阅者发帖、订阅用户帖子、转发帖子、回复帖子和对帖子发表评论的点对点社交媒体功能。  
    </p>
   </div> 
<!-- 创建一个容器用于显示行情图 -->   

<div class="container">
</div>
<h3 class="txt1">备注：本网站仅用于客观信息的集中展示，不提供任何投资指导。所有的投资决策和风险由个人自行承担。</h3>
<br>

</body>
</html>


