# MHGU Replay Recorder · 任务回放与自由镜头

**幼刀CDD** · [下载 / Download](https://github.com/CDD0321/MHGU-Replay-Recorder/releases/latest)

自动记录单人猎人任务。打完一局，可以在游戏里把时间拖回命中的瞬间，暂停，移动镜头，从另一个角度再看一次。

**实测环境**　Windows · MHGU Recomp 0.17.7 · MHGU 1.4.0 · Forge 1.5.1。插件界面和包内说明为中文。

## 第一次使用

1. 在下载页的 **Assets** 任选一个 ZIP。**10fps 轻量版**适合节省空间，**30fps 加强版**每秒记录更多姿态，适合回看快速动作。两版共用插件路径。
2. 关闭游戏，把 ZIP 内的 `MHGU_Replay_Probe` 文件夹解压到 `mhgurecomp.exe` 旁的 `mods` 文件夹。进游戏按 **Insert** 打开 Forge，检查插件标题。
3. 单人猎人任务加载后自动开始记录。在**关闭游戏前**打开 Forge，在「最近任务（保留两局）」点击「导出」。导出的 `.mhgudemo` 位于当前存档目录。
4. 进入与录像**同编号**的单人任务，在 Forge 的「已导出 Demo」选择文件，点击「播放所选 Demo」。建议使用录制时的装备与外观。自动换区未完成时，可按浮窗提示手动进区。

## 回放快捷键

先按 **Insert** 收起 Forge 主菜单。手柄键名按 Switch 布局。

| 操作 | 手柄 | 键盘 |
| --- | --- | --- |
| 暂停 / 继续 | A | 空格 |
| 前后跳 5 秒 / 调整倍速 | 十字键左右 / 上下 | 可用浮窗时间轴 |
| 切换自由镜头 | Y | C |
| 平移 / 转向 / 升降 | 左摇杆 / 右摇杆 / L、R | WASD / IJKL / Q、E |
| 加速移动 / 临时广角 | 按住 ZL / ZR | Shift 加速 |
| 显隐游戏 HUD / 回放浮窗 | L3 / R3 | F6 显隐浮窗 |

## 范围与反馈

本版面向单人猎人任务。多人、猎猫模式和猫车演出在支持范围之外。单个录像须小于 4 GiB，建议用录制时的版本回放。怪物特殊阶段、跨区特效、场景破坏、部分狩技及随从技能仍待更多实战对照。

遇到差异时，请在 [Issues](https://github.com/CDD0321/MHGU-Replay-Recorder/issues) 留下 **10fps 或 30fps、任务、区域、回放时间点、实战与回放的区别**。如方便，可附对应的 demo 或截图。

## English quick start

Record and replay single-player Hunter quests in MHGU Recomp with a free camera. Download **one** build under Assets. The 10 Hz build uses less disk space, while the 30 Hz build captures more poses per second. With the game closed, extract the `MHGU_Replay_Probe` folder into `mods` next to `mhgurecomp.exe`. Quests record automatically. Press **Insert** to open Forge and export a hunt before quitting; the session keeps the last two hunts. To replay it, enter the same quest and select the exported demo in Forge. The interface and packaged manual are in Chinese.
