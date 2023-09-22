# Esp32_ros
ESP32四层板设计，板载自动下载电路
```bash
主控:ESP32-WROOD-32E
串口芯片：CH340C
```
```
自动下载电路对照表：
DTR RTS  EN  IO0
 0   0    1   1
 0   1    1   0
 1   0    0   1
 1   1    1   1
```
