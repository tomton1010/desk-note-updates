# desk-note-updates

「桌面日报」桌面应用的**应用内更新通道**，仅在 Releases 中存放：

- `latest.json`：Tauri Updater 更新清单
- `desk-note_<version>_x64-setup.exe`：已签名的 NSIS 安装包
- `desk-note_<version>_x64-setup.exe.sig`：对应签名

应用源码位于私有仓库，本仓库不包含源码，也不包含任何用户数据。

安装版用户可在「设置 → 关于 → 检查更新」中获取新版本；更新包会先通过 Tauri Updater 公钥校验再安装。
