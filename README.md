# Opus 5.5 视觉展示

这份作品集汇集数字绘画、皮影演出、三维游览、互动游戏、粒子艺术、英语精读和教学视频。作品按主题与体验方式整理为六类，共 **17 个作品条目、20 个展示文件**，其中包括 16 个 HTML 网页和 4 个 MP4 视频。

电脑版与手机版归为同一作品的不同入口；《春江花月夜》的网页和视频也放在同一作品下。每个分类目录提供说明，介绍创作主题、实际使用的技术、视觉与交互效果，以及观看方式。

## 分类与技术效果

| 类别 | 作品条目 | 展示文件 | 内容与效果 |
| --- | ---: | ---: | --- |
| [数字水墨与诗意视听](01-ink-and-poetry/README.md) | 5 | 6 | 程序绘画、动态长卷、诗歌场景与音乐播放器，把传统意象转化为可观看、可游览、可创作的体验。 |
| [皮影戏与故事演出](02-shadow-theatre/README.md) | 2 | 2 | 通过皮影角色、戏台光影、剧情时间轴与锣鼓音效，将古典故事组织为可观看、可参与的演出。 |
| [三维场景与互动游戏](03-3d-scenes-and-games/README.md) | 3 | 5 | 程序化三维场景结合行走、骑行、镜头、天气与任务，让观众通过探索理解空间和文化内容。 |
| [粒子生成艺术](04-particle-art/README.md) | 1 | 1 | 数学形态、粒子运动与合成声音共同构成不断变换的动态视觉作品。 |
| [英语文学精读与学习工具](05-english-reading/README.md) | 3 | 3 | 将逐段原文、英文朗读、中文讲解、词句注释和闪卡复习组织为完整的阅读学习流程。 |
| [动态教学与知识短片](06-educational-films/README.md) | 3 | 3 | 通过配色图解、概念映射、叙事场景与字幕，把抽象知识组织为可直接播放的教学短片。 |

## 下载与观看

GitHub 文件链接用于查看与下载源文件，HTML 文件不会在仓库文件页直接运行。点击仓库的 **Code → Download ZIP**，解压后在浏览器中打开相应 HTML；MP4 可直接交给播放器。

大部分网页把绘画逻辑、核心库或音频放在单个文件中，不需要安装项目依赖。含外部字体的页面可能联网加载字体；《武松打虎》在线加载 Three.js，运行需要网络和支持 WebGL 的浏览器。三维作品也需要浏览器支持 WebGL，系统语音的可用性取决于浏览器与操作系统。

若本地文件打开时受到模块加载限制，可在已安装 Python 的电脑上进入解压目录并运行：

```sh
python -m http.server 8000
```

然后访问 `http://localhost:8000/` 并选择作品目录。播放网页声音通常需要先点击开始或播放；骑行和长卷作品建议横屏观看。学习记录和游戏成绩只保存在当前浏览器本机。

## 全部文件

### 数字水墨与诗意视听

- [水墨小品.html](01-ink-and-poetry/%E6%B0%B4%E5%A2%A8%E5%B0%8F%E5%93%81.html)
- [千里江山·活卷.html](01-ink-and-poetry/%E5%8D%83%E9%87%8C%E6%B1%9F%E5%B1%B1%C2%B7%E6%B4%BB%E5%8D%B7.html)
- [汴京一日.html](01-ink-and-poetry/%E6%B1%B4%E4%BA%AC%E4%B8%80%E6%97%A5.html)
- [春江花月夜.html](01-ink-and-poetry/%E6%98%A5%E6%B1%9F%E8%8A%B1%E6%9C%88%E5%A4%9C.html)
- [春江花月夜_720p.mp4](01-ink-and-poetry/%E6%98%A5%E6%B1%9F%E8%8A%B1%E6%9C%88%E5%A4%9C_720p.mp4)
- [所剩沾衣_2.html](01-ink-and-poetry/%E6%89%80%E5%89%A9%E6%B2%BE%E8%A1%A3_2.html)
### 皮影戏与故事演出

- [武松打虎.html](02-shadow-theatre/%E6%AD%A6%E6%9D%BE%E6%89%93%E8%99%8E.html)
- [孙悟空借芭蕉扇.html](02-shadow-theatre/%E5%AD%99%E6%82%9F%E7%A9%BA%E5%80%9F%E8%8A%AD%E8%95%89%E6%89%87.html)
### 三维场景与互动游戏

- [五色博物馆.html](03-3d-scenes-and-games/%E4%BA%94%E8%89%B2%E5%8D%9A%E7%89%A9%E9%A6%86.html)
- [鹈鹕骑行_越秀公园_电脑版_1.html](03-3d-scenes-and-games/%E9%B9%88%E9%B9%95%E9%AA%91%E8%A1%8C_%E8%B6%8A%E7%A7%80%E5%85%AC%E5%9B%AD_%E7%94%B5%E8%84%91%E7%89%88_1.html)
- [鹈鹕骑行_越秀公园_手机版.html](03-3d-scenes-and-games/%E9%B9%88%E9%B9%95%E9%AA%91%E8%A1%8C_%E8%B6%8A%E7%A7%80%E5%85%AC%E5%9B%AD_%E6%89%8B%E6%9C%BA%E7%89%88.html)
- [鹈鹕游越秀_游戏版_电脑版.html](03-3d-scenes-and-games/%E9%B9%88%E9%B9%95%E6%B8%B8%E8%B6%8A%E7%A7%80_%E6%B8%B8%E6%88%8F%E7%89%88_%E7%94%B5%E8%84%91%E7%89%88.html)
- [鹈鹕游越秀_游戏版_手机版.html](03-3d-scenes-and-games/%E9%B9%88%E9%B9%95%E6%B8%B8%E8%B6%8A%E7%A7%80_%E6%B8%B8%E6%88%8F%E7%89%88_%E6%89%8B%E6%9C%BA%E7%89%88.html)
### 粒子生成艺术

- [粒子宇宙.html](04-particle-art/%E7%B2%92%E5%AD%90%E5%AE%87%E5%AE%99.html)
### 英语文学精读与学习工具

- [散文阅读.html](05-english-reading/%E6%95%A3%E6%96%87%E9%98%85%E8%AF%BB.html)
- [瓦尔登湖.html](05-english-reading/%E7%93%A6%E5%B0%94%E7%99%BB%E6%B9%96.html)
- [Here_Is_New_York_full.html](05-english-reading/Here_Is_New_York_full.html)
### 动态教学与知识短片

- [让AI画得更好看_文生图中的色彩搭配.mp4](06-educational-films/%E8%AE%A9AI%E7%94%BB%E5%BE%97%E6%9B%B4%E5%A5%BD%E7%9C%8B_%E6%96%87%E7%94%9F%E5%9B%BE%E4%B8%AD%E7%9A%84%E8%89%B2%E5%BD%A9%E6%90%AD%E9%85%8D.mp4)
- [METAPHOR-The-Worlds-We-Think-Inside.mp4](06-educational-films/METAPHOR-The-Worlds-We-Think-Inside.mp4)
- [STORYTELLING-From-Homer-to-Steve-Jobs.mp4](06-educational-films/STORYTELLING-From-Homer-to-Steve-Jobs.mp4)

## 整理说明

保留原有作品文件名及页面内署名。“Opus 5.5 视觉展示”沿用作品集文件夹名称；具体技术说明依据网页实现与成片内容，不将目录名称作为所有文件的模型来源证明。

`瓦尔登湖.html` 实际是 E. B. White 的 *A Slight Sound at Evening* 精读页，内容为《瓦尔登湖》出版百年纪念文；`散文阅读.html` 对应 *Some Remarks on Humor*。

上传副本中的《汴京一日》在开头补充了 UTF-8 字符集声明，以避免中文乱码，其余 19 个展示文件保留原始字节。文件清单、大小和 SHA-256 校验值见 [作品清单](manifest.json)。

原始作品中的署名与来源说明予以保留，第三方库与字体沿用各自许可。本仓库未为全部内容另行指定统一开源许可。
