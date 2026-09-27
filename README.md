# 音乐库

「音乐库」桌面版与手机版的安装包发布仓库。

## 下载安装包

| 文件 | 平台 | 版本 | 说明 |
| --- | --- | --- | --- |
| [`packages/音乐库电脑版-1.6.5-搜索提速优化-安装版.exe`](packages/) | Windows 10/11 | 1.6.5 | 桌面安装版（搜索提速优化） |
| [`packages/音乐库-手机版-1.6.7-启动闪退修复.apk`](packages/) | Android 7+ | 1.6.7 | 手机版（启动闪退修复） |
| [`packages/音乐库-手机版-1.6.8-移除桌面歌词.apk`](packages/) | Android 7+ | 1.6.8 | 手机版（移除桌面歌词） |

功能包括：榜单、歌单、搜索、收藏、播放队列、歌词、桌面歌词（桌面版）、通知栏 / 锁屏控制（手机版）。

## 校验

安装包的 SHA-256 校验值见 [`packages/SHA256SUMS.txt`](packages/SHA256SUMS.txt)。

```bash
# Linux / macOS
sha256sum -c SHA256SUMS.txt

# Windows PowerShell
Get-FileHash *.exe,*.apk -Algorithm SHA256
```

## 说明

- 本仓库仅发布已公开的安装包；完整源码与打包脚本保存在私有仓库中，不对外公开。
- 桌面版与手机版依赖第三方聚合接口，接口随时可能变化或失效，请自行确认内容来源的合规性。
