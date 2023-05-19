# 加入 Matrix 上的 Decred 社区

---

## 什么是矩阵？

Matrix（矩阵）是一个安全、开放的消息传递平台，深受 Decred 承包商的欢迎。借助桥接软件 ，Matrix用户可以与 Discord 等其他 Decred 平台上的用户进行交流。Matrix 提供第一方注册；注册不需要识别信息或第三方服务。用户应注意，某些功能（例如密码重置）确实需要电子邮件地址。有关 Matrix 的安全功能和可用客户端的更多信息，请参阅[Matrix 项目主页](https://matrix.org/)。

要加入 Matrix，您需要选择客户端和家庭服务器。Matrix 支持众多客户端和家庭服务器，但对于初次使用的用户，我们推荐最受支持的 Matrix 客户端：Element（以前称为 Riot）和 Decred 的服务器。使用 Decred 家庭服务器可以更轻松地找到 Decred 聊天室，输入`decred.org`您的 ID，并允许您在 Decred 的家庭服务器与其他家庭服务器断开连接时继续发送消息。

---

## 创建您的帐户

使用开源 Matrix 客户端[Element](https://element.io/get-started)访问 Decred 的频道。

Element 支持多种平台：

- 桌面应用
- iOS
- 安卓
  - 谷歌应用商店
  - F-机器人
- 网页浏览器
  - [chat.decred.org 网站](https://chat.decred.org/)
  - [Element 的网络应用程序](https://app.element.io/)

创建帐户时，选择“高级”以选择使用自定义家庭服务器并输入`https://matrix.decred.org`.

![选择主服务器](https://docs.decred.org/img/matrix/matrix-02-select-home-server.png)

如果您填写了电子邮件字段，请检查您的收件箱以验证您的帐户。

![创建账户](https://docs.decred.org/img/matrix/matrix-03-create-account.png)

进入后，您可以使用“探索”功能开始探索不同的频道。

![探索房间](https://docs.decred.org/img/matrix/matrix-04-explore-rooms.png)

大多数 Decred 项目都有自己的频道，我们鼓励您加入您想要贡献的领域。

![房间清单列表](https://docs.decred.org/img/matrix/matrix-05-room-list.png)

任何人都可以创建新频道。随意为您的 Decred 相关项目或朋友组制作一个。

![创建房间](https://docs.decred.org/img/matrix/matrix-06-create-room.png)

Decred 是一个建设者社区。价格和交易讨论有自己的`#trading:decred.org`渠道。

![交易讨论频道](https://docs.decred.org/img/matrix/matrix-07-trading-channel.png)

请记住，Matrix 频道是 Decred 社区协作、工作和闲逛的地方。尊重。

---

## 使用移动应用程序

`https://matrix.decred.org`从您的移动设备登录需要您通过选中“使用自定义服务器选项（高级）”框在 Element 移动应用程序中设置家庭服务器。如果您没有帐户，请使用上面的指南创建它。

首次登录后，您的房间列表将为空。要查找 Decred 频道，请点击右上角的菜单点，然后点击“全球搜索”，然后浏览 Decred 的房间目录。

![移动应用](https://docs.decred.org/img/matrix/matrix-08-mobile.png)
<script type="module">
  import { init } from 'https://unpkg.com/@waline/client@v2/dist/waline.mjs';

  init({
    el: '#waline',
    // ...
    comment: true, // 评论数统计
  });
</script>
<ul>
  <li>
    当前页面浏览量:
    <span class="waline-pageview-count"/>
  </li>
</ul>
<script type="module">
  import { pageviewCount } from 'https://unpkg.com/@waline/client/dist/pageview.mjs';
  pageviewCount({
    serverURL: '<https://decred-test2.vercel.app/>',
    path: window.location.pathname,
  // 可选的，用于自定选择器，默认为 `'.waline-pageview-count'`
    // selector: 'waline-pageview-count',

    // 可选的，是否在获取时增加访问量，默认为 `true`
    // update: true,
  });
</script>

