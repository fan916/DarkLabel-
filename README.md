# DarkLabel-
1、打开exe文件

![alt text](image-2.png)

2、第1处选择图片位置

3、第2处选择数据集类型，选择

![alt text](image-3.png)

4、第3处选择标签名称，目前只选择0即可

![alt text](image-7.png)






对于标注跟踪数据来说，可以选择![alt text](image-4.png)这部分的跟踪方法粗标注后微调，点击![alt text](image-6.png)会按照选择的跟踪方法标注下一帧。



Tracker1(robust)
插值法，每次一个目标。
首先在第一帧点击Begin Interpolation，然后画目标bbox，按↓键往后几十帧，在找到该目标画出bbox，点击End Interpolation，然后就可以看到中间帧该目标都被圈住了，效果挺好的。

Tracker2(accurate)
在当前帧画出多个目标bbox，然后点击next,这些算法，越往后bbox就越不准了，但是可以多个目标同时跟踪，插值效果比较好，但是只能一个一个目标跟踪，自己选择。


标注完成后定时点击![alt text](image-5.png)保存标签