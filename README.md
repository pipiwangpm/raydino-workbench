# RayDino 测试标定工作台

Web 交互原型，包含设备连接、关节标零、硬件控制、遥控器、SN 编订和工程调试。

在线访问：https://pipiwangpm.github.io/raydino-workbench/

## 使用
直接打开 index.html，或用静态服务器启动本目录。无需安装依赖。

- 连接：Wi-Fi、蓝牙、局域网 IP。
- 标零：15 个关节、保存及验证。
- 硬件控制：录音、回放、摄像头、ToF、风扇与 LED。
- 遥控器：方向控制、功能键与头部控制。
- 工程调试：参数、CSV、OTA、离线升级、固件烧录及日志。

## 快捷键
W/S 前后，A/D 左右转，Q/E 左右平移，方向键等同 WASD，空格停止。
1–9 对应功能按键，I/K 头部上下，J/L 头部左右。按钮显示键位。

## 原型范围
设备连接、遥测、动作、升级与烧录均为模拟流程，尚未连接真实机器人；不会操作电脑网络或硬件。数据只保存在当前浏览器，可导出记录。CSV 和报告保留模拟数据标识。

## 文件
index.html 为入口，app.js、engineering.js、workbench.js、remote.js 实现交互；style.css、workbench.css 提供样式。
