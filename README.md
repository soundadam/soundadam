### 你好，我是 SoundAdam

近期在做语音信号处理：

- **语音唤醒**：关键词检测，重点是压低误唤醒
- **语音增强**：在噪声和混响里还原干净的语音
- **语音编解码**：低码率的神经语音编解码

#### 开源工具

**[nju-connect](https://github.com/soundadam/nju-connect)**：南京大学校园 VPN 客户端，支持 EasyConnect 与 aTrust，命令行 + macOS 菜单栏。
深信服官方客户端会改写系统路由表和 DNS；nju-connect 只在本机开一个 SOCKS5 端口 `127.0.0.1:1081`，系统网络不动。

**[tea](https://github.com/soundadam/tea)**：让 Mac 合上盖子也保持唤醒，当服务器用。
`caffeinate` 进程一退就失效，合盖照样睡；tea 改的是系统设置，结束时只还原自己改过的值。
名字里 tea 是茶，对应 caffeinate 的咖啡因。

**[pace](https://github.com/soundadam/pace)**：给校园网、教育网和代理出口分别测速的命令行工具。
每条路径单独出结果，不折算成一个分数；失败照实记录，没有遥测。

```sh
brew install --cask soundadam/tap/nju-connect
brew install soundadam/tap/tea
brew install --cask soundadam/tap/pace
```

另有 [nju-openapi](https://github.com/soundadam/nju-openapi)（南大教务接口的非官方 OpenAPI）。

[soundadam.com](https://soundadam.com) · hello@soundadam.com
