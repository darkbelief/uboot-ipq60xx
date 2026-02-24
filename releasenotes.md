### ✨ 功能更新

- 添加 bootconfig 命令，用于切换启动分区
- 添加 untar 命令，用于解析 sysupgrade tar image
- 支持刷写 sysupgrade 格式的固件
- 固件上传完成后检查其 kernel 与 rootfs 是否超过相应分区大小
- 支持通过 DHCP 为客户端分配 IP（dhcpd 跟随 httpd 自动启动）

### 📢 其他更新

- 调整文件上传完成后内存填充的起始地址，改用 0 填充内存
- 调整上传文件大小错误时打印的日志内容
- 合并 NN6000 V1 & V2 的 U-Boot
- 为打印的日志中的十六进制数添加 0x 前缀

## 📡 支持设备

- 京东云太乙（RE-CS-07）
