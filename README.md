# bili-uget

#### 介绍
批量下载B站up主视频

#### 软件架构
pyqt5
you-get
一个线程负责界面加载，另一个线程使用协程开启异步多任务下载


###安装教程

1.  pip install you-get
2.  pip install PyQt5
3.  pip install requests

#### 使用说明

1.  没有python环境的直接执行exe文件即可，不需安装任何包，但是需要下载个ffmpeg,别忘了将ffmpeg.exe所在目录添加到环境变量,
    合并为mp4文件时候需要用到,这个快200M了就不放进来了   [ffmpeg下载](https://pan.baidu.com/s/1ZVWakNq27AnIt8ZvPk6sXw) 提取码: mr45 
2.  有python环境的直接执行.py文件即可

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  可以根据up主uid下载该up上传的所有视频，自动以mp4格式保存到exe或.py文件同级的 video/up名/分区/文件名.mp4
2.  支持分区视频下载和同时多个视频下载
3.  cookies.sqlite文件是个空的，如果你是大会员想下载更高清视频可以找下怎么从火狐浏览器导出你的cookie文件，然后替换掉这个文件即可
4.  不要同时下载过多视频，最多不要超过20个。
5.  分P视频的下载还没做过几天会补上，ui文件混在py里代码写的很乱，后续会分离出来
6.  希望用这个更多是下载视频来学习，而不是盗UP的视频谋利。
