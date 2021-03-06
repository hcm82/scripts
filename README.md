# Linux 日常脚本
- `base64url`：URL Safe Base64，基本用法同 `base64`
- `netspeed`：显示指定网卡的实时网速，如 `netspeed eth0`
- `pmemory`：显示进程所占用的内存大小，如 `pmemory java bash`
- `random`：随机字符串生成，可选择复杂级别，如 `random -l3 -n30`
- `rescan-disk`：扫描新加入的磁盘（SCSI），主要用于 VMware 虚拟机
- `wifi-scan`：扫描附近可用的 WiFi 并显示结果，如 `wifi-scan wlan0`
- `zsh-bad-history-fix`：修复 zsh 的 history 文件（异常关机后常常出现）
- `grepvp`：grep 的简单实现（via perl），如 `grepvp '/systemd/' /etc/passwd`
- `sedvp`：sed 的简单实现（via perl），如 `sedvp -i.bak 's/\s+/ /g' fred.txt`
- `awkvp`：awk 的简单实现（via perl），如 `awkvp -F: 'print "$F[0] $F[6]"' /etc/passwd`
- `urldecode`：url 编码（百分号编码）的 decode 脚本，用法 `echo '%e4%b8%ad%e6%96%87' | urldecode`
