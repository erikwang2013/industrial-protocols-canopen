# CANopen 协议包 — 需 PCAN-USB/SocketCAN 接口桥接

> [English](README.en.md)

CANopen 基于 CAN 总线的应用层协议。需要 CAN 接口硬件（PCAN-USB、IXXAT 或 Linux SocketCAN），通过内核 Bridge 层桥接。

## 安装

```bash
composer require erikwang2013/industrial-protocols-canopen
```

## 功能

CANopen NMT/SDO/PDO 桥接、BridgeConnector 连接管理

## 所需硬件

PCAN-USB (Peak System)、IXXAT USB-to-CAN、Linux SocketCAN (can0)

## 兼容框架

Laravel / Webman / Hyperf / ThinkPHP / Yii2 / Plain PHP

## 系统要求

- PHP >= 8.1
- CAN 接口硬件
- erikwang2013/industrial-protocols-kernel

## License

MIT — Copyright (c) 2026 erik <erik@erik.xyz> — https://erik.xyz
