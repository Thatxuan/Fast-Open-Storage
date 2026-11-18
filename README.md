中文
纯前端 Minecraft 资源存储器 —— 模组、资源包、光影、整合包一站式检索。

✨ 功能

· 🔍 双平台搜索：Java 版（Modrinth API）+ 国际基岩版（内置精选数据），支持分页、按游戏版本/加载器/分类筛选、英文描述自动翻译
· 🧍 3D 皮肤预览：正版查询 / LittleSkin 查询 / 本地皮肤，支持经典与纤细模型
· 🎬 动作切换：走路、跑步、待机、飞行、旋转，状态本地持久化
· ⬇️ 导出皮肤 PNG；LittleSkin 模式下支持导出披风
· 🎭 本地披风导入，状态持久化
· 📸 头像截取：从 3D 模型截取头部生成头像，支持自定义用户名，头像与名字本地持久化
· 📁 本地文件管家：导入 .jar / .zip / .mcpack / .mcaddon 自动识别平台；.zip 可手动选择光影 / 资源包 / 整合包类型
· 🖱️ 拖拽导入：电脑端直接把文件拖进窗口即可识别，手机端保留点击选择入口
· ⬇️ 下载管理与本地文件记录：均持久化，支持单条删除与清空
· 🎨 7 套主题：晴空白、星耀黑、暗耀紫、暮光橙、海盐蓝、青提绿，外加跟随系统；切换零掉帧
· 🔧 设置分组卡片：外观 / 皮肤与头像 / 数据与缓存 / 关于
· 🛡️ 底层加固：localStorage 统一命名空间与版本号、读写 try/catch、外部跳转 noopener noreferrer、错误日志本地留底
· 💻 跨平台字体栈，修复 Windows 字体错乱；电脑端布局、hover、滚动条适配
· 👆 小彩蛋：点击左上角图标戳一戳，连戳 10 下会爆出一堆 💢

🚀 使用

直接用浏览器打开 index.html 即可，无需构建、无需后端、无需安装依赖。

⚠️ 已知问题

· 头像截取在部分设备上可能生成空白图片：WebGL drawing buffer 在合成阶段被清空导致，修复进行中。
· LittleSkin 登录功能目前处于测试阶段，登录失败为正常现象，后续版本会逐步完善。

📦 技术栈

原生 HTML / CSS / JavaScript · three.js · skinview3d · Modrinth API

📄 许可

个人项目，仅供学习与交流使用。

English
A pure front-end Minecraft resource hub — search mods, resource packs, shaders and modpacks in one place.

✨ Features

· 🔍 Dual-platform search: Java Edition (Modrinth API) + Bedrock Edition (curated built-in data), with pagination, filters by game version / loader / category, and automatic EN→ZH translation
· 🧍 3D skin preview: Mojang lookup / LittleSkin lookup / local skin, with classic and slim models
· 🎬 Action switching: walk, run, idle, fly, rotate — state persisted locally
· ⬇️ Export skin as PNG; export cape in LittleSkin mode
· 🎭 Import local cape, state persisted
· 📸 Avatar capture: crop the head region from the 3D model, custom username, avatar and name persisted locally
· 📁 Local file manager: auto-detect platform for .jar / .zip / .mcpack / .mcaddon; choose shader / resource pack / modpack type for .zip
· 🖱️ Drag & drop import on desktop; tap-to-select on mobile
· ⬇️ Download manager and local file records: both persisted, with per-item delete and clear-all
· 🎨 7 themes: Clear Day, Starry Black, Dark Purple, Sunset Orange, Ocean Blue, Mint Green, plus Follow System; flicker-free switching
· 🔧 Grouped settings cards: Appearance / Skin & Avatar / Data & Cache / About
· 🛡️ Hardening: namespaced localStorage with schema version, try/catch on storage access, noopener noreferrer on external links, local error log
· 💻 Cross-platform font stack (fixes Windows font glitches); desktop layout, hover and scrollbar adaptation
· 👆 Easter egg: poke the top-left logo — 10 pokes in a row triggers a 💢 explosion

🚀 Usage

Open index.html directly in a browser. No build step, no backend, no dependencies.

⚠️ Known Issues

· Avatar capture may produce a blank image on some devices: the WebGL drawing buffer is cleared during compositing. Fix in progress.
· LittleSkin login is currently in beta. Login failures are expected and will be improved in future releases.

📦 Tech Stack

Vanilla HTML / CSS / JavaScript · three.js · skinview3d · Modrinth API

📄 License

Personal project, for learning and sharing purposes only.
