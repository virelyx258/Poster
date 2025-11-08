<div align="center">
    <img width="100px" src="./Assets/logo.png" align="center" alt="RStatus" />
    <h2 align="center">Poster</h2>
    <p align="center">小米穿戴设备网络调试工具</p>
</div>
<div align="center">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/virelyx258/Poster?style=for-the-badge"> 
    <img alt="GitHub" src="https://img.shields.io/github/license/virelyx258/Poster?style=for-the-badge"> 
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/virelyx258/Poster?style=for-the-badge"> 
</div>

## 简介
> [!IMPORTANT]
> 以下内容于2025年11月8日撰写，本软件的实际功能可能会因新版本推送而与简介有所差异。

**Poster** 是一个适用于 Xiaomi Vela JS 操作系统的 POST 请求发送工具。其内部以⌈快捷指令⌋的方式来保存 POST 请求，以便用户在需要的时候直接发送特定的 POST 请求。

- 技术栈：`JavaScript`
- 支持的操作系统：Xiaomi Vela JS

## Todo List
- [x] 设备列表
- [x] 发送成功/失败提示
- [ ] `{` `}` 等符号的输入

## 下载
前往[Release](https://github.com/virelyx258/Poster/releases)页面进行下载。

## 编译

该软件使用 AIoT IDE 进行编写和调试。如果你想要编译该软件，请准备以下环境：

- Windows 10 和以上版本的电脑
- AIoT IDE 最新版本

同时，该软件引用了 [InputMethod](https://github.com/NEORUAA/Vela_input_method)，请在编辑 / 引用代码时遵守相关协议。

## 使用教程

1. 点击主页右下角的“➕”按钮，进入“新建”页面；
2. 输入 POST URL （请求地址）、请求数据、名称和简介等基本信息；
3. 点击“新建”页面最下方的“√”按钮，保存该条快捷指令；
4. 侧滑或点击页面左上角的“<”按钮，返回到主界面，刚才新建的快捷指令自动显示。
5. 日常使用，点击快捷指令列表中的项目即可快速发送 POST ，并弹窗提示请求结果。

## 兼容性

软件目前适配进度：

- [x] REDMI Watch 6
- [x] REDMI Watch 5 (eSIM)
- [x] Xiaomi Smart Band 9 Pro
- [ ] Xiaomi Smart Band 9 （部分界面未完善）
