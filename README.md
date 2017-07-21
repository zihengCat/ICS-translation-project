# ICS-translation-project

*ICS-CMU* 公开课翻译字幕制作计划。

# 说明

**-213: Introduction to Computer Systems(ICS)** 是最好的计算机导论课程之一，**目前此课程并不提供英/中字幕。**
我们希望为这门优秀的计算机导论课制作英/中字幕，帮助更多同学学习、入门计算机的世界。

# 翻译源

我们采用的翻译视频源是： *Intro to Computer Systems, Fall, 2015.*

## 课程主页

- [CMU课程主页](http://www.cs.cmu.edu/~./213/index.html)

## 转载源

- [YouTube](https://www.youtube.com/playlist?list=PLbY-cFJNzq7z_tQGq-rxtq_n2QQDf5vnM)

- [Bilibili](https://www.bilibili.com/video/av10774914/)

# 翻译进度

## 翻译状态

- *[finished]* 翻译已完成

- *[translating]* 翻译制作中

- *[waiting]* 翻译等待接手

## 课程列表

- lesson-01: Overview *[waiting]*
- lesson-02: Bits ints Part1 *[waiting]*
- lesson-03: Bits ints Part2 *[waiting]*
- lesson-04: Floating Point *[waiting]*
- lesson-05: Machine Level Programming I Basics *[waiting]*
- lesson-06: Machine Level Programming II Control *[waiting]*
- lesson-07: Machine Level Programming III Procedures *[waiting]*
- lesson-08: Machine Level Programming IV Data *[waiting]*
- lesson-09: Machine Level Programming V Advanced Topics *[waiting]*
- lesson-10: Program Optimization *[waiting]*
- lesson-11: The Memory Hierarchy *[waiting]*
- lesson-12: Cache Memories *[waiting]*
- lesson-13: Linking *[waiting]*
- lesson-14: ECF  Exceptions & Processes *[waiting]*
- lesson-15: ECF  Signals and Nonlocal Jumps *[waiting]*
- lesson-16: System Level I O *[waiting]*
- lesson-17: Virtual Memory  Concepts *[waiting]*
- lesson-18: Virtual Memory  Systems *[waiting]*
- lesson-19: Dynamic Memory Allocation  Basic Concepts *[waiting]*
- lesson-20: Dynamic Memory Allocation  Advanced Concepts *[waiting]*
- lesson-21: Network Programmin Part 1 *[waiting]*
- lesson-22: Network Programming Part II *[waiting]*
- lesson-23: Concurrent Programming *[waiting]*
- lesson-24: Synchronization  Basics *[waiting]*
- lesson-25: Synchronization  Advanced *[waiting]*
- lesson-26: Thread Level Parallelism *[waiting]*
- lesson-27: Future of Computing *[waiting]*
 
# 翻译须知

## 翻译流程

请使用 GitHub 进行大部分的翻译工作。

- *fork/clone* 下载到本地
- *pull request* 合并翻译文本
- *issue* 反映问题

请先在**课程列表**处打好标签，再进行翻译/校对：
```
- 课程号: 课程名 [翻译状态] [翻译人/审校人]
```
注意添加**翻译状态**、**翻译人/审校人**标签。

## 目录结构

```
auto-srt/lesson-[01-27]/<en.srt/ch.srt>
translated-srt/lesson-[01-27]/<en.srt/ch.srt>
README.md
```
- `auto-srt`下存放**YouTube自动生成字幕**。
- `translated-srt`下存放**翻译/校对后字幕**。

## 字幕格式

英/中字幕均采用`SRT`格式。SRT（Subripper）是最简单的文本字幕格式，扩展名为.srt，其组成为：一行字幕序号，一行时间代码，一行字幕数据。

```
45
00:02:52,184 --> 00:02:53,617
慢慢来
```
这表示：第45个字幕，显示时间从该视频开始的第2分52.184秒到第2分53.617秒，内容为：慢慢来。

> 摘自维基百科

## 推荐工具

`SRT`为纯文本字幕格式，任何**文本编辑器**都可以轻松编辑。

# 版权相关

[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)

