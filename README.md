# NFC-MusicPlayer
一个使用NFC功能来播放音乐的DIY播放器
所需硬件：
1. ESP32C3
2. MP3模块
3. RC522读取模块
4. 小喇叭
5. 内存卡
6. WS2812B灯带

## 硬件连接图
![image](https://github.com/user-attachments/assets/5fdb3db6-b442-4bd7-a8ba-3232f445a0e6)

## 功能说明
1. RC522读卡器读取NFC Tag中标签，将标签信息传给ESP32C3
2. ESP32C3读取标签信息后，下达指令给MP3播放器，播放该标签下对应的歌曲，同时下达指令给WS2812B灯带展示相应的灯光效果


