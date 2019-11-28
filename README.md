# baidu-easyDL2xml
数据集导出并没有官方的api，本工具模拟浏览器下载实现，因官方可能调整相关链接及参数，并不能保证以后一定可用。（2019.11.28 可用。）
注意：easyDL有三个版本：经典版、专业版、零售版，本代码在专业版可以直接使用。
该版本的实现，借鉴 https://github.com/kooky126/easydl2labelImg （经典版 easydl2labelImg)

1 将本代码下载到本地

2 正常登录自己的百度账号，进入物体检测数据集页面

3 使用cookie工具(google chrome 可以使用EditThisCookie）导出当前cookie到cookie.txt文件，格式为 Netscape HTTP Cookie File

4 记下要导出的数据集id备用

代码基于python 3.x 版本

5、打开test.py, 设置downloaddateset的两个参数（参数为数据集id和本地保存目录，本地目录需要预先建好）
然后直接运行该文件，即可下载。

Note：下载数据的数量若出问题，查看 easydl2labelImg.py 的第147行说明。



