# 豆b番——豆瓣电影显示IMDb和烂番茄评分

<div align="center">
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/alternatives/icon_original.png" width="128" height="128"/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/equals.png" width="78" height="78" style="margin: 20px 20px;"/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/douban.png" width="128" height="128"/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/plus.png" width="78" height="78" style="margin: 20px 20px;"/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/imdb.png" width="128" height="128"/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/plus.png" width="78" height="78" style="margin: 20px 20px; "/>
<img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/rottentomatoes.png" width="128" height="128"/>
</div>

## 效果展示

![效果展示](https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/screenshots/v1/preview.png)

## 功能
- 显示IMDb评分和评分人数
- 显示烂番茄专业评分和观众评分
- 点击评分可跳转到对应网站查看详情

## 安装
1. 首先需要安装 [Tampermonkey](https://www.tampermonkey.net/) 等浏览器扩展
2. 然后点击 [这里](https://greasyfork.org/zh-CN/scripts/527823-%E8%B1%86%E7%93%A3%E7%94%B5%E5%BD%B1-imdb%E5%92%8C%E7%83%82%E7%95%AA%E8%8C%84%E8%AF%84%E5%88%86%E6%98%BE%E7%A4%BA) 安装本插件

## 使用说明

### 首次使用
首次使用时，脚本会请求访问 IMDb 和烂番茄网站的权限：

<table>
  <tr>
    <td valign="top"><img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/screenshots/permission-imdb.png" width="400"/></td>
    <td valign="top"><img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/screenshots/permission-rottentomatoes.png" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><em>IMDb 权限请求页面</em></td>
    <td align="center"><em>烂番茄权限请求页面</em></td>
  </tr>
</table>

建议点击"**<ins>总是允许</ins>**"以获得最佳使用体验。如果不小心点击了其他选项，可以在 Tampermonkey 的设置页面中重新授权。

### 使用须知
由于脚本需要从 IMDb 和烂番茄网站获取数据：
- 确保你的网络环境可以访问 IMDb (<ins>www.imdb.com</ins>) 和烂番茄 (<ins>www.rottentomatoes.com</ins>)
- 如果无法访问这些网站，对应的评分将无法显示
- 如在IMDb中无此电影词条则无法显示
- 某些在IMDb上无词条的电影无法显示评分
- 烂番茄评分可能因错误识别电影名称而显示错误

### 关于评分
- 烂番茄图标含义：[About Rotten Tomatoes®](https://www.rottentomatoes.com/about)
- IMDb评分常见问题：[IMDb Ratings FAQ](https://help.imdb.com/article/imdb/track-movies-tv/ratings-faq/G67Y87TFYYP6TWAV?showReportContentLink=false#)

## 兼容性
- Edge 最新版
- Chrome 最新版
- Firefox 最新版
- Safari 最新版

## License
[MIT License](LICENSE)

## 项目地址
<a href="https://github.com/fisheepx/douban-imdb-rt" target="_blank">
    <img src="https://raw.githubusercontent.com/fisheepx/douban-imdb-rt/main/assets/icon/github.png" width="99" height="99"/>
</a>