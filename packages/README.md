# 已发布的安装包

| 文件 | 平台 | 版本 | 大小 |
| --- | --- | --- | --- |
| `音乐库-电脑版-1.6.5.exe` | Windows 10/11 | 1.6.5 | 88.0 MiB |
| `音乐库-手机版-1.6.8.apk` | Android 7+ | 1.6.8 | 3.9 MiB |

校验：

```bash
# Linux / macOS
sha256sum -c SHA256SUMS.txt

# Windows PowerShell
Get-FileHash *.exe,*.apk -Algorithm SHA256
```

电脑版安装包与官网上公布的 SHA-256 完全一致。手机版安装包使用统一的发布签名，
以后升级手机版请从相同来源获取安装包，才能覆盖安装。
