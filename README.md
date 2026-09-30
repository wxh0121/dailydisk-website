# DailyDisk 官网

DailyDisk（macOS 磁盘增长监视器）的产品网页与用户文档。纯静态页面，没有构建步骤。

- `index.html`：首页（30 秒开场影片、逐日账本、八项监控能力、工作原理、实测数据、隐私、安装）
- `docs.html`：用户文档（安装、首次设置、日常使用、读懂报告、隐私、命令行、卸载、已知限制、疑难排查）
- `assets/`：网页使用的影片、海报、配图与图标
- `icons/`：全套图标（透明圆角 PNG 16–1024、`favicon.ico`、`DailyDisk.icns`、macOS 规格 1024 图标、原始图标）

## 本地预览

直接双击 `index.html` 即可；或在此目录运行：

```bash
python3 -m http.server 8000
```

然后打开 http://localhost:8000 。

## 用 GitHub Pages 发布

仓库 **Settings → Pages → Build and deployment**，Source 选 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)`，保存后稍等即可访问。

## 说明

- 网页字体来自 Google Fonts；离线时自动回退到系统字体。
- 下载按钮与文档中的源码链接指向 https://github.com/Nu1sance/DailyDisk ，如需更改，在 `index.html` 和 `docs.html` 中搜索 `Nu1sance/DailyDisk` 替换。
- 1080p60 高质量母版影片（约 178 MB）超过 GitHub 单文件 100 MB 上限，未放入仓库；网页内使用的是 13 MB 的网页版。
