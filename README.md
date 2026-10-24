# SayPlain Legal Documents

本仓库托管 SayPlain（人话）iOS 应用的上架合规页面：

| 文件 | 用途 | 填入位置 |
|---|---|---|
| `privacy.html` | 隐私政策（中英双语） | App Store Connect → App 信息 → 隐私政策 URL |
| `terms.html` | 服务条款（中英双语） | App 内「设置 → 服务条款」链接 |

## 在线地址（GitHub Pages 启用后）

- 隐私政策：https://sps2013.github.io/sayplain-legal/privacy.html
- 服务条款：https://sps2013.github.io/sayplain-legal/terms.html

## 本地预览

直接用浏览器打开 `privacy.html` / `terms.html` 即可，无需构建、无依赖。
页面右上角可切换中文 / English。

## 关于本应用的数据处理声明

SayPlain 完全在设备端运行（Apple Vision OCR + Apple Foundation Models），不收集、不上传、不共享任何个人数据，无账号体系、无服务器、无广告与统计 SDK。详见隐私政策。

## 维护说明

- 修改文案后直接提交到 `main` 分支，GitHub Pages 会自动重新发布（1-2 分钟生效）。
- 政策/条款变更时，请同步更新页面顶部的「更新日期」。
- 联系方式邮箱如变更，需同时更新两份 HTML 中的 mailto 链接。
