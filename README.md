## GitTest
### 二狗手把手教你如何上传开源项目到GitHub上

##### 导语

> 很多iOS开发的朋友不会上传项目到GitHub上，其实方案有很多，使用GitHub的客户端，或者使用GitHub提供的HTTPS/SSH方案。笔者习惯了使用HTTPS的方式上传开源项目到GitHub上，这里，笔者就分享下自己的做法！
说下大体思路：首先你在GitHub上有一个存放项目的代码仓库，然后创建GitHub的代码仓库，之后Clone到本地，在本地完善代码，最后Push到GitHub上。

##### 第一步：在GitHub上创建代码仓库，记得添加忽略文件和README；

##### 第二步：拷贝地址，待会儿要将GitHub项目Clone到本地。操作如下图，比如拷贝到的地址为：https://github.com/CoderSimons/GitTest.git

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step2.jpg)

##### 第三步：打开你的终端（Terminal）或者iTerm。先指定要把GitHub上的项目Clone到本地的哪个目录，然后Clone下来。笔者使用的是iTerm，在终端中要写的Linux指令是相同的。操作如下图：

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step3.jpg)

##### 第四步：打开Xcode创建项目, 项目的.xcodeproj文件要和.git文件夹在同一级目录, 只有它们在同一级, .git文件夹才能管理项目源码。或者把你要上传的项目拷贝到对应位置。

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step4.jpg)

##### 第五步：用Xcode打开你的本地项目，点击菜单栏中的Source Control下的Commit项，将新建的项目文件Commit到本地仓库，再Push到GitHub。Commit到本地仓库的界面中有Push to remote选项, 建议勾选。之后想要直接Push到GitHub, 可以直接点击Source Control下的Push项会先Commit到本地再Push到GitHub。注意，这里的Commit Message是必须要填写的，用于记录本次提交的代码干了些什么。

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step5_1.jpg)
![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step5_2.jpg)
![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step5_3.jpg)

##### 第六步：如果你想要在GitHub的某个代码仓库的页面添加一些文字，图片或GIF来进一步向全世界人民展示你的项目或介绍你的框架的使用方法，你可以把图片或GIF资源Push到GitHub的代码仓库中，在README文件中使用MarkDown语法编辑一段文字，再引用这些图片或GIF文件，对你的项目进行一番介绍。

> 图片/GIF资源的地址如何获取？在GitHub上打开这个图片/GIF文件，在浏览器中拷贝地址。然后编辑README文件，下面有如何在README文件中引用图片资源的MarkDown写法。MarkDown语法打开浏览器满世界都是，这里就不介绍了。

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step6_1.jpg)
![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/step6_2.jpg)

> 祝好运~

![image](https://github.com/CoderSimons/GitTest/blob/master/GitTest/Icon.JPG)
