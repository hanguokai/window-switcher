> [English](./README.md)

# Window Switcher

macOS 窗口快速切换工具 —— 在**当前激活应用**的多个窗口之间快速切换。

## 功能特性

- **全局快捷键**：默认 `⌥` + `` ` ``（Option + 反引号）触发，可在设置中自定义（提供了多种快捷键组合供选择）
- **窗口循环切换**：按快捷键循环选择窗口，松开修饰键确认切换
- **反向切换**：按住 Shift + 快捷键反向循环
- **菜单栏应用**：无 Dock 图标，仅在菜单栏显示 ⌨️ 图标
- **开机自启**：支持设置登录时自动启动
- **检查更新**：在设置中一键检查新版本

## 系统要求

- macOS 13.0 (Ventura) 或更高版本

---

## 安装

1. 前往 [Releases](https://github.com/hanguokai/window-switcher/releases) 页面，下载最新版本的 `.dmg` 文件
2. 打开下载的 DMG 文件
3. 将 **Window Switcher** 拖拽到 **Applications** 文件夹
4. 从 Applications 中启动 Window Switcher
5. 首次使用时，系统会提示授予 **Accessibility（辅助功能）权限**，请点击允许（详见下方说明）

## 使用方法

1. 启动后，菜单栏出现 ⌨️ 图标
2. 打开一个应用的多个窗口（如多个 Finder 窗口、多个浏览器窗口）
3. 按下 `⌥` + `` ` ``（Option + 反引号）触发窗口切换浮层
4. 继续按 `⌥` + `` ` `` 循环选择不同窗口（按住 Shift 反向循环）
5. 松开 Option 键，确认切换到选中窗口
6. 按 Esc 取消切换

### 菜单栏选项

点击菜单栏的 ⌨️ 图标：

- **Settings...** — 自定义快捷键、开机自启、检查更新
- **Check Accessibility Permission** — 检查辅助功能权限状态
- **Quit Window Switcher** — 退出应用

---

## 更新

1. 打开菜单栏 → **Settings...** → **About** 区域
2. 点击 **Check for Updates**
3. 如果有新版本，点击 **Download** 按钮，浏览器会打开新版本的下载页面。或者直接来 [GitHub Releases](https://github.com/hanguokai/window-switcher/releases) 页面，查找最新版本的 DMG 文件。
4. 下载新版本的 DMG 文件
5. 在菜单栏点击 ⌨️ → **Quit Window Switcher** 退出当前版本
6. 打开新版本 DMG，将新的 Window Switcher 拖拽到 Applications（替换旧版本）
7. 重新启动 Window Switcher

---

## Accessibility 权限

Window Switcher 需要 macOS 辅助功能（Accessibility）权限来读取和操作窗口。

### 首次授权

首次按下快捷键时，系统会自动弹出授权对话框，点击 **"Open System Settings"** 并开启权限即可。

也可以通过菜单栏 → **Check Accessibility Permission** 手动触发。

### 权限故障排除

如果快捷键无响应或窗口切换不工作，请尝试以下步骤：

1. 打开 **系统设置** → **隐私与安全性** → **辅助功能**
2. 在列表中找到 **Window Switcher**
3. 先将其**关闭**（或点击 `−` 按钮移除），然后重新**开启**（或点击 `+` 按钮重新添加）
4. 在菜单栏点击 ⌨️ → **Quit Window Switcher**，退出应用
5. 重新启动 Window Switcher

---

## 许可
Copyright © 2026 Guokai Han. All rights reserved.

此项目源码不公开，仅通过 Release 分发软件。
