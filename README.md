### 你好，我是 SoundAdam

近期在做语音信号处理：

- **语音唤醒**：关键词检测，重点是压低误唤醒
- **语音增强**：在噪声和混响里还原干净的语音
- **语音编解码**：低码率的神经语音编解码

#### 开源工具

**[nju-connect](https://github.com/soundadam/nju-connect)**：南京大学校园 VPN 客户端，支持 EasyConnect 与 aTrust，命令行 + macOS 菜单栏。
深信服官方客户端会改写系统路由表和 DNS；nju-connect 只在本机开一个 SOCKS5 端口 `127.0.0.1:1081`，系统网络不动。

**[teaway](https://github.com/soundadam/teaway)**：让 Mac 合上盖子也保持唤醒，当服务器用。
`caffeinate` 进程一退就失效，合盖照样睡；teaway 改的是系统设置，结束时只还原自己改过的值。
名字里 tea 对应 caffeinate 的咖啡因，away 是你可以走开。

```sh
brew install --cask soundadam/tap/nju-connect
brew install soundadam/tap/teaway
```

另有 [soundprobe](https://github.com/soundadam/soundprobe)（南大 / M-Lab / 国内网络测速）
和 [nju-openapi](https://github.com/soundadam/nju-openapi)（南大教务接口的非官方 OpenAPI）。

[soundadam.com](https://soundadam.com) · hello@soundadam.com
