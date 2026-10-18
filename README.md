# M870

[中文](#中文) · [English](#english)

**[⬇ 下载最新版 / Download the latest version](https://github.com/zzMerl1n25/m870-releases/releases/latest)**

---

## 中文

M870 是一款多人语音聊天软件。建一个房间，把邀请发给朋友，大家就能语音和文字聊天，还能视频通话、共享屏幕、一起看视频。开黑、开会、群聊、一起自习，都可以在一个房间里完成。

画面和声音在成员之间点对点直连，延迟低，内容也不经过别人的服务器。

### 适合这些场景

- **开黑**：边玩边语音，互相看游戏画面；可以只共享游戏的声音，队友的说话声不会被传回去。
- **会议**：开摄像头视频通话，共享屏幕或某个窗口来讲解，需要时录下来。
- **群聊**：几个朋友挂在房间里语音聊天，也可以打字。
- **学习**：一起自习，共享屏幕讲题或对答案。
- **一起看**：一个人打开视频网页，所有人的播放进度自动同步。

### 功能

- **语音**：降噪（关 / 标准 / 强）、人声增强、回声消除；麦克风和耳机可以单独选择；每个人的音量可以分别调。
- **文字聊天**：房间内的消息端到端加密。
- **视频通话**：摄像头 360P～1080P，同时共享屏幕时摄像头以小窗显示。
- **屏幕共享**：
  - 共享整个屏幕或某个窗口，最高 1440P / 60 FPS。
  - 声音可以选几个程序，也可以选整个系统声音。
  - 共享中能随时改分辨率、帧率和画质取舍，或换成别的窗口和声音，大家不用重新进房间。
- **一起看**：房间里内置浏览器，播放、暂停、拖进度、换视频，所有人同步。
- **录像**：把自己或别人的画面录成 MP4。
- **房间**：开黑、聊天、会议、学习、一起看等多种类型。公开房间会出现在房间列表里，任何人都能加入；私密房间凭房间码加入。两种都可以设密码。
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
4. 进房后点底部的麦克风按钮开始说话；想给大家看画面时，点 **共享屏幕**，选择屏幕或窗口，以及要不要带声音。

### 常见问题

**画面卡、糊，或者对方提示带宽不足？**
共享时选低一点的分辨率或帧率，或者在共享设置里选「流畅优先」。成员列表里能看到每个人实际收到的画质和原因。

**连不上对方？**
画面和声音需要在双方之间直接连通。有些网络（手机热点、公司或学校网络）不允许直连，换一个网络试试，比如从手机热点换成家里的宽带。房间里点 **更多 → 连接诊断** 可以看到连接情况。

**进不了房间、一直显示正在连接？**
M870 默认使用公共信令服务器牵线，偶尔会不稳定。可以在 **设置 → 网络** 里换一个服务器再试；同一个房间的人要选同一个服务器。

**共享游戏时画面是黑的？**
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

M870 is a group voice chat app. Create a room, send the invite to your friends, and everyone can talk by voice and text, make video calls, share screens and watch videos together. Gaming, meetings, group chats and study sessions all happen in one room.

Video and audio go peer-to-peer between members with low latency, and the content never passes through anyone else's server.

### Made for

- **Gaming**: talk while you play and watch each other's game screens. You can share only the game's audio, so teammates' voices are not sent back to them.
- **Meetings**: video calls with your camera, share a screen or a single window to present, and record when needed.
- **Group chat**: hang out in a room with friends over voice, or type.
- **Studying**: study together and share your screen to go through problems or compare answers.
- **Watch together**: one person opens a video page and everyone's playback stays in sync.

### Features

- **Voice**: noise suppression (off / standard / strong), voice enhancement and echo cancellation; choose your microphone and headphones; set each person's volume separately.
- **Text chat**: room messages are end-to-end encrypted.
- **Video calls**: camera from 360P to 1080P, shown as picture-in-picture while you share your screen.
- **Screen sharing**:
  - Share a whole screen or a single window, up to 1440P / 60 FPS.
  - For audio, pick one or more apps, or the whole system.
  - While sharing, change resolution, frame rate and the quality trade-off at any time, or switch to another window or audio source, without anyone having to rejoin.
- **Watch together**: a built-in browser in the room; play, pause, seek and video changes stay in sync for everyone.
- **Recording**: record your own or someone else's stream to MP4.
- **Rooms**: gaming, chat, meeting, study, watch together and more. Public rooms appear in the room list and anyone can join; private rooms are joined with a room code. Both can have a password.
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
4. In the room, click the microphone button at the bottom to start talking. To show your screen, click **Share screen** (共享屏幕) and pick a screen or window, and whether to include audio.

### FAQ

**The picture stutters, looks blurry, or a viewer has low bandwidth?**
Pick a lower resolution or frame rate, or choose "Smoothness first" (流畅优先) in the share settings. The member list shows what each person actually receives and why.

**Can't connect to someone?**
Video and audio need a direct connection between you. Some networks (mobile hotspots, office or campus networks) block direct connections; try another network, for example home broadband instead of a hotspot. **More → Connection diagnostics** (更多 → 连接诊断) in a room shows the connection details.

**Can't enter a room, or it keeps connecting?**
M870 uses a public signaling server by default to introduce members, which is occasionally unstable. Pick another server in **Settings → Network** (设置 → 网络) and try again; everyone in the same room must use the same server.

**A shared game shows a black screen?**
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
