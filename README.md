# Esp32_ros(验证终端)
普通ROS机器人成本高，在运行大型算法时机载电脑算力要求高，例如在运行VINS-FUSION算法时，需要用上NUC，由此希望实现低成本ROS节点通讯ESP32,来验证ROS集群小机器人，通过单台电脑的算力来控制数个不同的终端，ESP32四层板设计，板载自动下载电路,基于ROS微型机器人的验证终端
```bash
主控:ESP32-WROOD-32E
串口芯片：CH340C
开发环境:Platformio
```
自动下载电路对照表：
```bash
DTR RTS  EN  IO0
 0   0    1   1
 0   1    1   0
 1   0    0   1
 1   1    1   1
```
1.Toplayer

![image](https://github.com/TheRoadToReality/Esp32_ros/blob/main/Esp32_Fireware/asset/ESP32_3D_TOP.png#pic_center)

2.bottomlayer

![image](https://github.com/TheRoadToReality/Esp32_ros/blob/main/Esp32_Fireware/asset/ESP32_3D_back.png#pic_center)

3.布线

![image](https://github.com/TheRoadToReality/Esp32_ros/blob/main/Esp32_Fireware/asset/asset/布线.png#pic_center)

4.render

![image](https://github.com/TheRoadToReality/Esp32_ros/blob/main/Esp32_Fireware/asset/asset/render.png#pic_center)
