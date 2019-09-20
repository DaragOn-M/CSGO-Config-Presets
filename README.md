# [CS:GO] Cfg-Preset-By-Purp1e
>这是我个人写的CSGO config的预设，包含各种应用场景，注释详细

>涉及很多日常使用的指令和功能（服务器指令pass），实时修改更新

>对接触csgo指令不熟悉的人和想方便改变、转移设置等玩家都有很大帮助

### Cfg Preset v1.2b

根据9.20的更新进行若干修改

1.跑图用practice.cfg中添加T键重现最近一次的投掷物（同nadetraining插件）

- 增加实时预测轨迹的指令键位"，" 和预测投掷物轨迹的按键'[' ']' 分别为30/100s（按一次触发一次）
   
- 增加修改半甲/全甲的指令提示等
   
2.修复hlae.cfg中一键高亮的键位提示错误  应为q键  增加若干提示

3.使用说明中增加对各个文件作用的描述

4.添加了2个无聊的小彩蛋

### Cfg Preset v1.2a

适配HLAE新版本特性(1和2必须使用hlae开启CSGO才有效)

1.增加上一回合/下一回合的指令及快捷键"," "."  修改一键高亮击杀快捷键为"q"

2.一键高亮击杀等功能现在在控制台中显示中文提示

3.增加判断是否成功使用hlae打开csgo的指令，成功时显示

```
HLAE启动状态

成功√
```
失败时显示
```
HLAE启动状态：

x
```
### Cfg Preset v1.2

1.新增export.cfg，使用预设之前单独加载该cfg可以显示准星+持枪参数

2.跳投全部调整为双键，现在右键也可以使用跳投

3.丰富了启动项说明

4.新增ffmpeg.cfg和ffmpeg420.cfg，用于搭配hlae录制集锦素材

5.hlae.cfg新增天空贴图skybox相关指令快捷键，预置几个天空贴图指令

6.修复若干说明错误，细节进一步优化

### Cfg Preset v1.1

1.auto.cfg中恢复基础跳投、基础投掷物准星

   【防误触跳投+自动投掷物准星+个性化左右手】相关指令移到"可选指令.txt"

   因为这些功能之间有交集 所以针对不同的情况分别给出了代码

   现在直接复制对应代码 覆盖auto.cfg中对应位置即可

   请根据个人需要自取

2.demo.cfg中现在按p切换demo暂停/继续，取消之前的'['和']'键

3.删除了demo.cfg中和hlae相关的指令

   新增hlae.cfg 包含很多demo、hlae相关指令(一键高亮等)

4.solo.cfg增加solo模式的选择

   控制台输入如aksolo或者按下设定好的按键(7890-=)

   可以设置好出生武器并重新开始游戏

5.solo.cfg中默认100回合

6.新增"可选指令.txt" "使用说明.txt""武器购买代码.txt"

7.其它细节优化

### 使用视频：

#1 AV34054584 前7分钟

#2 AV34789804 (终结篇)

#3 AV45088666 (转移设置脚本)

#4 AV47120170 (v1.0使用说明)

#5 av51220317 (v1.1使用说明)

#### Cfg Preset By Purp1e

链接:https://pan.baidu.com/s/1m91kr2eqH68sYSZgsPP38A

提取码:vh21

### 各文件功能预览

#### 1.auto.cfg

目录  亮度设置  准星设置 鼠标设置

基础设置  持枪视角设置 HUD设置

音量设置  绑定清血迹  解绑按键避免冲突

滚轮跳+中键切换(声音提示)

大跳 基础跳投+投掷物准星

切换左右手  单独绑定投掷物

快速购买武器

使用提示

#### 2.crosshair.cfg

准星修改提示

准星参数

#### 3.crosshair_throw.cfg

投掷物准星参数

#### 4.practice.cfg

开启作弊 各项参数修改

投掷物、弹着点轨迹

金钱、时间修改

全图、任意时间购买

全枪全弹（掉一地枪）

绑定按键（bot操作）(开关轨迹、透视模式等)

使用提示

#### 5.solo.cfg

开启作弊 各项参数修改

可选solo模式 按7890-=键分别切换不同模式

回合开始1s等待

回合结束2s等待

金钱、时间修改等

使用提示

#### 6.demo.cfg

绿色静态准星 集锦专用持枪

暂停demo

绑定按键（暂停继续雷达等）

鼠标前后侧键切换demo播放速度

还原默认HUD设置

使用提示

#### 6.hlae.cfg

hlae相关参数设置

绿色静态准星 集锦专用持枪  还原默认HUD设置

暂停demo   绑定按键（暂停继续雷达等）

鼠标前后侧键切换demo播放速度

一键高亮击杀V2

使用提示

#### 6.export.cfg

显示准星+持枪视角参数

【防误触跳投+自动投掷物准星+个性左右手+快速切换道具】

6种不同需求组合的代码

#### 6.可选指令.txt

网络参数可选指令 双键跳投

【防误触跳投+自动投掷物准星+个性左右手+快速切换道具】

6种不同需求组合的代码
