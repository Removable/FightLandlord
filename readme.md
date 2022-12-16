# .NETCore斗地主服务端 + HTML5前端

本项目最终目标为AI斗地主，机器人最优方案对打。

声明：本项目谥在学习，任何用于违法用途的行为与作者无关。

如果对本项目感兴趣，欢迎加入 FreeSql QQ讨论群：8578575

# 项目演示

运行环境：.NET6.0 + redis-server 2.8+

下载 [FreeIM](https://github.com/2881099/FreeIM) 开源代码：

> cd ImServer && dotnet run --urls=http://*:6001

运行网络版：BetGame.DDZ.WebHost2

> cd BetGame.DDZ.WebHost2 && dotnet run

打开多种浏览器(chrome/Edge/chrome 隐身模式)，分别访问 http://127.0.0.1:5000

![](001.png)

![](003.png)

# 环境依赖

* .NETCore 2.1
* chrome
* redis-server(本地环境)

# 已实现功能

* 洗牌
* 发牌
* 抢地主
* 斗地主（游戏环节）
* 提示出牌
* 游戏结束

# 待现实功能

* 超时机制设计（抢地主、斗地主）
* 牌型分析
