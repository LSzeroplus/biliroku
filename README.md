﻿# biliroku
bilibili 生放送（直播）录制

BiliRoku v1.4.1

Licensed by GPLv3 详情请见LICENSE文件

BiliRoku是用来录制bilibili生放送（直播）内容的。
说录制其实不准确，其实是直接接收直播的视频流并保存到本地。

使用方法：输入房间号。
房间号就是看直播的网址：http://live.bilibili.com/xxxxx
里面xxxxx的数字。

作者：Zyzsdy
（主页 http://zyzsdy.com/biliroku)

运行平台: .NET framework 4.0以上

-------------

更新说明：

1.4.1 build 27 (2016-8-19)

修复了由于弹幕服务器连接不稳定造成的崩溃退出问题。（紧急修复，可能仍有bug）

1.4.0 build 26 (2016-4-21)

改善高分屏下的显示效果。

改善了弹幕连接模式。

增加录制模式：现在可以等待主播推流开始后自动录制了，也会根据主播的推流自动中止哦。

重构代码架构，增加稳定性。

修复一些bug。

1.3.1 build 15 (2015-11-22)

修复一个统计模块可能导致无响应的bug。

1.3.0 build 14 (2015-11-22)

新增：弹幕录制功能——自动获取直播间的弹幕并以xml格式保存下来。可以用本地弹幕播放器播放。

修改保存文件的方式。

增加一个统计模块。

1.2.3 build 13 (2015-11-14)

支持自动读取，写入配置。在重启程序后自动加载配置。

1.2.2 build 12 (2015-11-11)

B站短房间号现在可以正常录制了。
