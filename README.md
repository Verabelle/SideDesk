# 📌 SideDesk – 桌面侧边卡片

> 开机即见的待办清单 + 日历小工具，逾期任务自动下沉，永不遗忘。
![预览图，你可以把背景图换成自己喜欢的](image-1.png)

## ✨ 功能

- 今日待办（添加、完成、编辑、删除）
- 已完成任务自动置底并显示灰色删除线
- 逾期未完成的任务自动收集，无逾期时区域自动隐藏
- 一键将逾期任务「移回今天」
- 迷你日历：点击任意日期查看/编辑当天的任务
- 毛玻璃界面，可拖拽移动位置
- 纯本地存储（localStorage），无需联网
- 开机自启动

## 🖥️ 如何使用

### 方式一：作为桌面壁纸（推荐）

1. 下载并安装 [Lively Wallpaper](https://rocksdanister.com/lively/)（官网或 Microsoft Store），安装一般直接一直下一步就可以了。
2. 打开 Lively，将 `SideDesk.html` 文件直接拖入主窗口
3. 点击「设为壁纸」即可

### 方式二：直接浏览器打开

双击 `SideDesk.html`，使用 Chrome / Edge 打开即可使用。

## 🖼️ 更换卡片背景图片

默认背景为在线示例图片。换成你自己的壁纸：

1. 将图片（如 `my.jpg`）复制到 `SideDesk.html` 所在文件夹
2. 用记事本打开 `SideDesk.html`，找到以下代码：

   background: url('https://picsum.photos/id/104/1920/1080') no-repeat center center fixed;

3. 改为：

   background: url('my.jpg') no-repeat center center fixed;

4. 保存，刷新浏览器或重新加载 Lively 壁纸

> 图片文件名建议使用英文，避免空格。

## 📦 文件说明

- `SideDesk.html` – 主程序（单文件，所有代码都在里面）
- 你的壁纸图片（可选） – 与 HTML 放在同一目录

## 📄 许可证

MIT © Verabelle

---