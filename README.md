# 简介
RPMC公告板 & BUG/问题回复
一些关于RPMC服务器的讨论、计划、BUG、正在面临的问题

# RPMC宣言/历史
[点我](./DECLARATION.md)

# 讨论、BUG、建议
请发ISSUE以便管理

# 服务器功能讲解介绍/使用帮助
- [BaseGamerule](./help/BaseGamerule.md)
- [登录密码/CatSeedLogin](./help/CatSeedLogin.md)
- [Java-Bedrock互通/Geyser](./help/Geyser-Spigot.md)
- [原版加强/Tweakin插件](./help/Tweakin.md)
- [服务器核心组件/EssentialsX](./help/EssentialsX.md)
- [坐下！——各种姿势插件/Gsit](./help/Gsit.md)
- [地图画/Images](./help/Images.md)
- [彩色命名/ColoredAnvils](./help/ColoredAnvils.md)
- [创世神/WorldEdit](./help/WorldEdit.md)
- [更好的附魔/ExcellentEnchants](./help/ExcellentEnchants.md)
- [负魔书/DeEnchantment](https://user-images.githubusercontent.com/65019366/182375428-b02a48ea-8b45-49f2-b6b4-a425c46fd74a.png)
- [Paper服务器上的SandDupe/GravityControl](./help/GravityControl.md)
- [⚔EliteMobs⚔](./help/EliteMobs.md)
> 未完待续……

# 目前需要解决的问题
## 服务器软件
- [ ] 时刻关注[EssentialX](https://github.com/EssentialsX/Essentials)插件更新状况
- [x] 时刻关注[IronElevators](https://www.spigotmc.org/resources/ironelevators-1-4-6-1-20-x.19451/)插件更新状况
- [x] ~~时刻关注Ess-PlaceHolder-TAB联动情况~~ 毁灭吧，升1.20之后placeholder一直抽风，excenchant也受影响，已经把TAB换成TABTPS了
- [x] 时刻关注[SlimeFun](https://github.com/StarWishsama/Slimefun4)插件更新状况
- [ ] 时刻关注[Veinminer](https://github.com/2008Choco/VeinMiner)反选功能的更新

## 服务器状况
- [x] mca删除无用旧版区块 现在的地图焕然一新！！

## 游戏
- [ ] [监督无赖WuThreeThree完成那一大堆烂尾工程](./WUTHREETHREE.md)
- [ ] 重建电力工程
- [ ] 烂尾楼改造成地图博物馆 - 执行获取所有地图命令
- [x] 修缮未建完的RepentStar的家 - 三楼修缮完成！
- [x] 搬迁工业设施到末地(刷石机重置)
- [x] 把旧建筑暂存场地搬迁至海上
- [x] 把村民繁殖机放到主世界
- [ ] 在每个人头上写上自己要干的事情(指令/插件) 

## Bug
- 没有任何征兆的服务器自动重启(通常发生在玩家进出后)(未找到原因)
- 僵尸猪人不踩海龟蛋 魏佬的噩梦

# 服务器目前遇到的问题(基本无解)
真的很生气！怎么会有这种傻逼。
目前我遇到四个`ServerSeeker`/`Bunger`/`cuute`/`Minecraft`
```log
[00:26:37] [Server thread/INFO]: com.mojang.authlib.GameProfile@534e44a8[id=cc7155c9-d7f0-3cd6-bfc3-fcd1cd0479a9,name=cuute,properties={textures=[com.mojang.authlib.properties.Property@79bf88b5]},legacy=false] (/176.58.106.79:42124) lost connection: Disconnected
[23:27:56] [Server thread/INFO]: Disconnecting com.mojang.authlib.GameProfile@693c0cc9[id=5faee1a6-b4f5-3eb9-b90a-dd57407c43ae,name=ServerSeeker,properties={textures=[com.mojang.authlib.properties.Property@2b18552]},legacy=false] (/109.123.240.84:50652): 你没在白名单里！由于某些原因腐竹开启了白名单，若有需要请联系腐竹，Q3266306682
[03:55:10] [Server thread/INFO]: Disconnecting com.mojang.authlib.GameProfile@5c4367de[id=95608b22-7d7f-3267-b844-24cdd996c5ee,name=Bunger,properties={textures=[com.mojang.authlib.properties.Property@3d67d752]},legacy=false] (/147.28.173.143:36058): 你没在白名单里！由于某些原因腐竹开启了白名单，若有需要请联系腐竹，Q3266306682
```
以上是服务器日志的一部分，都是机器人(`Minecraft`机器人我遇到的较少，懒得翻日志了)，不像正规网站的扫服机器人，它们曾尝试*进入*服务器，要命的点在下方列举：
1. 它们会自动记录曾经在线的玩家名字，然后用玩家的名字尝试进入，已经遇到过了，所以我使用插件隐藏了在线玩家名
2. 它们通常会在服里没有玩家的时候尝试进入，所以根本不易察觉
3. 换端口没用的，我换了照样是遇到它们
4. 每个名字下的IP隔几天会变，不过基本IP位置不变
5. 不止我遇到了这个问题，详情如下

[一些腐竹为这个问题做的帖子合集，每一个帖子都很有价值，分析了它们的IP分布](https://www.reddit.com/r/Minecraft/comments/14mah9o/list_of_known_minecraft_server_seeker_bots_cuute/)
[甚至还有一个Google文档来曝光收集它们的行踪](https://docs.google.com/spreadsheets/d/1AeNtPHAKepa8OPTfcHSeX9ltAFCTWCHqGrcZ_Abb30c/edit#gid=1673550978)

# 计划
暂无

# 展望未来
~~前途迷茫~~

# QQ、钉钉群
Q:群：769232093
D:(需先加我钉来拉群，我钉:1o5-rby5d6h844)

# Github上的朋友
你偶然间发现了这个仓库，也想学着这样为玩家们提供帮助信息？
欢迎交流！

我的QQ:3266306682,Tele:@repentstar

本仓库遵循MIT协议，所有文字都是我原创（如果使用了辅助工具我会在文末注明，使用AI技术辅助写文章目前来说是完全合法的），如果你引用了本仓库的内容请注明出处并标出本仓库链接，要求并不高

复制粘贴白嫖者祖坟冒黑烟，下辈子株连九族