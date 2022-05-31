# AI-research-tools

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/bighuang624/AI-research-tools/blob/master/LICENSE)

> * 推荐一些我喜欢的科研工具（有些限定于 AI 领域）
> * 标记【待尝试】的是我还未使用过但感觉比较有用的工具，会尽快尝试并根据体验决定是否保留
> * 请通过 issues 等方式向我推荐您觉得好用的但不在此清单上的 AI 领域科研工具，感谢

## 目录  <!-- omit in toc -->

- [AI-research-tools](#ai-research-tools)
  - [趋势关注](#趋势关注)
    - [RSS 阅读器](#rss-阅读器)
  - [论文查找](#论文查找)
    - [搜索引擎](#搜索引擎)
    - [arXiv 相关](#arxiv-相关)
    - [代码实现查找](#代码实现查找)
  - [论文阅读](#论文阅读)
    - [查阅下载](#查阅下载)
    - [文献管理](#文献管理)
    - [文献翻译](#文献翻译)
    - [笔记工具](#笔记工具)
  - [编码实验](#编码实验)
    - [Pytorch 相关](#pytorch-相关)
      - [功能配置封装](#功能配置封装)
      - [项目参考](#项目参考)
      - [项目管理](#项目管理)
      - [风格指南](#风格指南)
      - [项目模板](#项目模板)
      - [神经网络分析器](#神经网络分析器)
      - [可视化](#可视化)
    - [实验记录](#实验记录)
    - [数据集查找](#数据集查找)
    - [数据集下载](#数据集下载)
    - [特征工程](#特征工程)
    - [超参搜索](#超参搜索)
    - [Debug 工具](#debug-工具)
  - [论文写作](#论文写作)
    - [LaTeX 模板](#latex-模板)
    - [LaTeX 编辑器](#latex-编辑器)
    - [语言表达](#语言表达)
      - [搭配查找](#搭配查找)
      - [句式推荐](#句式推荐)
      - [写作检查](#写作检查)
    - [公式编辑](#公式编辑)
    - [截屏悬浮](#截屏悬浮)
    - [表格转 LaTeX](#表格转-latex)
    - [模型绘图](#模型绘图)
      - [PPT 插件](#ppt-插件)
      - [图片转换](#图片转换)
  - [会议投递](#会议投递)
    - [会议查找筛选](#会议查找筛选)
    - [匿名链接](#匿名链接)
    - [代码开源](#代码开源)
  - [其他](#其他)
    - [专利检索](#专利检索)
    - [专注工作](#专注工作)
    - [白噪声 / 音乐](#白噪声--音乐)

## 趋势关注

### RSS 阅读器

* [irreader 阅读器 - FATECORE](http://irreader.fatecore.com/)：这是我现在在使用的 RSS 阅读器。一个非常大的优点是，对于一些没有提供 RSS 订阅源的网站，irreader 可以自定义 RSS 订阅源。另外，订阅的 RSS 更新时，有弹窗提醒。还有一个我暂时用不到的功能是，irreader 同时支持订阅播客和播放有声媒体。

## 论文查找

### 搜索引擎

* [Google scholar](https://scholar.google.com/schhp?hl=zh-CN)：搜索论文的首选，可以在这里查看论文统计和引用参考文献，还能通过关注作者或者论文获得新论文更新提醒，以及利用自动化推荐来提供一个基本库。

* [Semantic scholar](https://www.semanticscholar.org/)：可以结合外部材料整合进行论文的语义分析。功能包括：展示引用和参考文献、度量论文影响力、展示论文图表、自动生成关键词（根据标题）、分析作者、在互联网寻找额外资源（例如，相关 youtube 视频），以及推荐论文。

* [dblp: computer science bibliography](https://dblp.org/)：专为 CS 设计的论文查询网站，收录比较顶级并可以被检索到的论文。可以根据会议、期刊等分类查询作者的论文，想搜一个计算机会议的所有文章时好用。

* [中国知网海外服务](https://chn.oversea.cnki.net/index/)：支持全 PDF 格式下载。具体可见 [海外版知网升级了！（全PDF下载），从此告别CAJ阅读器！](https://iseex.github.io//2020-07/CNKI-oversea/)。

### arXiv 相关

* [arXiv](https://arxiv.org/): 论文预印本收录网站。

* [arXiv-sanity](http://arxiv-sanity.com/)：在功能上相比于 arXiv 有很大的改进，包括在浏览中显示摘要、评论和非常基本的社交、推荐、库功能。搜索也更好用。

* [Semantic Sanity: A Personalized Adaptive Feed](https://s2-sanity.apps.allenai.org)：创建自己的个性化 arXiv 选读 Feed。创建每个 Feed 时，会让您先选择几篇论文，然后根据这几篇论文开始推荐，对于推荐结果可以点赞或者不喜欢来帮助调整推荐结果。

* [卖萌屋Arxiv服务](http://arxiv.xixiaoyao.cn/): 只包含 arxiv 当日更新的论文。优点在于把作者机构也展示出来。仍在改进。

* [Paper Digest – AI for tracking and summarizing papers](https://www.paperdigest.org/): 提供邮件订阅前一天出的论文的列表，附有每篇论文的一句话总结。在会议论文公布时，这个网站也会整理。

### 代码实现查找

* [Papers With Code](https://paperswithcode.com/)：自动把论文连接到实现代码的 GitHub 资源库和数据集，并根据 GitHub 的收藏量排序。展示各任务上的 SOTA 以供比较。

* [rasbt/deeplearning-models](https://github.com/rasbt/deeplearning-models)：使用 TensorFlow 和 PyTorch 实现各种深度学习模型的合集。

* [labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations)：很多算法的 PyTorch 实现，带有在线版的注释。缺点是展示的部分不是从头实现，一部分代码放在他们自己的包里了。

## 论文阅读

### 查阅下载

* [SCI-Hub 科研论文全文下载可用网址](http://tool.yovisun.com/scihub/)

### 文献管理

* [Mendeley](https://www.mendeley.com)：支持 web、PC、Mac 和移动手机等多个平台，可以直接注释和高亮显示 PDF，有限额的免费云存储。另外有每周邮件推荐论文。

### 文献翻译

* [CopyTranslator](https://copytranslator.github.io/)：最大的优点在于有置顶、点按复制、监听剪贴板等功能，阅读文献配合使用时可以无缝切换，非常方便。

* [Saladict 沙拉查词](https://saladict.crimx.com/)：浏览器翻译插件，有非常丰富的设置来配合用户的使用习惯。除了官方文档，也可以看 [沙拉查词 + Alfred，打造最佳文献翻译体验！ - 知乎](https://zhuanlan.zhihu.com/p/113809716) 来了解。我还在探索如何在 Windows 系统上实现浏览器外翻译。

### 笔记工具

* 我个人习惯使用[印象笔记](https://www.yinxiang.com/)。

## 编码实验

### Pytorch 相关

#### 功能配置封装

* [williamFalcon/pytorch-lightning](https://github.com/williamFalcon/pytorch-lightning)：将 PyTorch 开发中的各种通用配置（训练验证逻辑、超参搜索、分布式训练等）全部包装起来，以更高级的形式快速搭建模型。功能强大，有些复杂，正在摸索。[机器之心写的简介](https://mp.weixin.qq.com/s/5ueJvt1tcWW0wknpkM3WIg)

#### 项目参考

* [ritchieng/the-incredible-pytorch](https://github.com/ritchieng/the-incredible-pytorch)：有关 PyTorch 的各种教程、项目、视频等资源。

* [microsoft/computervision-recipes](https://github.com/microsoft/computervision-recipes)：微软出品，基于 PyTorch 的各种 CV 任务的教程。

* [donnyyou/torchcv](https://github.com/donnyyou/torchcv)：基于 PyTorch 的 CV 模型框架，包含图像分类、语义分割、目标检测、姿态检测、实例分割、生成对抗网络等任务中的多个常见模型。

#### 项目管理

* [torchtracer](https://oidiotlin.com/torchtracer/)：一个管理 PyTorch AI 实验项目的工具，主要用于保存各类训练数据（模型 checkpoints、超参数组合、日志、loss 变化曲线图像等）。

#### 风格指南

* [IgorSusmelj/pytorch-styleguide](https://github.com/IgorSusmelj/pytorch-styleguide)：一份 PyTorch 的非官方风格指南和最佳实践总结。

#### 项目模板

* [moemen95/Pytorch-Project-Template](https://github.com/moemen95/Pytorch-Project-Template)：一个可扩展的 PyTorch 项目模板，包括图像分割、目标分类、GANs 和强化学习等实例。

* [lyakaap/pytorch-template](https://github.com/lyakaap/pytorch-template)：另一份 PyTorch 项目模板。

#### 神经网络分析器

* [sksq96/pytorch-summary](https://github.com/sksq96/pytorch-summary)：打印 PyTorch 模型信息，包含模型每层的参数量、输出张量大小等。

* [sovrasov/flops-counter.pytorch](https://github.com/sovrasov/flops-counter.pytorch)：计算模型总共的 FLOPs（浮点运算数，理解为计算量，可以用来衡量算法/模型的复杂度）以及每层的占比。缺点是似乎不支持 RNN 相关层，另外打印下来的信息不是很方便看。

<!-- * <del>[Swall0w/torchstat](https://github.com/Swall0w/torchstat)：PyTorch 专用的轻量级神经网络分析器，可以展示网络的参数，空间大小，MAdd，FLOPs 等指标。</del>【支持的层种类过少，只包含卷积网络中常用的那些层】【[有一个 bug 需要修改](https://github.com/Swall0w/torchstat/issues/14)】

* <del>[Tramac/torchscope](https://github.com/Tramac/torchscope)：同样是 PyTorch 专用的神经网络分析器，看起来展示时比上面的 torchstat 更加清晰。</del>【对 Linear 层报错，貌似是 [torchstat 带来的 bug](https://github.com/Swall0w/torchstat/issues/18)】【同样不支持 RNN 相关层】【感觉有时间自己可以 fork 然后修改一下】 -->

#### 可视化

* PyTorch 最新版本已经带有 tensorboard。[官方 tutorial](https://pytorch.org/tutorials/intermediate/tensorboard_tutorial.html)。

* [facebookresearch/visdom](https://github.com/facebookresearch/visdom)：【待尝试】用于创建、组织和共享实时丰富数据可视化的灵活工具。

* [Convolution Visualizer](https://ezyang.github.io/convolution-visualizer/index.html)：如果卷积层配置比较复杂，不方便计算输出大小时，可以利用这个可视化工具辅助。

### 实验记录

* [fastnlp/fitlog](https://github.com/fastnlp/fitlog)：【待尝试】架构无关的实验记录工具，可以看[邱锡鹏老师在知乎写的介绍](https://www.zhihu.com/question/384519338/answer/1181186086)。

### 数据集查找

* [Google Dataset Search](https://toolbox.google.com/datasetsearch)

* [Data Search | Bifrost](https://datasets.bifrost.ai/)：视觉数据集搜索。

### 数据集下载

* 针对在 Google Drive 上下载大型数据集常发生的失败现象，推荐 [wkentaro / gdown](https://github.com/wkentaro/gdown)。

### 特征工程

* [Featuretools](https://github.com/featuretools/featuretools)：【待尝试】自动化特征工程库。

### 超参搜索

* [optuna](https://github.com/optuna/optuna)：自动超参数优化框架。

* [microsoft/nni](https://github.com/microsoft/nni/blob/master/README_zh_CN.md)：【待尝试】用于神经模型搜索和超参数调优的开源自动机器学习（AutoML）的工具包，支持绝大多数主流框架和运行环境。

* [Hyperopt](http://hyperopt.github.io/hyperopt/)：【待尝试】分布式异步超参数优化。看到知乎上有人推荐，不过根据文档来看，目前支持的优化算法只有两种，且不包括贝叶斯优化。

* [BoTorch](https://github.com/pytorch/botorch)：【待尝试】基于 PyTorch 的贝叶斯优化库。

* [automl/Auto-PyTorch](https://github.com/automl/Auto-PyTorch)：【待尝试】基于 PyTorch 的自动结构搜素和超参数搜索。

### Debug 工具

* [cool-RR/PySnooper](https://github.com/cool-RR/pysnooper)：【待尝试】致力让用户抛弃`print`函数来 debug（然而，至少目前我还是习惯用 logging 模块，和`print`差不了多少）。[机器之心写的简介](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650760939&idx=1&sn=5b69c106549f329f83ca241e1bc71ff3&chksm=871aa295b06d2b83deade4fc16f99ed5354572c8838d202d0a229d804bb535815f2315d980d0&scene=0&xtrack=1&key=6854b25c2a023c1b259671991171b31fab8ca8f0b3be42cfe9746f0ac6a97af337c3f692988c69af5813e1658308b6087dc66c1d1f218619aab29c7d02dfc8b005eff42eea7fcb837022e321727f14b5&ascene=1&uin=MjA1ODkwNzIyNw%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=5JdoVuTltfAvWg%2FaBYq40SvnVT0xZhhRK9fPaxA3iu2MgoceoLJpRqamQ9gnBuY2)

## 论文写作

### LaTeX 模板

包括论文、报告、海报等在内的各种 LaTeX 模板。

* [Templates from Overleaf](https://www.overleaf.com/latex/templates)

* [LaTeX Templates](http://www.latextemplates.com/)

### LaTeX 编辑器

* 我个人习惯使用 VSCode 进行离线的 LaTeX 写作，配合 Github 私有库进行版本管理。

* [Overleaf](https://www.overleaf.com/)：支持多人协作的**在线** LaTeX 编辑器。但是对网络连接有一定要求。

### 语言表达

#### 搭配查找

可以看一下这篇文章的推荐：[有了这些网站，英文论文再也不难写了（15个英文论文写作辅助网站介绍和使用技巧） - 知乎](https://zhuanlan.zhihu.com/p/35396232)

* [Linggle](https://linggle.com/)：搜索最常出现的英文词语搭配。不确定自己的表达方式是否正确时使用。

* [Corpus of Contemporary American English (COCA)](https://www.english-corpora.org/coca/)：可以查词汇搭配的**美式**英语语料库，可以查看具体的用了这个词的句子。 [British National Corpus (BYU-BNC)](https://www.english-corpora.org/bnc/)：英式英语的语料库，语料比美式的少一些

* [Thesaurus](https://www.thesaurus.com/)：将低端词汇转换为同义的高端词汇。

* [易搜搭ESODA](http://www.esoda.org/)：清华HCI Lab工作室出品的一款适合国人英语写作的词组搭配查询工具。可切换具体研究方向的论文语料库，展示相关的可替换用法，支持中英混搜。

* [Words and phrases: frequency, genres, collocates, concordances, synonyms, and WordNet](https://www.wordandphrase.info/analyzeText.asp)：用不同颜色区分高中低频词，展现代表文章类型的词汇，并归类出相关可替换的词。虽然说是英文写作措辞辅助工具，感觉最大的用途是学习相关领域论文常用的词汇和搭配。

#### 句式推荐

* [Academic Phrasebank](http://www.phrasebank.manchester.ac.uk/)：学术用语库，告诉你各个章节适合用哪些句式搭配。

#### 写作检查

请注意在线检测工具的泄露风险，谨慎处理关键文字。

* [Grammarly](https://www.grammarly.com/)：语法、句型、标点、选词检测修改，有浏览器插件。

* [Nounplus.net](https://www.nounplus.net/)：免费的在线英文语法检测。

* [LongGang Pang/proofread](https://gitlab.com/snowhitiger/proofread)：【待尝试】对科学文章草稿自动检查，寻找不符合英文科学写作标准的部分，并提出修改意见。作者写的介绍：[分享一个自己做的英文科学写作检查器 - 知乎](https://zhuanlan.zhihu.com/p/62351973)。

### 公式编辑

* [Mathpix](https://mathpix.com/)：通过截取复杂数学方程式的截图将其转换为 LaTeX 代码。可以处理 PDF 的印刷体和照片中的手写公式等。

* [MyScript Webdemo](https://webdemo.myscript.com/)：Math 模块可以将手写公式转为 LaTeX 代码；同时，Diagram 模块可以将手绘的框图转化为工整的框图。

* [Detexify LaTeX handwritten symbol recognition](http://detexify.kirelabs.org/classify.html): 忘记某些字符用 LaTeX 怎么表示时，可以在这个网站上通过手写来查询。

### 截屏悬浮

写论文时经常会遇到需要参考多个文献或代码的情况，同时查看多个文件并频繁切换会非常麻烦。这里是别人推荐的两个能够将截图悬浮置顶的工具，并随时调整位置和大小，方便写作时参考。

* [Snipaste](https://www.snipaste.com/)：【待尝试】有 Windows 和 Mac 版，暂时没有 Linux 版。

* [Snappy](http://snappy-app.com/)：【待尝试】有 Mac 和 iPhone & iPad 版，暂时没有 Windows 版。

### 表格转 LaTeX

* [Excel2LaTeX](https://ctan.org/tex-archive/support/excel2latex)：用在 Excel 上的宏工具，能够将 Excel 表格转换为 LaTeX 代码，节省很多时间。能够满足大多数效果的转换，有些效果可能需要微调。
* [表格生成器](https://www.tablesgenerator.com/)：在线可视化编辑表格，然后生成latex、html、markdown等源码。

### 模型绘图

* PPT 通常是我的第一选择：入手快，种类多，自由度高，支持导出矢量图。

* [Inkscape](https://inkscape.org/) with [latex equation extensions](https://writetex.tk/)：【待尝试】

* [http://Lucidchart.com](https://www.lucidchart.com/)：在线画矢量图，可以导出 png、pdf，也支持各种颜色，组合和图层等。

* [xinychen/academic-drawing](https://github.com/xinychen/academic-drawing)：Matlab/Python 绘图，主要用于画时序数据。

* [xinychen/awesome-latex-drawing](https://github.com/xinychen/awesome-latex-drawing)：LaTeX 绘图，主要用于画贝叶斯网络、张量分解等。

* [HarisIqbal88/PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet)：Python 得到可用于 LaTeX 的图，主要画 CNN。

#### PPT 插件

* [IguanaTex](http://www.jonathanleroux.org/software/iguanatex/)：帮助插入 LaTeX 公式的 PPT 插件。将输入的 LaTeX 代码转换为高质量的 png 图片来插入。

#### 图片转换

提供各种格式的图片的转换服务的网站很多。这里只是简单列举，你也可以通过搜索引擎来找到其他类似的网站。

* [Convert PNG/JPEG (Raster) to EPS/PDF (Vector) Format](http://www.tlhiv.org/rast2vec/)：将 jpg、png 格式的图片文件转换为 eps 文件。

* [EPS到PDF转换器](https://convertio.co/zh/eps-pdf/)：也可以将 eps 文件转换为别的格式的图片。

* [Crop PDF files online - PDF Tools](https://pdfresizer.com/crop)：裁剪 pdf 文件的白边。

* 在命令行中直接将 eps 转换为 pdf：`epstopdf <file.eps>`；自动裁剪 pdf 的白边：`pdfcrop <file.pdf>`。

## 会议投递

### 会议查找筛选

* [ccf-deadlines](https://ccfddl.github.io/)：可以根据研究方向和 CCF 等级来筛选本年度已经确定截稿日期的会议。对国内的同学比较友好。

* [AI Conference Deadlines](https://aideadlin.es/)：可以根据研究方向筛选会议。但是好像需要科学上网才能看到全部信息。

* [Conference List](http://www.conferencelist.info/upcoming.html)：根据截稿时间排序，过期的会议不在首页出现。有一页可以看每个研究方向有哪些会议，但是没有办法根据研究方向筛选还没过期的会议。

* [Conference Partner (会伴)](http://www.myhuiban.com/)：计算机最新国际会议和期刊列表。可以注册以关注会议或期刊。比较全，但目前信息更新不及时。

* [lixin4ever/Conference-Acceptance-Rate](https://github.com/lixin4ever/Conference-Acceptance-Rate)：主要会议近年录取率统计。

### 匿名链接

出于论文盲审考虑，有时候文件（如源码）链接需要是匿名的。有些人会选择在 Github 上创建一个匿名用户，但为每一个会议的每一篇论文都创建一个之后再用不到的用户过于繁琐。我查到有一些工具支持匿名分享文件如下。

* [Dropbox](https://www.dropbox.com/)：应该是最常用的。

* [Open Science Framework](http://help.osf.io/m/links_forks/l/783581-create-a-view-only-link-for-a-registration)

* [Figshare](https://knowledge.figshare.com/articles/item/how-to-share-cite-or-embed-my-data)

### 代码开源

为已发表的论文提供清晰、可复现的代码能够有效推动领域发展。这里推荐一些对开源代码有帮助的工具。

* [ReproducibilityChecklist-v2.0](https://www.cs.mcgill.ca/~jpineau/ReproducibilityChecklist.pdf)：一份机器学习复现清单，列举了你应该提供哪些文件来增强你的论文的可复现性。

* [Damnever/pigar](https://github.com/Damnever/pigar)：Python 项目 requirements 文件自动生成工具。

## 其他

### 专利检索

* [Google Patents](https://iseex.github.io//2020-05/Google-Patents/)：免费检索和下载中英文专利。具体可见 [Google Patents，免费检索和下载中英文专利的最佳工具！](https://iseex.github.io//2020-05/Google-Patents/)。

### 专注工作

* [番茄·人生](http://www.tomatolife.cn/index.html)：Windows PC 端待办事项软件，番茄工作法时钟。

### 白噪声 / 音乐

* [Rainyscope rain simulator](https://rainyscope.com)：下雨声。

* [lofi.cafe - lofi music 🎧](https://www.lofi.cafe/)：随机播放 Lo-Fi 音乐，习惯在工作时听音乐的同学可以尝试一下。需要科学上网。
