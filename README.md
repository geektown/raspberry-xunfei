# raspberry-xunfei
科大讯飞树莓派语音测试
=====
## Raspberry PI B型 代码库位置
/home/pi/xunfei/Linux_voice_1.109

## 环境配置
`export LD_LIBRARY_PATH=/home/pi/xunfei/Linux_voice_1.109/libs/RaspberryPi:$LD_LIBRARY_PATH`

`sudo ldconfig`

## 测试样例
```shell
chmod +x bin/tts_sample
bin/tts_sample temp.wav "Hello Jasper 这个是科大讯飞tts合成的文本。体验一下还不错吧？"
```

## 编译脚本
在sample目录中
