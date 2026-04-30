# 3D 音频动效反馈

一个能对 麦克风输入/标签页音频采集 实时反馈为3D粒子动效的裸 HTML。
[在线体验](https://audio.whiteday13jin.com)

## 效果展示
![preview](./preview.png)

![demo](./demo.gif)

![demo](./demo2.gif)

## 功能
- 支持麦克风输入
- 支持标签页 / 屏幕音频采集（移动端麦克风可用，标签页采集权限可能受限）
- 实时响度与频段反馈
- 基于 Three.js 的 3D 粒子可视化

采集音频，建议使用 **HTTPS** 或 **localhost**,给麦克风权限。  
抓取网页声音，建议用 Chromium 内核浏览器，并勾选 **共享标签页音频**。
