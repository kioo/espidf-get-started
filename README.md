# espidf-get-started
这个项目是我在淘宝上买的开发版
使用 platfram.io 在 visual code 工具上作为插件创建的一个测试项目
这个项目用来将实例代码打包并且写入到开发版中能正常运行

## 难点记录
1. 第一次创建工程困难：对完全陌生的领域的探索，总是需要些困惑
2. 不知道怎么配置：看官网的教程
3. 创建实例项目找不到对应的开发版的型号： Board 选择 Espressif ESP32 Dev Module 就可以
4. 端口选择错误导致代码烧录不进去：默认检测的短裤可以看日志，但是烧录不进去，需要指定端口，在 platformio.io 配置文件中 添加 `upload_port = /dev/cu.wchusbserial53100008761`
   端口列表可以在 Devices 中查看
