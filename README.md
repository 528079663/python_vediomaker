# python_vediomaker
自动剪辑生成视频

#开始

moviepy == 1.0.0

python > 3.5

自行安装ImageMagick

缺少的库自行pip

1. 需准备一个时长大于50s的视频，有无背景音乐均可，命名为`in.mp4`
2. 需准备一个时长大于50s的BGM，命名为`in.mp3`
3. 提前在`args.txt`文本中定义好话术。
4. 在`args.txt`文本中添加讯飞语音合成（流式版）的`APPID`、`APIKey`、`APISecret`，以英文分号`;`分隔
5. 执行程序

