# CASIA-HWDB解压
数据集下载链接：
> http://www.nlpr.ia.ac.cn/databases/download/feature_data/HWDB1.1trn_gnt.zip
> http://www.nlpr.ia.ac.cn/databases/download/feature_data/HWDB1.1tst_gnt.zip

作者：Panverson
链接：https://www.jianshu.com/p/27efcf38c0c9
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

#### 介绍
CASIA-HWDB离线包HWDB1.1的解压

为什么会有三个文件
因为gnt2png.py这个文件是单纯的将gnt文件转化为png文件，例如![输入图片说明](https://images.gitee.com/uploads/images/2020/1030/213747_de141c53_7353706.png "gnt2png.PNG")
gnt2png_train.py以及gnt2png_test.py是将gnt文件解压到对应汉字的文件夹下，例如![输入图片说明](https://images.gitee.com/uploads/images/2020/1030/213804_4564ba21_7353706.png "gnt2png_test or gnt2png_train.PNG")
