# 掌上博物馆PRD文档
## （一）背景

- 随着时代的发展，社会的进步，大部分人的物质生活基本上得到了满足，精神生活也开始丰富了起来。去听讲座、看画展、逛博物馆，这些从前我们很少做的事情，现在的我们已经可以去亲自体验，用自己的感官去了解更多对我们精神层面有帮助、有启发的事物。

- 但是，一般人的需求可能就到这里基本上已经被满足，但也会有人对这些地方可能会有额外的要求。针对这些相对较为特殊的人群，我们是否也能最大程度的保证其能正常有便捷的去体验这些活动呢？

## （二）加值宣言

- 主要：将会使用文本翻译、语音翻译等API，让用户可以自己设定使用语音/文本导播方式查看博物馆的介绍，为博物馆app加值。一来既可以满足大众的基本需求，二来也能考虑到特殊人群的需求（视力障碍/听力障碍等）。
- 次要：将会使用室内地图API以及普通IP定位API，设置博物馆地图并提供导航。一来可以方便特殊人群省时省力游览博物馆，二来该功能可以收集到用户的走动路线，能更好的帮助馆长以及管理员规划场馆内部的各类设计与布置。

## （三）核心价值（最小可行性产品）

- 提供文本/语音的游览导播方式供用户挑选，并提供室内地图、室内导航服务给用户。

## （四）目的

- 做你的博物馆小助手———掌上博物馆app

## （五）目标
- 前期目标：
  1. 提供语音/文本搜索功能，并给予相对应的反馈（语音输入-语音输出、文本输入-文本输出），方便在听/写领域不便、认为文本枯燥的多动人群更好的游览博物馆。
  2. 提供二维码识别功能，用户扫二维码即可了解展品信息。
  3. 提供室内地图及定位功能，让身障人群更方便游览博物馆。

- 后期目标（现在不实施）：
  1. 添加社交功能，来博物馆的人可以互相交流。

## （六）用户
- 普通游客、多动儿、身障者

## （七）用户痛点
- 场景一：游客觉得导播员在身边不自在，想轻松简便独自看展，又想了解一些基本的藏品信息怎么办？
- 场景二：游客身体上有缺陷，相对普通游客而言看展相对麻烦，如何提升该类游客的游览体验感？
- 场景三：游客想快速知道某展馆位于何处，并且想了解目前自己身处何处怎么办？

## （八）用户需求（使用的人工智能要反映到需求列表中）

| 用户案例 | 对应功能 | 重要程度 |
:---:|:---:|:---:|
| 用户想独自看展但又可以随时提问，提供游览趣味度 | 语音识别功能-语音搜索 | 重要 |
| 用户想快捷了解展品信息 | 文字识别功能-二维码识别 | 重要 |
| 用户想了解当前所在位置 | 普通IP定位功能 | 次重要 |
| 用户想查看馆内地图 | 普通IP定位功能 | 次重要 |

# 原型
## （九）使用者交互与设计（axure产品原型）
- [原型文档展示](https://pl728329.github.io/museum_axure/#g=1&p=%E4%BA%A7%E5%93%81%E7%BB%93%E6%9E%84%E5%9B%BE)
- [原型文档下载区](https://github.com/PL728329/museum_axure)

- **登录页面**
![登录页面](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png)

- **掌上博物页面**
![掌上博物页面](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%8E%8C%E4%B8%8A%E5%8D%9A%E7%89%A9%E9%A1%B5%E9%9D%A2-%E4%B8%BB%E9%A1%B5%E9%9D%A2.png)

- **个人模块页面**
![个人模块页面](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E4%B8%AA%E4%BA%BA%E6%A8%A1%E5%9D%97%E9%A1%B5%E9%9D%A2.png)

- **导览地图页面**
![导览地图页面](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E5%AF%BC%E8%A7%88%E5%9C%B0%E5%9B%BE%E9%A1%B5%E9%9D%A2.png)

- **产品结构图**

![产品结构图](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%8E%8C%E4%B8%8A%E5%8D%9A%E7%89%A9%E9%A6%86-%E4%BA%A7%E5%93%81%E7%BB%93%E6%9E%84%E5%9B%BE.png)

- **功能结构图**

![功能结构图](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%8E%8C%E4%B8%8A%E5%8D%9A%E7%89%A9%E9%A6%86-%E5%8A%9F%E8%83%BD%E7%BB%93%E6%9E%84%E5%9B%BE.png)

- **信息结构图**

![信息结构图](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%8E%8C%E4%B8%8A%E5%8D%9A%E7%89%A9%E9%A6%86-%E4%BF%A1%E6%81%AF%E7%BB%93%E6%9E%84%E5%9B%BE.png)

- **产品流程图**

![产品流程图](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E4%BA%A7%E5%93%81%E6%B5%81%E7%A8%8B%E5%9B%BE.png)
