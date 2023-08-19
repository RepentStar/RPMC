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
