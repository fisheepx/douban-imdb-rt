# 豆瓣电影显示IMDb和烂番茄评分插件

在豆瓣电影页面显示对应的IMDb评分和烂番茄评分（影评人，观众）数据。

## 效果展示

![效果展示](assets/screenshots/v1/preview.png)

## 功能
- 显示IMDb评分和评分人数
- 显示烂番茄专业评分和观众评分
- 点击评分可跳转到对应网站查看详情

## 安装
1. 首先需要安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 然后点击 [这里](Greasy Fork链接待定) 安装脚本

## 使用说明

### 首次使用
首次使用时，脚本会请求访问 IMDb 和烂番茄网站的权限：

<div style="display: flex; justify-content: flex-start; gap: 20px; margin-bottom: 20px;">
    <div>
        <img src="assets/screenshots/permission-imdb.png" width="400" alt="IMDb权限请求">
        <p style="text-align: center; color: #666; margin-top: 5px;">IMDb</p>
    </div>
    <div>
        <img src="assets/screenshots/permission-rottentomatoes.png" width="400" alt="烂番茄权限请求">
        <p style="text-align: center; color: #666; margin-top: 5px;">烂番茄</p>
    </div>
</div>

建议点击"总是允许"以获得最佳使用体验。如果不小心点击了其他选项，可以在 Tampermonkey 的设置页面中重新授权。

### 使用须知
由于脚本需要从 IMDb 和烂番茄网站获取数据：
- 确保你的网络环境可以访问 IMDb (www.imdb.com) 和烂番茄 (www.rottentomatoes.com)
- 如果无法访问这些网站，对应的评分将无法显示
- 如在IMDb中无此电影词条则无法显示
- 某些电影

## 兼容性
- Edge 最新版
- Chrome 最新版
- Firefox 最新版
- Safari 最新版

## License
[MIT License](LICENSE)