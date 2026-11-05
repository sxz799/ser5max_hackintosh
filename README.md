# Beelink SER5 MAX Hackintosh

基于 OpenCore 引导的零刻 Beelink SER5 MAX 黑苹果项目，搭载 AMD Ryzen 7 5800H 处理器，使用 AMD Radeon Vega 核显，并更换 Broadcom BCM94352Z 无线网卡。

本项目主要记录 EFI 配置、驱动方案、系统安装及硬件适配情况，方便后续维护和更新。

## 硬件配置

| 硬件 | 型号 / 规格 |
|---|---|
| 主机 | Beelink SER5 MAX |
| CPU | AMD Ryzen 7 5800H |
| CPU 核心 | 8 核 16 线程 |
| GPU | AMD Radeon Vega 核显 |
| 独立显卡 | 不使用 |
| 内存 | DDR4（容量以实际配置为准） |
| 硬盘 | NVMe SSD |
| 有线网卡 | Realtek RTL8111 |
| 无线网卡 | Broadcom BCM94352Z |
| 蓝牙 | Broadcom Bluetooth |
| 声卡 | Realtek ALC897 |


## 注意事项

- 本项目针对 Beelink SER5 MAX 和 AMD Ryzen 7 5800H。
- 不保证其他型号的 SER5 系列可以直接使用。
- 更换无线网卡后，需要重新检查 Wi-Fi 和 Bluetooth 驱动。
- 更新 macOS 或 OpenCore 前，建议备份原 EFI。
- 更新 Kext 后，需要同步检查 config.plist 中的加载顺序和配置。
- AMD 平台部分 Apple 原生功能可能存在兼容性限制。
- 黑苹果不属于 Apple 官方支持的硬件平台。

## 参考资料

- [OpenCore 官方文档](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Vanilla Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla)
- [NootedRed](https://github.com/ChefKissInc/NootedRed)

## 免责声明

本项目仅供个人学习、研究及技术交流使用。

使用本 EFI 所产生的系统故障、数据丢失及其他问题，需要使用者自行承担责任。

---

**项目平台：** Beelink SER5 MAX

**处理器：** AMD Ryzen 7 5800H

**无线网卡：** Broadcom BCM94352Z

**操作系统：** macOS Ventura 13.7.8

**引导程序：** OpenCore
