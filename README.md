# 🌐 On-line Radiation Detector

**在线辐射检测仪**，基于 RA6M5 和瑞萨开发环境开发。

## 📦 项目组件
- **RA6M5**: 主控制器
- **ATGM332D GPS**: 北斗模块
- **迪文串口屏**: 显示模块
- **ESP8266**: Wi-Fi 模块

## 🚀 功能
- **物联网实时监控**: 实现对辐射数据的实时监控。
- **GPS 定位**: 集成 ATGM332D 模块进行定位。
- **显示数据**: 通过迪文串口屏显示检测数据。
- **联网功能**: 采用 ESP8266 模块实现 Wi-Fi 连接。
- **基于 ThingsCloud 平台**: 数据传输和监控基于 ThingsCloud 平台。
- **MQTT 协议**: 使用 MQTT 协议进行数据通信。

## 🛠️ 开发工具
- **瑞萨开发环境**: 使用瑞萨开发环境进行编程和调试。
- **thingscloud**：物联网平台。
- ![image](https://github.com/pieceofApple/On-line-radiation-detector/assets/116827010/746dfe3e-0a07-4495-9166-0d5c06a313b5)

- ![image](https://github.com/pieceofApple/On-line-radiation-detector/assets/116827010/9c4786ae-7f81-44e1-9546-f374bec5048b)

## 调试现象
  ![RA6M5调试](https://github.com/pieceofApple/On-line-radiation-detector/assets/116827010/b128dc85-3abc-45e6-9c16-f649b240dfba)

## 📡 连接示例
```plaintext
RA6M5          ATGM332D GPS     迪文串口屏       ESP8266
VCC            VCC              VCC              VCC
GND            GND              GND              GND
TX             RX               RX               TX
RX             TX               TX               RX
