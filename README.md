# Leili Codex Skin

一个面向 macOS Codex 桌面端的本地主题中心。可浏览、应用、验证和恢复主题，并在 GitHub 发布新主题后自动提示更新。

> 非官方项目，与 OpenAI 无隶属、赞助或背书关系。不会修改官方 `app.asar`，主题通过本机回环接口临时应用，可随时恢复官方界面。

## 主题展示

| 晓·红云月夜 | 一笔千山 |
|---|---|
| ![晓·红云月夜](showcase/akatsuki-red-cloud.jpg) | ![一笔千山](showcase/ink-mountains.jpg) |

| Easter Islands · 仰望星河 | 奇点 · 黑洞之眼 |
|---|---|
| ![Easter Islands](showcase/easter-islands.jpg) | ![奇点 · 黑洞之眼](showcase/singularity-black-hole.jpg) |

| 禅静 |
|---|
| ![禅静](showcase/zen-stillness.jpg) |

## 下载与安装

1. 安装并至少启动一次官方 Codex macOS 桌面端。
2. 从 [Releases](https://github.com/Raven7979/Leili-Codex-Skin/releases/latest) 下载 `Leili-Codex-Skin-1.1.0.zip`。
3. 解压后双击“安装 Leili Codex Skin.command”；首次运行若被 macOS 拦截，请右键选择“打开”。
4. 打开 `Leili Codex Skin.app`，在“雷厉的主题中心”选择并应用主题。

支持 macOS 12 及以上版本。APP 使用官方 Codex 自带的签名 Node.js，不捆绑官方应用或运行时。

## 主题更新

APP 启动后会定期检查 GitHub 更新清单；发现新主题时显示界面提示和 macOS 通知。手动点击“检查主题更新”也可以立即检查。

下载的主题包必须同时通过 GitHub HTTPS、文件大小、SHA-256、ZIP 路径和主题结构检查，才会写入本机主题库。被替换的旧主题会自动备份。

## 隐私

- 主题中心仅监听 `127.0.0.1`，操作接口由随机本地令牌保护。
- APP 不上传对话、侧边栏、项目名称、文件路径或截图。
- 网络请求仅用于读取本仓库的更新清单和下载发布包。
- 本仓库只包含发布必需文件和专门制作的主题预览图。

## 说明

软件运行组件基于 Codex Dream Skin Studio 的 MIT 许可代码。主题图片、角色、商标及第三方素材不属于 MIT 软件许可范围，使用者应遵守所在地法律和对应权利人的要求。详见 [NOTICE.md](NOTICE.md)。
