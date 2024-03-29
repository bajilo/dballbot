dballbot
========

Dragon Ball Robot For App Engine

访问 [dballbot.appspot.com](http://dballbot.appspot.com/) ([国内链接](http://dballbot.appsp0t.com/)) 获得预览

支持Android，IOS版龙珠Q传，妖精尾巴各版本

本app使用python开发，可部署在google app engine上24小时运行，也可单击运行特定脚本。
最新版本包含3.0.1版签名算法，欢迎使用其他语言改写。

主要功能
-----------

1. 模拟客户端任意操作，单机脚本和服务器可共享session同时运行
2. 24小时副本，掠夺，抢碎片，购买乌龙，升级人物装备，布尔玛，定时吃面，收建筑，龟屋，活动抽免费武者
3. 多线程打Boss抢最后一击
4. 智能试炼，预估对方阵容，参考[Rush Team](http://dballbot.appspot.com/rush) （[国内链接](http://dballbot.appsp0t.com/rush)）
5. 抢活动卡
6. 小号给公会刷钱
7. 多帐号配合无等级、宿敌限制掠夺
8. 同时控制上千帐号，体验指挥千军万马的快感
9. 自行探索新功能：刷钱，刷钻，刷潜力，刷助阵 （注意低调）

另有修改版客户端，可跳过登录，使用任意帐号进入游戏。

私服服务器策划中，欢迎有志之士联系参与。 EMail：ganli.leo AT gmail.com

Q&A
-----------

Q：使用外挂是否有封号危险？

A：

外挂的原理是模拟客户端给服务器发消息，例如，下面是掠夺发给服务器的消息：


        POST /dragon/grab/fight HTTP/1.1
        Host: 203.195.191.62
        Accept: */*
        Accept-Encoding: gzip
        Content-Length: 169
        Content-Type: application/x-www-form-urlencoded
        
        sig=f36f0f53b2ac64fdcd5e4b818289ece0
        sessionKey=102411344-7dbefbc9-402a-42a0-bbd2-4ea8f24b0710
        enemyId=102407576
        version=1.1.0
        channel=00000003
        time=1393050884310.000000


外挂发的和客户端发的一模一样，GM根本无法区分。所以除非利用了系统漏洞刷东西，或者太高调惹了大R，不会有封号的危险。

Q：玩手机游戏还用外挂，有意义吗？

A：

现在手机卡牌游戏都很坑爹，即使充钱了也要尽量多时间守着游戏，因为体力精力都是缓慢恢复的，建筑物需要守着，布尔玛需要守着，浪费了大量陪家人，泡妞的时间，简直是谋杀生命。

这游戏最坑的就是Boss战，每分钟点1下，刚出来我朋友就跟我说，手动打Boss的都是SB吧，被游戏玩成这样。

有了外挂，每天只要花2分钟进游戏看看有没刷到新东西，调整调整阵容就行了，其他时间可以享受现实生活。

Q：何时发布？

A：

由于本程序原本是自己做了给自己玩的，有些功能不适合所有人，现正在调整中，请关注本页面获得最新消息。
