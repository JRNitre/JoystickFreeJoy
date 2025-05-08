# JoystickFreeJoy

*基于 FreeJoy 固件的高精度双轴霍尔传感器 USB-HID 低成本 3D 打印摇杆方案*

# 许可证

本项目采用 MIT 许可证。有关详细条款，请参阅 LICENSE 文件。

# 源项目地址

- **FreeJoy**：https://github.com/FreeJoy-Team/FreeJoy
- **底座机械结构**：https://www.thingiverse.com/thing:2496028

# 烧录程序

1. 仓库提供了 freejoy 固件和 cfg 配置文件，烧录在 GUI 配置程序中导入配置文件即可使用。
2. PCB 上设计了一个使用间距 2.0mm 4P 的烧录针，通过 ST-Link Utility 烧录程序。

# 其它

1. 目前 Z 轴 (主控板) 的 PCB 基于 AD22 绘制，提供了源文件，Y 轴 PCB 基于嘉立创 EDA 绘制暂未提供源文件 (以后会转移到 AD 上提供到仓库)
2. 模型基于 Solidworks 2022 绘制，提供了源文件，后续会追加 STL 文件方便导入打印机打印。