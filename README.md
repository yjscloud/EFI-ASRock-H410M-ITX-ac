# Mini ITX 4k 办公黑苹果 macOS 12 Monterey EFI

## 装机清单

| 名称          | 品牌型号                       | 备注 |
| ------------- | ------------------------------ | ---- |
| CPU           | 英特尔 i5 10400                |      |
| 主板          | 华擎 H410M-itx/ac              |      |
| 散热器        | 九州风神 船长 240 EX White RGB |      |
| 内存          | 光威 DDR4 2666 16G x 2         |      |
| 硬盘          | 海康威视 C2000 Pro             |      |
| 显卡          | 核显 UHD 630                   |      |
| 无线网卡/蓝牙 | 板载有线+板载无线网卡+板载蓝牙 |      |
| 显示器        | 冠捷 U27908                    |
| 机箱          | 乔思伯迷你 mini 铝制小机箱     |      |
| 电源          | 爱国者 ATX 400w                |      |

### 95%完美

- [x] BIOS 版本
  - [x] 4.40
  - [x] 1.5
- [x] macOS 版本
  - [x] [12.3.1]
- [x] 显卡
  - [x] 单 4k 显示器（DisplayPort）
- [x] 声卡(Realtek ALC1220)
  - [x] 主板后置
  - [x] 机箱前置
  - [x] DisplayPort 声音输出
- [x] 睡眠/唤醒
- [x] 有线网卡
- [x] 无线 WiFi
- [x] 蓝牙
  - [x] Handoff
  - [ ] Airdrop
- [x] 所有 USB 插口
  - [ ] 前置/后置 USB 外接麦克风无法识别

## 安装教程

### 前期准备

开机 F2 进入 BIOS 再按 F6 切换高级模式，至少需要做如下修改具体情况还需要看硬件情况：

- 高级（Advanced） > 芯片配置（Chipset Configuration） > VT-d -> Disabled
- 高级（Advanced） > USB 配置（USB Configuration） > XHCI Hand-off -> Enabled

### 安装黑苹果

请移步至 bilibili 自行搜索黑苹果安装教程

## 教科书版黑苹果教程

- https://www.tonymacx86.com/threads/guide-asrock-z390-phantom-gaming-itx-ac-i9-9900k-rx-580.268992/
- https://www.tonymacx86.com/threads/success-asrock-z390-phantom-gaming-itx-tb3-igpu-mojave-sff-build.277418/
- https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/
