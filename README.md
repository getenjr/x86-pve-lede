# x86-pve-lede
自动构建x86机型，PVE环境下的lede镜像

# 编译选项
    Target System (x86)
    Subtarget (x86_64)
    Target Profile (Generic x86/64)
    Target Images > ext4
    Target Images > Root filesystem partition size (in MB)
    Target Images > Build PVE/KVM image files
    Base system > blockd 	
    Base system > dnsmasq-full > build with dhcpv6 support(支持IPv6）(*)
    Extra packages > autosamba (只支持samba3,选择samba4时去掉)
    Extra packages > ipv6helper(支持IPv6）(*)
    Kernel modules > Filesystems > kmod-fs-nfs
    Kernel modules > USB Support > kmod-usb2
    Kernel modules > USB Support > kmod-usb3
    Kernel modules > USB Support > kmod-usb-net
    LuCI > Collections > luci
    LuCI > Modules > Translations > Chinese (zh-cn)
    LuCI > Applications > luci-app-adbyby-plus
    LuCI > Applications > luci-app-adguardhome
    LuCI > Applications > luci-app-advanced
    LuCI > Applications > luci-app-nps
    LuCI > Applications > luci-app-openclash
    LuCI > Applications > luci-app-passwall
    LuCI > Applications > luci-app-ssr-plus
    LuCI > Applications > luci-app-samba 与 luci-app-samba4不共存
    LuCI > Applications > luci-app-smartdns
    LuCI > Applications > luci-app-turboacc
    Utilities > Compression > gzip
    Utilities > Disc > cfdisk
    Utilities > Disc > fdisk