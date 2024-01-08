# Dynmap

网页地图

[插件发布地址](https://www.spigotmc.org/resources/dynmap%C2%AE.274/)

# 使用文档

具体地址请进游戏看公告或进 QQ/钉钉群看公告

-   网页可使用滚轮缩放，但不能旋转角度
-   网页的左下角/下方会有聊天栏，可以和游戏内的玩家对话，玩家说的话会显示在地图上并保持几秒。聊天会自动匹配进游戏的 ip 来判断你是谁，继而在游戏中显示是谁用网页地图说的这句话，如果匹配失败，发送人仅显示`[WEB]`
-   网页的右方有一个小箭头，点开里面可以选择地图样式，查看在线玩家
-   可以自行在网页地图上标点，可自定义图标/名字。在游戏中前往要标点的地方，执行`/dmarker add`命令，命令详解见本页尾

## `/dmarker`命令用法

游戏中有 tab 补全，使用起来应该不会太难
有些参数不需要填，一下命令 set 参数都不建议填

### 列出点位

`/dmarker list`

### 增加点位

可以通过以下几种方式添加标记:

-   `/dmarker add <marker label> icon:<icon id> set：<markerset id>`
    这必须由登录的玩家执行，并将在玩家的当前位置定义一个标记。如果未提供集合，则将在默认标记集合“标记”中创建标记。如果未定义图标，则使用默认的标记图标（默认为房屋）。(这里建议不填写 set 参数，因为所有现有标记都在默认集合)
-   `/dmarker add id:<marker id> <marker label> icon:<icon id> set:<markerset id>`
    与上述相同，只是指定了标记的唯一 id。(建议使用这个命令，不填写 set 参数，因为所有现有标记都在默认集合)

### 删除点位

`/dmarkder delete id:<marker id>`

### 更改点位

-   `/dmarker update <marker-label> set:<markerset-id> icon:<icon-id> newlabel:<new-label>`
-   `/dmarker update id:<marker-id> set:<markerset-id> icon:<icon-id> newlabel:<new-label>`
    注意：选择不在默认标记集（标记）中的标记需要标记集 id，标记集 id 不可编辑。

### 可用图标列表

![可用图标表](https://mikeprimm.com/images/Markers.png)

更多标记功能请前往[源地址](https://izzelaliz.gitbooks.io/dynmap-wiki/content/Using-markers.html)查看，全为英文。
