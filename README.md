# iHloveDwordsU

账号密码是智慧杭电的

为保护密码隐私，输入密码时不显示但其实有输入，输入后回车即可。

需要python环境，安装requests和PyExecJS库

运行main.py


  
  

莫名其妙退出了的话请检查账号密码是否输入正确，输入的格式是否正确（比如输入了浮点数之类的）

在测试时发现多次密码输入错误时可能需要过一段时间尝试，具体可以访问：https://skl.hduhelp.com/ 用智慧杭电账号密码登录检查自己是否能正常登录（账号密码是否正确）



2023.4.12更新：

修复了原来一词多义与一个中文多个英语单词的题目无法做出的情况，在修正了这个问题之后，每次测试基本能做到100分（？

将测试的时间单位由min变更为s，满足时间更精准的需要（7min40s == 460s）

为避免尴尬输入在240~480范围外的数字默认460



由于题库基本完善以及有题库自动更新功能，因此爬取题库选项意义降低，所以删除了爬题库的选项。

同样，由于脚本基本完善，基本能出高分，准确模式的意义降低，所以删除准确模式，添加选择分数的选项。



选择的分数不在0~100范围内的，取最高可以拿到的分数

在0~100范围内时，由于题库不一定全，存在有题库之外题目情况，所以实际分数不一定等于选择的分数，但一般情况下偏差不大。



