# M870

[中文](#中文) · [English](#english)

**[⬇ 下载最新版 / Download the latest version](https://github.com/zzMerl1n25/m870-releases/releases/latest)**

---

## 中文

M870 是一个"线上网吧"：小房间里的几个人互相看屏幕、开黑、语音聊天、一起看视频。画面和声音点对点直连，延迟低，也不经过别人的服务器。

### 能做什么

- **互相看屏幕**：共享整个屏幕或某个游戏窗口，最高 1440P / 60 FPS。可以只带上游戏的声音，不会把队友的语音传回去。
- **直播中随时调整**：共享过程中能改分辨率、帧率、画质取舍，也能换成别的窗口或声音，观众不用重新进房间。
- **语音和聊天**：带降噪和人声增强；每个人的音量可以单独调；房间内文字聊天端到端加密。
- **视频通话**：打开摄像头，同时共享屏幕时以小窗显示。
- **一起看**：房间里内置浏览器，一个人打开视频网页，大家的播放进度自动同步。
- **录像**：把自己或队友的画面录成 MP4。
- **房间**：开黑、聊天、会议、学习、一起看等多种类型。公开房间所有人都能看到并加入，私密房间凭房间码加入，都可以设密码。
- **免注册账号**：第一次打开自动生成账号。导出恢复码后，换电脑也能用同一个账号。

### 系统要求

- Windows 10 或 Windows 11（64 位）。
- 只共享某个程序的声音，需要 Windows 10 2004 及以上版本。
- 一个房间建议不超过 5 人，最多 6 人。

### 安装

1. 打开 [Releases 页面](https://github.com/zzMerl1n25/m870-releases/releases/latest)，下载 `M870-Setup-版本号.exe`。
2. 双击运行安装程序。
3. 如果出现「Windows 已保护你的电脑」：点击 **更多信息 → 仍要运行**。安装包暂时没有购买代码签名证书，所以会有这个提示。
4. 安装完成后从桌面或开始菜单打开 M870。

更新时直接下载新版安装包覆盖安装即可，账号和设置都会保留。

### 开始使用

1. 点 **创建房间**，选择房间类型和公开 / 私密，进入房间。
2. 点侧栏里的 **复制邀请**，把邀请文字发给朋友。
3. 朋友在 M870 里点 **加入房间**，把整段邀请文字粘贴进去，房间码和密码会自动识别。
4. 进房后点底部的 **共享屏幕**，选择屏幕或游戏窗口，以及要不要带声音。

### 常见问题

**画面卡、糊，或者对方提示带宽不足？**
共享时选低一点的分辨率或帧率，或者在共享设置里选「流畅优先」。成员列表里能看到每个人实际收到的画质和原因。

**连不上对方，或者一直显示「中继」？**
有些网络（手机热点、公司网络）没法直连，会自动经服务器中转，这时画质会受限制。条件允许的话换一个网络试试。

**游戏画面是黑的？**
全屏独占模式的游戏可能抓不到画面。把游戏改成「无边框窗口」，或者共享「整个屏幕」。

**听不到共享的声音？**
确认共享时选了声音，以及电脑的 Windows 默认播放设备是你正在用的耳机或音箱。

**遇到其他问题？**
在房间里点 **更多 → 连接诊断**，复制诊断报告（不含 IP 地址），然后到 [Issues](https://github.com/zzMerl1n25/m870-releases/issues) 提交问题，附上报告和问题描述。

### 隐私

- 画面和声音在你和朋友之间直接传输，并且加密；服务器只帮大家建立连接，看不到内容。
- 房间消息和聊天内容端到端加密。
- 不需要手机号或邮箱注册。账号保存在你自己的电脑上，请妥善保存恢复码。

### 版权

© 2026 zzMerl1n25，保留所有权利。

M870 免费供个人下载和使用。本仓库只发布安装包，不是开源项目。未经许可，不得修改、反编译、重新打包或再分发本软件。

---

## English

M870 is an "online internet café": a few people in a small room watch each other's screens, game together, voice chat and watch videos together. Video and audio go peer-to-peer with low latency and never pass through anyone else's server.

### What it does

- **Watch each other's screens**: share a whole screen or a single game window, up to 1440P / 60 FPS. You can share just the game's audio, without sending teammates' voices back to them.
- **Adjust while live**: change resolution, frame rate and the quality trade-off during a share, or switch to another window or audio source, without viewers having to rejoin.
- **Voice and chat**: noise suppression and voice enhancement, separate volume for each person, and end-to-end encrypted text chat in the room.
- **Video calls**: turn on your camera; it shows as picture-in-picture while you share your screen.
- **Watch together**: a built-in browser in the room. One person opens a video page and everyone's playback stays in sync.
- **Recording**: record your own or a teammate's stream to MP4.
- **Rooms**: gaming, chat, meeting, study, watch together and more. Public rooms are visible to everyone; private rooms are joined with a room code. Both can have a password.
- **No sign-up**: an account is created the first time you open the app. Export a recovery code to use the same account on another computer.

### Requirements

- Windows 10 or Windows 11 (64-bit).
- Sharing the audio of a single app requires Windows 10 version 2004 or later.
- Rooms work best with 5 people or fewer (6 maximum).
- The app interface is in Chinese; the steps below give the Chinese button names in brackets.

### Install

1. Go to the [Releases page](https://github.com/zzMerl1n25/m870-releases/releases/latest) and download `M870-Setup-<version>.exe`.
2. Run the installer.
3. If you see "Windows protected your PC", click **More info → Run anyway**. The installer is not code-signed yet, which is why Windows shows this warning.
4. Open M870 from the desktop or Start menu.

To update, download the new installer and install over the old version. Your account and settings are kept.

### Getting started

1. Click **Create room** (创建房间), choose a room type and public / private, and enter the room.
2. Click **Copy invite** (复制邀请) in the side panel and send the text to your friends.
3. Your friends click **Join room** (加入房间) in M870 and paste the whole invite; the room code and password are filled in automatically.
4. In the room, click **Share screen** (共享屏幕) at the bottom and pick a screen or game window, and whether to include audio.

### FAQ

**The picture stutters, looks blurry, or a viewer has low bandwidth?**
Pick a lower resolution or frame rate, or choose "Smoothness first" (流畅优先) in the share settings. The member list shows what each person actually receives and why.

**Can't connect, or it keeps showing "relay" (中继)?**
Some networks (mobile hotspots, corporate networks) block direct connections, so traffic is relayed through a server and quality is limited. Try another network if you can.

**The game shows a black screen?**
Games in exclusive fullscreen mode may not be capturable. Switch the game to borderless windowed mode, or share the whole screen.

**Can't hear the shared audio?**
Make sure audio was selected when sharing, and that Windows' default playback device is the headphones or speakers you are using.

**Something else?**
In a room, open **More → Connection diagnostics** (更多 → 连接诊断), copy the report (it contains no IP addresses), and open an issue in [Issues](https://github.com/zzMerl1n25/m870-releases/issues) with the report and a description.

### Privacy

- Video and audio travel directly and encrypted between you and your friends; the server only helps you connect and cannot see the content.
- Room messages and chat are end-to-end encrypted.
- No phone number or email is needed. Your account lives on your own computer, so keep your recovery code safe.

### Copyright

© 2026 zzMerl1n25. All rights reserved.

M870 is free to download and use for personal purposes. This repository only publishes installers and is not an open-source project. Modifying, decompiling, repackaging or redistributing the software without permission is not allowed.
