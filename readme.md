# 锄大地助手

本项目为一个微信小程序，在微信中扫描下面小程序码即可使用：

![](./miniprogram_code.jpg)

## 功能介绍
该小程序为一个辅助记录工具，用于进行锄大地游戏时记录各人累计剩余牌数，省去使用纸笔的麻烦。采用的规则是每局剩余1-7张时按一倍计算，8-9张时2倍，10-12张3倍，13张4倍。每轮计算时选择实际剩余牌数即可，程序会自动按相应倍数进行换算。
该小程序有三个页面：

### 1.首页

![](http://os738issp.bkt.clouddn.com/BigTwoShow_1.jpg)

点击“开始”按钮后，程序先对本地存储进行检查，看是否有历史数据的存在，若无则进入新建牌局的页面，若有则弹出对话框询问用户选择新建牌局或者读取历史数据。
另外该页面有显示小程序当前版本信息，以及小程序功能介绍信息的显示按钮。

---

### 2.新建牌局页面

![](http://os738issp.bkt.clouddn.com/BigTwoShow_2.jpg)

该页面用于新建牌局时记录每人的姓名信息。填写并点击“确认”后进入功能主页面。

---

### 3.功能主页面

![](http://os738issp.bkt.clouddn.com/BigTwoShow_4.jpg)
![](http://os738issp.bkt.clouddn.com/BigTwoShow_5.jpg)

改页面有三个部分，首先是改局游戏每一轮的详细数据，样式与平时使用纸笔时记录相似。第二个部分为数据统计图表，以比较直观的图表形式展现该局游戏的进展，有柱状图和折线图两种，点击相应按钮可进行切换显示。最下面为相关的功能按钮，游戏正常进行时为“结算新一轮”的按钮，点击后会在下方弹出数字拨盘，用于选择最新一轮中每人的剩余牌数：
![](http://os738issp.bkt.clouddn.com/BigTwoShow_3.jpg)

当在某一轮记录之后，若有至少一人的累计剩余牌数已经超过100，则下方“结算新一轮”的按钮隐藏，显示“退出”与“新开牌局”的按钮。（该处的“新开牌局”按钮为保持当前玩家姓名不变的情况下新开一局游戏，若需要更新玩家姓名需点击“退出”后在主页中新建牌局）


