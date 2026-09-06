- 3D model online preview: https://a360.co/4c95q6T
- PCB schematic and layout: https://oshwhub.com/hyan/project_uewvqdli
    - the antenna is not tuned for optimal, but it works somehow
    - PCB is 4-layered, 1.2 mm thick
- Electronics:
    - 头部主控是 ESP32-S3R8，底板 ESP32-C3N4 辅助，USB 正反接分别连接两个芯片
    - PCB 间用 SH1.0mm 导线连接，有些是两头同向，有些是两头反向，注意看 PCB 自行判断
    - 普通蓝色 180° 舵机，把两耳朵剪掉
    - GM12-N10 马达，短轴
    - 后轮用 8x4x14mm 轴承
    - GC0308 摄像头，其他型号因该也可以用，推荐 120° 广角
    - 50x30x40 锂电池，注意正负极
    - 3012 小扬声器

TODO: 
    use shorter wires and smaller connectors for the servos

LICENSE: TAPR Open Hardware License

firmware: https://github.com/hyansuper/cozmars.git

![](imgs/cad_img.jpg)
![](imgs/assembly.jpg)
![](imgs/3dprint2.jpg)
