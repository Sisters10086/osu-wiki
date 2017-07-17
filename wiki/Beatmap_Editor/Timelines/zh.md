# 时间轴

在[铺面编辑器](/wiki/beatmap_editor)中，铺面制作者们将会遇到三种不同的时间线。
这篇文章将逐一介绍它们的作用

## 快捷键

_在[快捷键](/wiki/shortcut_key_reference/#general)中可以找到有关时间轴的一系列快捷键。_

## 音乐播放器

![Song's Timeline](/wiki/shared/BE_STL.jpg "Song's Timeline")

在铺面编辑器中的任何一部分都能看见音乐播放器。

以毫秒为单位的时间戳与歌曲进程百分比都在播放器的左侧
如果一个铺面拥有storyboard，这百分比可能会显示“前奏”或“结尾”。

In the centre, it shows the timeline with markings and the compulsory music player buttons.
“Test"按键会保存目前的作图进度，同时会从目前的时间戳来开始试玩。

时间线本身会用些不同的刻度线来表达各种意义

| 颜色 | 描述 |
| ------ | ----------- |
| 亮白长条 | 目前所在时间 |
| 黄色长条| 预览部分 |
| 黄色上半条| 实际游戏部分的开始时间 |
| 绿色上半条 | 有关音效的Timing设定 (参照 [Timing](/wiki/Timing)) |
| 红色上半条| Timing设定 (参照 [Timing](/wiki/Timing)) |
| 蓝色下半条 | 书签 |
| 灰色 (突出部分) | 休息时间 |
| 橙色 (突出部分) | Kiai time（timing切换点？） |



## 游戏物件

根据游戏模式的不同会有共两种不同的物件时间轴。

### osu!, osu!太鼓, 和osu!接水果

![在osu!、osu!太鼓、osu!接水果中的物件时间轴](/wiki/shared/BE_NTL.jpg "这显示了相对于音符时值与时间戳的物件。")

在 [compose（作曲）](/wiki/compose) 模式中，这条时间轴会在 “Compose（作曲）”标签下（除了[osu!mania](wiki/osu!mania)之外）。
	
| Name | 描述 |
| ---- | ----------- |
| `+`/`-` 按钮 |放大 / 缩小时间轴 |
| 白色垂直双线 | 当下于时间轴上所在的位置 |

可以通过鼠标左键来选择物件，拖动鼠标则会移动物件在时间轴中的位置。

可以通过鼠标右键来删除物件。

### osu!mania
	
![osu!mania 游戏界面](/wiki/shared/BEM_PF.jpg "osu!mania 游戏界面")

在osu!mania的作曲模式中，这条时间轴会显示于游戏界面的下方。
	
左方的方框表示铺面的物件密集度。

这被用来当做时间轴。
中间的方框表示游戏区域
游戏区域由线和游戏物件组成。

| 线条颜色 | 描述 |
