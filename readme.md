## 简介
这是一款我在业余时间独自开发的一款数独app，里面可以玩数独，提供了难、中、易各500道数独题目。除了玩数独之后还可以完全解数独，或者提供下一个步骤。另外还提供了自动生成数独的接口。
### 下载
apk下载地址：https://www.pgyer.com/ezPc
github源码地址：https://github.com/huolizhuminh/sodu
### 玩数独

点击新游戏进入玩数独页面，有易、中、难三种水平可以选择。

![玩数独1.png](https://github.com/huolizhuminh/MyImages/blob/master/sodu/玩数独1.png?raw=true)

选择其中的一个空白格，就可以进行输入。

![玩数独2.png](https://github.com/huolizhuminh/MyImages/blob/master/sodu/玩数独2.png?raw=true)

点击答案按钮会显示整个数独题目的答案。点击提醒时，如果已填入的数据错误，则会更正错误数据，否则，会随机选择一个空白格，填入答案。

![玩数独3.png](https://github.com/huolizhuminh/MyImages/blob/master/sodu/玩数独3.png?raw=true)

### 解数独
填入的值有两种，一种是原题，另外一种是玩者已经填入的值。完成填入后可以点击答案按钮，获取答案，也可以点击提醒按钮，提示下一步的步骤。

![解数独.png](https://github.com/huolizhuminh/MyImages/blob/master/sodu/解数独.png?raw=true)

### 自动生成数独接口
SoduFileGenerator中提供了startRun方法可以自动生成相应level的数独并保存


