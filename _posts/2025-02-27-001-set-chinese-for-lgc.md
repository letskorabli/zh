---
title: "游戏启动器（Lesta Game Center）汉化"
date: 2025-02-27
permalink: /set-chinese-for-lgc/
---

## 介绍

Lesta Games**不提供**Lesta Game Center（以下简称为LGC）中文语言，因此我们需要手动修改LGC的相关文件。

[澪刻](https://gitee.com/localized-korabli)提供了可用的中文汉化包。

## 安装

[视频教程](https://www.bilibili.com/video/BV1WhcxerEBk)

步骤：

1. 访问[蓝奏云分享页面](https://tapio.lanzn.com/b0nyr0hkh)并下载最新的LGC汉化包。

2. 根据图1、图2的指示，查看LGC的版本并打开其安装目录。
    
    P1
    ![Picture 1](/../zh/assets/set-chinese-for-lgc/1.png)

    P2
    ![Picture 2](/../zh/assets/set-chinese-for-lgc/2.png)

3. 检查LGC的版本是否与汉化包文件名中的版本相吻合。如果不吻合，请尝试升级LGC，或访问蓝奏云分享页面下载更新版本的LGC汉化包。

4. 退出LGC。

5. 备份LGC安装目录中的**dlls**文件夹。

6. 将LGC汉化包中的**dlls**文件夹解压到LGC安装目录，确保**lgc_res.dat**被替换。

7. 启动LGC。

8. 根据图3的指示，将语言切换为中文。

    P3
    ![Picture 3](/../zh/assets/set-chinese-for-lgc/3.png)

9. 一切就绪！请注意：硬编码文本和新闻文本无法通过本地文件翻译，将仍然为俄语。

    ![Showcase](/../zh/assets/set-chinese-for-lgc/showcase.png)

## Q&A

- Q：为什么汉化失效了？

  A：Lesta Game Center更新了lgc_res.dat文件，请重新安装汉化。
  
- Q：为什么部分文本没有汉化？

  A：Lesta Game Center更新后，可能需要一段时间来整理新文本并发布新汉化，请您密切关注发布页。
