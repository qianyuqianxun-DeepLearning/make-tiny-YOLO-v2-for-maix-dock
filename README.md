本项目是使用sipeed公司的勘智K210人工智能芯片进行设计的深度学习模型部署教程，

完整教程请参考：
https://blog.csdn.net/baidu_39629638/article/details/105198926

欢迎关注我的CSDN的社区:千与千寻ML
网址：https://blog.csdn.net/baidu_39629638?spm=1000.2115.3001.5343

维信公众号:AI学习经历分享

博主微信：AIxeuxijingli

![image]（https://github.com/qianyuqianxun-DeepLearning/make-tiny-YOLO-v2-for-maix-dock/blob/master/qrcode_for_gh_8ded28aa9760_258(1).jpg）

欢迎关注，一起学习进步~

以下是完整的代码以及操作教程资料

下载此工程样本数据集：

链接：https://pan.baidu.com/s/1fpgWtH1Wr6l26wwY-_8NRQ 提取码：4z7r 

在工程根目录下将[train_ann.zip]和[train_img.zip]解压到文件夹的根目录下

下载maix的固件烧录：

链接：https://pan.baidu.com/s/15K9zFWbQX3wf9IwQa2Z4Wg 
提取码：jwob 

下载数据集标注工具labelimg（源代码形式，非exe执行程序）

链接：https://pan.baidu.com/s/1HgmZuTsYG98eAMN4pw-IZg 
提取码：xly9

下载ncc工具箱：

链接：https://pan.baidu.com/s/1AEU-RKJp9qwsd_082LU6Cg 提取码：igzx

将[ncc_0.1_win.zip]放置在工程根目录，解压到当前文件夹，等待转化

在[configs.json]中修改网络类型，lable标签（如raccoon），和其他参数 注意存放图片(train_img)和存放注释(train_ann)的文件夹名称

Copyright
* See [LICENSE](LICENSE) for details.
* This project started at [basic-yolo-keras](https://github.com/experiencor/basic-yolo-keras)&[basic-yolo-keras](https://github.com/experiencor/basic-yolo-keras).   

Reference
（1）https://github.com/TonyZ1Min/yolo-for-k210
