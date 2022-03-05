---
id: upyun
title: 又拍云存储设置教程
hide_title: true
---

## 一、注册又拍云账号

点击 <a href="https://console.upyun.com/register/?invite=B1K7kNtvt"  target="_blank">这里</a> 即可注册又拍云账号。

> 已有账号可忽略。另外，建议加入 <a href="https://www.upyun.com/league"  target="_blank">又拍云联盟</a>，申请通过后每年都有代金券发放，个人使用完全足够，不然使用前请注意余额。
> 
> 因为关于又拍云存储设置的文章只有一篇几年前的，所以在此教程基于 <a href="https://bbs.halo.run/u/ryanwang"  target="_blank">@Ryan Wang</a> 大佬的文章 <a href="https://bbs.halo.run/d/150"  target="_blank">又拍云存储设置教程</a> 进行的了修改和更新。(按本教程基本上是没有啥问题的......大概吧🧐

## 二、新建云存储

[![1636542462](https://tupian.clotliu.com/0354560ac6154ee18570ae2bc8aa2ff2.jpg)](https://tupian.clotliu.com/0354560ac6154ee18570ae2bc8aa2ff2.jpg)

[![1636539766-650163-apb09zgiysq7uydhzvo](https://tupian.clotliu.com/fb6cf308e80bcc4f4c376f182e345ea7.png)](https://tupian.clotliu.com/fb6cf308e80bcc4f4c376f182e345ea7.png)

> 注意：第一次使用需要新建一个操作员，权限全勾上。应用场景选择网页图片即可。

## 三、绑定域名

[](https://i.loli.net/2019/07/20/5d3296c6a654743117.jpg)[![Snipaste_2019-07-20_12-21-11.jpg](https://i.loli.net/2019/07/20/5d3296c6a654743117.jpg)](https://i.loli.net/2019/07/20/5d3296c6a654743117.jpg)

[](https://i.loli.net/2019/07/20/5d3296fca0f5f83331.jpg)[![Snipaste_2019-07-20_12-22-06.jpg](https://i.loli.net/2019/07/20/5d3296fca0f5f83331.jpg)](https://i.loli.net/2019/07/20/5d3296fca0f5f83331.jpg)

> 绑定之后还不能用，还需要在服务器添加解析

[![1636540297-512652-image](https://tupian.clotliu.com/00b2e77d18424820c7d37f17024635fc.png)](https://tupian.clotliu.com/00b2e77d18424820c7d37f17024635fc.png)

[![1636540342-689871-image](https://tupian.clotliu.com/822aa86438ba381789f339914b55c6cf.png)](https://tupian.clotliu.com/822aa86438ba381789f339914b55c6cf.png)

## 四、缩略图策略

我们需要新建一个缩略图策略以供博客后台展示所用。

[![1636540810-274621-image](https://tupian.clotliu.com/0caaa97a401d89e883c4390b936cd3b2.png)](https://tupian.clotliu.com/0caaa97a401d89e883c4390b936cd3b2.png)

> 记住这个间隔标识符，这是用于标识处理后的图片的，在图片链接末尾加上间隔标识符+图片处理版本名即可。

[![1636540910-245473-image](https://tupian.clotliu.com/f9e2372f79ff942978af69fd069379e8.png)](https://tupian.clotliu.com/f9e2372f79ff942978af69fd069379e8.png)

> 新建图片处理 - 自定义版本

[![1636540986-893655-image](https://tupian.clotliu.com/9dff32715067df9c92f3c57f6010f0f1.png)](https://tupian.clotliu.com/9dff32715067df9c92f3c57f6010f0f1.png)

> 版本名称自己设置就好，缩略方式建议限定宽度和高度。完了保存即可。

## 五、Halo 后台设置

[![1636541922-154535-m-at-htf4sza3fja-at-705l](https://tupian.clotliu.com/8d7281743f28b00730c120bd17bddf3e.png)](https://tupian.clotliu.com/8d7281743f28b00730c120bd17bddf3e.png)

1. 存储位置选择又拍云
2. 域名填写自己在又拍云绑定的域名即可，主要有没有 https，如果需要 https，自己去又拍云申请一个绑定到这个域名就行了。

[![1636541100-864849-image](https://tupian.clotliu.com/cd6da8d752d304fcce67b447ee8d2ef3.png)](https://tupian.clotliu.com/cd6da8d752d304fcce67b447ee8d2ef3.png)

[![1636541144-112295-image](https://tupian.clotliu.com/3fce0155d67bdc5fd5b81cf3247077e1.png)](https://tupian.clotliu.com/3fce0155d67bdc5fd5b81cf3247077e1.png)

[![1636541172-646532-image](https://tupian.clotliu.com/3ba592bba4853f56290234d5d1673be9.png)](https://tupian.clotliu.com/3ba592bba4853f56290234d5d1673be9.png)

会跳到以下界面(大概吧:🧐:)，如果不对就打开这个网站`https://console.upyun.com/toolbox/ssl/`

[![1636541336-323111-image](https://tupian.clotliu.com/f29176e3ca5304d139511053db3c3873.png)](https://tupian.clotliu.com/f29176e3ca5304d139511053db3c3873.png)

申请好或是上传好自己的证书之后可以在下面的位置查看

[![1636541565-788120-image](https://tupian.clotliu.com/2b39f2c27b1c8d91cba65025b4735567.png)](https://tupian.clotliu.com/2b39f2c27b1c8d91cba65025b4735567.png)

[![1636541587-575611-image](https://tupian.clotliu.com/e63fe4c99fb5d56d152a46cf9d63ae4a.png)](https://tupian.clotliu.com/e63fe4c99fb5d56d152a46cf9d63ae4a.png)

可以在这里打开打开 `HTTPS 访问`和 `强制 HTTPS`

3. 空间名称即你新建的存储空间名称。
4. 操作员名称和密码选择新建云存储空间的时候的即可。
5. 文件目录自定义。
6. 缩略图处理策略即 `间隔标识符+图片处理版本名称`。

## 六、最后

去附件管理上传图片试试吧！
