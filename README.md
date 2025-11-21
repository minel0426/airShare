⚡️ AirShare: 局域网隔空快传工具
LAN Peer-to-Peer File Transfer Tool. Zero setup, zero dependencies. Share files and text across Mac, Windows, and iOS via a single browser page.


🚀 核心特性 (Features)
⚡️ 极速传输： 基于 WebRTC (点对点通信)，文件在设备间直接传输，速度取决于您的局域网环境。

🌐 零配置： 无需安装 App 或运行命令行，只需一个浏览器标签页。

🛡️ 隐私安全： 文件经过加密，绝不会上传到任何服务器（包括 GitHub 或您的主机）。

💻 跨平台： 完美支持 Mac、Windows、iOS、Android 手机浏览器。


💡 如何使用 (How to Use)
AirShare 的工作原理是：先开一个房间（主机），然后其他设备扫码加入（访客）。

1. 启动主机 (Host)
在您希望发送或接收文件的主设备（Mac/Windows）上，打开您的专属网址：

访问 **https://minel0426.github.io/airShare/**
页面会自动生成一个独特的 二维码 和连接。

此设备将保持为 主机状态，等待连接。

2. 扫码连接 (Guest)
在另一台设备（iPhone/Windows/Mac）上：

使用 相机 或 浏览器 扫描主机页面上显示的二维码。

访客设备将自动尝试建立连接。

3. 开始互传
当连接状态变为 "✅ 已安全连接" 时，双方即可开始互传。

发送文件： 将文件直接拖拽到页面中央的虚线框内。

接收文件： 文件传输完成后，点击列表中的 "下载" 按钮即可保存。

🔒 安全性与隐私声明 (Security & Privacy)
AirShare 的设计核心在于保护您的数据，我们无法获取您的任何文件。

文件不经服务器： AirShare 使用 WebRTC DataChannel 技术。这意味着文件数据是点对点 (P2P)，直接从您的设备 A 传输到设备 B，中间不经过我们用于托管页面的 GitHub 服务器或其他云端。

仅用于信令： GitHub Pages 或您的服务器，仅用于托管页面的代码和 WebRTC 握手的 信令 (Signaling) 信息，就像一部电话簿，只负责让两台设备找到对方。

自动加密： WebRTC 连接本身强制使用 DTLS 和 SRTP 协议，您的数据在传输过程中是默认加密的。



-----

# ⚡️ AirShare: LAN Air-to-Air Transfer Tool

> **LAN Peer-to-Peer File Transfer Tool.** Zero setup, zero dependencies. Share files and text across Mac, Windows, and iOS via a single browser page.

## 🚀 Key Features

  * **⚡️ Lightning Fast:** Built on WebRTC (Peer-to-Peer), files transfer directly between devices. Speed is limited only by your local network (LAN) environment.
  * **🌐 Zero Configuration:** No need to install apps or run command line interfaces (CLI). All you need is a single URL.
  * **🛡️ Privacy Guaranteed:** Files are encrypted and **never** uploaded to any server (including GitHub or your host).
  * **💻 Cross-Platform:** Seamlessly supports browsers on Mac, Windows, iOS, and Android.
## 💡 How to Use

AirShare works by establishing a room (Host) and having other devices join (Guest) by scanning a QR code.

### 1\. Launch the Host

On your primary device (Mac/Windows) where you want to initiate sending or receiving, open your unique project URL:

```
Visit **https://minel0426.github.io/airShare/**
```

  * The page will automatically generate a unique **QR code** and connection link.
  * This device remains in **Host state**, waiting for connections.

### 2\. Connect the Guest

On the secondary device (iPhone/Windows/Mac):

  * Use the **camera** or browser to **scan the QR code** displayed on the host's screen.
  * The guest device will automatically attempt to establish a direct P2P connection.

### 3\. Start Transferring

  * Once the status changes to **"✅ Connected Securely"**, both parties can begin sharing.
  * **To Send:** Simply drag and drop files onto the dashed box in the center of the page.
  * **To Receive:** Click the **"Download"** button next to the file name to save the data.

## 🔒 Security & Privacy Statement

**AirShare is designed to protect your data; we have no ability to access your transferred files.**

  * **No Server Middleman:** AirShare utilizes the **WebRTC DataChannel** technology. This means file data is **Peer-to-Peer (P2P)**, moving directly from your device A to device B without passing through the GitHub server or any other cloud service used for hosting the UI.
  * **Signaling Only:** The hosting server (GitHub Pages) is only used for serving the UI code and facilitating the **Signaling** process (like a phone book connecting two parties).
  * **Mandatory Encryption:** WebRTC connections enforce the use of DTLS and SRTP protocols, ensuring your data is **encrypted** during transmission by default.



