<p align="center">
	<img src="/img/logo.svg" style="width: 200px"></img>
</p>
<p align="center">
	<strong>VanBlog 是一款简洁实用优雅的高性能个人博客系统。支持 HTTPS 证书全自动按需申请、黑暗模式、移动端自适应和评论，内置流量统计与图床，内嵌评论系统，配有完备的、支持黑暗模式、支持移动端、支持一键上传剪切板图片到图床、带有强大的编辑器的后台管理面板。</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/github/v/release/mereithhh/van-blog?display_name=tag" />
  <img src="https://img.shields.io/github/stars/mereithhh/van-blog" />
  <img src="https://img.shields.io/bitbucket/issues/mereithhh/van-blog" />
  <img src="https://github.com/mereithhh/van-blog/workflows/release/badge.svg" />
  <img src="https://img.shields.io/badge/license-GPL%20v3-yellow.svg" />
</p>
<p align="center">
	<strong>项目主页: </strong>  <a target="_blank" href='https://vanblog.mereith.com'>vanblog.mereith.com</a>
</p>
<p align="center">
	<strong>Demo(后台账号密码均为 demo): </strong>  <a target="_blank" href='https://blog-demo.mereith.com'>blog-demo.mereith.com</a>
</p>

## 预览图

![前台-白色](/img/前台-白色.png)
![前台-黑色](/img/前台-黑色.png)
![后台-白色](/img/后台-白色.png)
![后台-黑色](/img/后台-黑色.png)

<p align="center"> 
  <img src="/img/lighthouse.png" style="width: 400px"></img>
</p>

## 特性

- [x] 快到极致的响应速度，Lighthouse 接近满分。
- [x] 独一份的按需全自动 HTTPS，甚至不用填域名。
- [x] 包括完整的前后台和服务端。
- [x] 前台和后台都为响应式设计，完美适配移动端和多尺寸设备。
- [x] 前台和后台都支持黑暗模式，并可自动切换。
- [x] 前台为静态网页（SSG），并支持秒级的增量渲染，每次改动无需重新构建全部页面。
- [x] SEO 和无障碍友好。
- [x] 静态网页，CDN 友好。
- [x] 版本号展示和更新提醒。
- [x] 基于 React，项目工程化，二次开发友好。
- [x] 内置强大的分析功能，可统计访客等数据。并配有精美看板。
- [x] 内嵌评论系统。
- [x] 强大的 markdown 编辑器，支持图表和数学公式，一键插入 more 标记，一键剪切板及本地图片上传
- [x] TOC、草稿、代码复制、访客数、评论数、分类、标签、搜索、加密、友链、打赏、自定义导航栏。
- [x] 多个布局设置，可自定义页面细节。
- [x] 内置图床，并支持各种 OSS 图床、github 图床（外部图床基于 picgo）等。
- [x] 极致轻量化，没有花里胡哨。页面秒切换、图片懒加载。
- [x] docker 一键部署，支持 ARM 平台。
- [x] 支持 GA、百度分析
- [x] 简单易用的后台，支持数据的导出与导入。
- [x] 完善的 API，完全利用本项目后台和服务端，自己写前端或适配其他页面生成器
- [x] 有较完善的日志记录，后台可直接查看登录日志和 Caddy 日志。

## 快速上手

请移步项目文档：[快速上手](https://vanblog.mereith.com/guide/docker.html)

## 常见问题

> [作者 logo 无法加载](https://vanblog.mereith.com/ref/faq.html#%E5%9B%BE%E7%89%87%EF%BC%88%E4%BD%9C%E8%80%85%20logo%EF%BC%89%E5%8A%A0%E8%BD%BD%E4%B8%8D%E5%87%BA%E6%9D%A5)
>
> [http error](https://vanblog.mereith.com/ref/faq.html#%E9%83%A8%E7%BD%B2%E5%90%8E-http-error)
>
> [docker 镜像拉取慢](https://www.runoob.com/docker/docker-mirror-acceleration.html)
>
> [更多常见问题](https://vanblog.mereith.com/ref/faq.html)

## 说明与文档

请移步项目主页： [https://vanblog.mereith.com](https://vanblog.mereith.com)

## CHANGELOG

[CHANGELOG](CHANGELOG.md)

## 谁在用

目前就我自己- -

- [Mereith's Blog](https://www.mereith.com)

## TODO

- [x] 精简前台 js 体积，优化性能
- [x] 精简打包体积
- [x] 集成 HTTPS 和自动证书申请续期
- [x] 后台增加登录日志
- [x] 内嵌评论系统
- [x] 支持 ARM64
- [x] 支持 mermaid 语法
- [x] 替换编辑器为 bytemd（掘金同款）（老的编辑器有些臃肿，复制偶尔会有格式会错乱的问题）
- [x] 导入 md 创建文章/草稿功能
- [x] 标签管理
- [x] 黑暗模式图标样式优化
- [ ] 内嵌评论的邮件通知和 webhook
- [ ] 浏览器消息通知
- [ ] RSS 订阅
- [ ] 增加在特定事件后触发执行自定义代码或 webhook 的扩展能力
- [ ] 精简配置项，尽可能移动到运行时配置
- [ ] 增加一些 e2e 测试，集成到 CI
- [ ] 国际化

## 问题反馈

请提 `issue` ，如无特殊情况会在一天内解决。

## 打赏

如果觉得项目不错的话可以打赏哦。您的支持就是我最大的动力！

打赏时您可以备注名称，我会将您添加至打赏列表中。

<p align="center">
  <img  alt="打赏-微信" src="/img/wechat.jpg"  style="width: 200px;margin-right: 4px;" />
  <img  alt="打赏-支付宝" src="/img/ali-pay.jpg"  style="width: 200px" />
</p>

## Star 趋势图

[![Star History Chart](https://api.star-history.com/svg?repos=mereithhh/van-blog&type=Date)](https://star-history.com/#mereithhh/van-blog&Date)
