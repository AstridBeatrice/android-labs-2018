﻿+ # 第六次实验  
+ ## 1. 实验目标  
+ 掌握Android网络访问方法；
+ 理解XML和JSON表示数据的方法。
+ ## 2. 实验内容  
+ 1.从网络下载一个文件（图片、MP3、MP4）；
+ 2.保存到手机，在应用中使用文件；
+ 3.将应用运行结果截图。 
+ ## 3. 实验步骤
+ 1.在实验五的基础上添加功能，实验五通过搜索按钮打开新界面后添加“更换专辑封面”并调整布局 
+ 2.同时设置可编辑文本，按钮功能是通过网络下载所输入url指向的图片并应用到textview中 
+ 3.运行后会有封面替换的效果
+ ## 4. 实验结果  
+ 第一个界面按下搜索按钮，进入播放界面，出现更换封面按钮和左边的输入框。
+ ![image](https://github.com/LoadedFreak/android-labs-2018/blob/master/soft1614080902417/%236/%E5%9B%BE1.jpg)
+ 输入网址后点击按钮，图片即被下载下来并覆盖上方的图片。
+ ![image](https://github.com/LoadedFreak/android-labs-2018/blob/master/soft1614080902417/%236/%E5%9B%BE2.jpg)
+ 输入不同的网址会替换不同的图片。
+ ![image](https://github.com/LoadedFreak/android-labs-2018/blob/master/soft1614080902417/%236/%E5%9B%BE3.jpg)
+ ## 5.实验体会
+ 实验过后基本掌握了简单连接网络下载图片的方法，可以选择通过分配线程提供下载。实验遇到的最大问题就是按钮无法实现功能，一直是点击后什么都没有出现，后来换成新的界面进行设置才解决了问题，看来应该是同一界面内不同活动发生了冲突或者是某些地方没有设置妥当，具体原因尚未找出
