#Project1 说明文档
####姓名：罗宇琦
####学号：18307130255
##一、Github地址&Github Pages地址

##二、项目完成情况
本次项目涉及HTML、CSS及少数JS，本人bonus之外功能性要求全部完成。bunus除响应式布局实现可能不够全面之外基本完成。以下是各页面的截图（展示的是chrome上效果，firefox外观差不多，除了input框的默认表现不太一样，但不影响整体感官）
###主页
![主页截图](https://github.com/lyq-keep-going/Project1/raw/master/img/pageCuts/home1.png)
![主页截图](./img/pageCuts/home2.png)
![主页截图](./img/pageCuts/home3.png)
###浏览页
![浏览页截图](./img/pageCuts/browser1.png)
![浏览页截图](./img/pageCuts/browser2.png)
###搜索页
![搜索页截图](./img/pageCuts/serach1.png)
![搜索页截图](./img/pageCuts/search2.png)
###上传
![上传截图](./img/pageCuts/upload1.png)
![上传截图](./img/pageCuts/upload2.png)
###我的照片
![我的照片截图](./img/pageCuts/mpphotos1.png)
![我的照片截图](./img/pageCuts/myphotos2.png)
###我的收藏
![我的收藏截图](./img/pageCuts/myfavourites1.png)
![我的收藏截图](./img/pageCuts/myfavourites2.png)
###登录界面
![登陆界面截图](./img/pageCuts/index1.png)
![登陆界面截图](./img/pageCuts/index2.png)
###注册界面
![注册界面截图](./img/pageCuts/register1.png)
![注册界面截图](./img/pageCuts/register2.png)
###照片详情
![照片详情页截图](./img/pageCuts/details1.png)
![照片详情页截图](./img/pageCuts/details2.png)

##三、bonus完成情况和解决方法
###1、图片剪裁
我通过用div作为承载图片的容器，将图片作为div的背景，通过控制div大小实现剪裁效果。并使用css使照片尽量展示中间主体部分。在browser中我使用js展示16张照片也运用了这种方式。理论上来说，我所有的照片都使用的是normal文件夹中的照片（除非我漏改了orz，应该没有）
###2、响应式布局
响应式布局我主要控制的是宽度方面的响应式，因为高度目前我不知道是否能够有效控制。主要是在涉及页面宽度和margin-left、margin-right的大小用百分比控制，这样适度地缩放页面宽度，页面各组件的相对位置不会有太大变化。在index和register页面我使用了min-with因为当页面缩小幅度过大会使背景图高度不够，无论是否repeat都十分丑陋。
###3、界面美观
布局主要是依据示例微调了一些，界面风格以简洁大方为主，色调是蓝黄对比色，引入了blackjack字体来装饰标题。

##四、对本课程的建议
我觉得lab与pj内容多有重复，反复重复类似操作。lab要是能让我们学习一个小而有趣的知识点可能对pj会更有帮助。比如上次bootstrap学习运用轮播图就比较有趣。（但球球不要像软件工程这门课一样过头orz）
