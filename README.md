Hi👋  <img align="right" src="https://komarev.com/ghpvc/?username=hanchengxu&style=flat-square"/>
-------
#### 中文 | [日本語](https://github.com/a2181745/a2181745/blob/main/README-ja.md) 
大家好，我是Hanchengxu，一名从业8年的web软件开发工程师。软件编程对于我不仅仅是工作，更是一种业余爱好。

<!-- <a href="https://github.com/hanchengxu/github-readme-stats">
<img align="center" src="https://github-readme-stats.vercel.app/api?username=hanchengxu&show_icons=true&include_all_commits=true&theme=dracula&hide_border=true" alt="Anurag's github stats" />
</a> 
<a href="https://github.com/hanchengxu/github-readme-stats">
 <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hanchengxu&layout=compact&theme=dracula&hide_border=true" />
</a> -->

![](./profile-3d-contrib/profile-season-animate.svg#gh-light-mode-only)
![](./profile-3d-contrib/profile-night-rainbow.svg#gh-dark-mode-only)


最近痴迷于arduino，正在制作一款IoT仓鼠笼，如果感兴趣，不妨往下看看👇

## 背景
2020年7月，因新冠疫情在家办公已半年有余，为了缓解居家的枯燥，和夫人一同饲养了一只雄性罗布罗夫斯基仓鼠🐹。
至此开启了我们的养鼠生涯。

养鼠之后发觉，作为夜行性动物的他，日间活动及其单调，除了吃粮、喝水之外整个白天几乎都在睡觉。而等我们拖着疲
惫的身躯入睡的时候，它才开启一天的生活。很好奇，这可爱的小生灵，一晚上究竟会在跑轮上跑多远的距离呢。这也是
制作这款仓鼠监控系统的初衷。

## 单机版
恰巧手里有一只arduino uno 开发板，为了获取仓鼠夜间运动数据，我便在uno上制作了初版的仓鼠跑圈计数程序。
因为uno板单核心、内存小(其实是自己水平有限哈哈)等原因，单机版的程序目前仅支持下面几个功能  
1. 记录总圈数  
2. 计算总里程  
3. 数据支持显示在0.96的单色OLED屏幕 

单机版也是各位鼠友最容易部署安装的版本了。它仅需要一块uno、一块屏幕、一块红外传感器即可构建成功。
当然您可能也需要一定的DIY能力里和对arduino平台的了解。(组装线路图还没来得及上传，抱歉(。・＿・。)ﾉ)

👉[单机版项目地址](https://github.com/a2181745/hamster_arduino) 

## IoT版
经过几次版本迭代，arduino已经无法满足接下来的需求，于是入坑了esp8266和esp32开发板，开启了物联网小鼠箱的制作之旅。
不得不说，对于单片机开发和C语言知识有限的我，arduino平台简易的API帮助我快速地搭建了原型机。  

用上esp32之后更是如虎添翼，它的多内核以及更大的内存让我有了更多挥霍的空间。

目前IoT版的仓鼠箱进度如下(✅:已完成 ❌:未完成)
1. 统计每日运动信息，并显示在终端(比如网页✅，微信小程序❌)
2. 记录仓鼠箱的环境温湿度和加热垫部位的温度✅
3. 配置Iphone的快捷程序可以使用Siri实现自动喂食功能✅
4. 以小时为单位分析仓鼠夜间活动数据✅
5. 实时查看当前仓鼠运动数据(目前2分钟会更新一次数据，计划使用Websocket做到实时观察)❌
6. 使用esp32 cam 获取仓鼠箱内部图像照片并显示在网页❌
7. 分析图像照片分析仓鼠当前状态:在窝中休息，喝水，运动❌
8. 添加红外传感收集仓鼠日常运动轨迹❌
10. 将上述收集到的数据利用机械学习神经网络使我的仓鼠永远活在服务器中❌

正如最后一个目标那样，可爱的小家伙平均寿命虽只有2年左右。可能项目还未开发完成，它就会离开我们去了吱星🌎。
但是作为程序员的我，如果能收集到足够多的数据，相信它会以另外一种形式永远陪伴着我们。虽然目前我并不具备
实现上述功能的全部知识，但作为寿命比仓鼠大几十倍的物种来说，我认为还是有时间和机会去实现这个远大的目标的。😊

## 围观🔥🔥🔥🔥
目前您可以来我的项目主页，观看我家鼠子的运动信息。  
这可它真实的运动数据哟💪

项目主页👉：  
 　　　　　　https://hanchengxu.com/#/hCare (大陆访问迅速⚡)  
 　　　　　　https://github.hanchengxu.com/#/hCare (境外)

最后奉上一张他的照片  
<img src="https://github.com/a2181745/hamster-esp32/blob/main/hamster.jpg" width = "600" height = "360" alt="" align=center />


对了，他的名字叫 **溜肉段！😃**

