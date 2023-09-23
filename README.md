# War Thunder BlueberryPie Air Assistant
### Usage
 - This is a bot script for basic AirRB usage in War Thunder. It supports base-bombing and rush-n-die.
 - The script supports locating the bases automatically, turn towards it, and drop the bombs, fly until death, quit after death, then start a new game.
 - Because Gaijin has been banning bots, the script added support for semi-auto gameplay, and is planning to remove the full-auto feature.
 - Under the semi-auto version, the script **will not** automatically join a game but **will** auto-spawn after joining, it **will not** aim at a base, the player has to point the plane in the direction of a base. The script **will** automatically go into the scope vision and drop the bombs when over a base, and **will** quit to hanger after death, but **will not** join a new game.
 - Please beware that usage of any bots are against the game's rules. This script is a simple script, only made in the free time of my computer science image processing class, it will not try to deter any detection methods, nor will any long-time supports be made.
 - Please understand that a human, any human, can be more efficient than a bot. So if you decided to use this script, don't spread it around. Also, it's free to use, so don't try to sell it anywhere.
 - If I, under any circumstances, recieved request to take this thing down, I will cooperate accordingly, and private or delete the repo.
   
## 战争雷霆-蓝莓派-简约空战助手
### 前言
 - 本软件脱胎于大学暑期图像识别基础课课上实践作业，主要的点为在游戏中根据不同页面点击对应的图标。没有用到什么高深技术，现结课后根据规定修改后免费公开，请勿售卖本软件，造成的后果概不负责。
 - 本软件修改自苹果派助手
 - 可以用于战争雷霆空战挂机。不保证抢得到战区。
 - 虽然但是，该说的话还是得说的：你手打的效率比脚本高多了。如果你游戏打得银狮掉得只能用脚本了，那想拿去用就拿去咯。反正我话放在这里了，出了事也别找我，被骂了也别找我，我这边骂的人多起来我就把这个repo给private掉。

#### 新·半自动使用方法
 - Gaijin下场封禁包括空历的脚本后，本脚本已经取消了全自动炸战区，改为半自动
 - 半自动轰炸功能：进入对局后自动出生，在出生后30秒左右进入投弹视角，检测到战区时可自动修正航线，然后摁空格（炸弹最好不要超过20个），死亡后自动J3以及返回车库。
 - 半自动下你需要做的：点击进入游戏，出生后鼠标对准一个战区，然后就可以去刷手机了，结算后手动点击进入游戏即可进入下一局。

#### 使用方法
    1.找到最新版下载，解压缩，双击运行文件
    2.按照设置好键位，点击开始
    3.开始运行后，选中战争雷霆窗口，会自动探测到
    4.运行途中不要遮挡或移动战争雷霆游戏窗口，不要选定其他窗口
    5.如要停止，点击停止按钮，脚本会自动退出
#### 注意事项
    1.事先说好，这是挂机脚本，效率远低于手打，而且会占用电脑（脚本操作时不能使用电脑）
    2.挂机中的收益都会存在battlelog文件夹里，最多存储1000局，请按需查看和删除
    3.不会经常更新。写脚本是编程的副产品。
    4.不支持敌人识别，不含AI寻路，不包含自瞄和提前量，不一定会炸到战区
    5.推荐弹链全部用默认，炸弹用不要钱的默认炸弹
    6.永久免费，永久免费，永久免费，别拿去卖
    7.网上有效率比这个高多了的版本，我技术力不足，别人技术好一些
#### 其他可能的问题
    Q：我的log文件里面都是空的！
    A：这个是编码问题。我的机子是国内的GBK编码，程序做好了放在utf编码的机子上就会出现不写入log的问题。
       不影响使用。
       
    Q：脚本卡死，报错代码说窗口什么什么
    A：这个是win11更新了一些安全设定导致程序无法获取战争雷霆的窗口名称以及无法移动窗口至左上角。
       解决方法是用管理员模式启动脚本。

    Q：我直接打开exe文件结果脚本闪退了。
    A：因为路径不一样了。那个bat文件其实就是启动exe文件。所以你想直接通过exe文件启动，记得把exe文件移出来。
       就是移到bat文件的那个位置，这样就可以识别到需要的几个文件夹了（model和battlelog之类）
    
    Q：适配了哪些飞机？
    A：轰炸机必须有空出和投弹镜，其他飞机只要有空出就行。不适配喷气。不适配CCRP或CCIP

    Q：可以用银币飞机吗？
    A：可以，甚至可以用来刷配件，可以自动购买配件。但是维修费大于六千且自身没有高账的情况下强烈不推荐。
#### 目前的效率是？
    仅供参考。效率有太多因素了。有高账。
    图1，送死流，8小时30万银狮+16万研发
    金B-25，炸战区，2小时25万银狮+13万研发
    
#### 有做更高级版本的打算吗
    没有。
