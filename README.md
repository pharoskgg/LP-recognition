# LP-recognition
vehicle license plate recognition
# 说明
由于项目指导老师说暂时不能开源，所以代码就不上传了，简单的说下思路：目标检测加字符识别 ,首先将车牌和整车用yolo网络定位出来并将整车和车牌分别feed至resnet和crnn网络进行车型车颜色和车牌号码识别。不对车牌做预处理和分割，端到端识别。
本项目采用技术：yolov3+crnn+resnet进行牌车、车标、车型、车颜色做车辆综合信息识别
微信小程序端在线车辆检测车牌识别视频演示视频：https://www.bilibili.com/video/BV1SU4y1x7Ex/
