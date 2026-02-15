# OpenClaw Mobile

OpenClaw Android 移动应用，基于 Capacitor/WebView 技术构建。

## 软件预览

| 概览 | 会话 |
|------|------|
| ![概览](screenshots/screenshot1.jpg) | ![会话](screenshots/screenshot2.jpg) |

| 聊天 | 配置 |
|------|------|
| ![聊天](screenshots/screenshot3.jpg) | ![配置](screenshots/screenshot4.jpg) |

## 功能特性

- 移动端控制面板
- 实时聊天
- 会话管理
- 技能市场
- 配置管理

## 使用方式

1. 从 Releases 下载 APK
2. 安装到 Android 设备
3. 配置网关地址（默认 ws://localhost:18789）

## 编译

```bash
./gradlew assembleDebug
```

APK 输出位置：`app/build/outputs/apk/debug/app-debug.apk`

## 自动构建

GitHub Actions 自动构建，查看 [Actions](https://github.com/lg31415/openclaw-mobile/actions) 页面。
