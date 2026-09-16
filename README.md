# Septcats Releases

Septcats（本地优先笔记应用）的安装包发布仓库，兼作自动更新 feed（Ed25519 自签 latest.yml.sig）。

- 下载最新安装包：见 Releases
- 源码：暂不公开
- 安全说明：更新包经应用内硬编码公钥验签后才安装；feed 篡改会直接被拒（E_FEED_SIGNATURE）。
