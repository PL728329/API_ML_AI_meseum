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

## （十）API使用（使用水平）
#### 1. 百度开放平台-语音识别api
- 描述：将60秒以内的语音精准识别为文字，可适用于手机语音输入、智能语音交互、语音指令、语音搜索等短语音交互场景
- API文档：[语音识别API文档](https://ai.baidu.com/ai-doc/SPEECH/Ek39uxgre)
- 语音识别api测试代码：[测试代码](http://nfunm069.gitee.io/baidu_speech_recognition)
---
#### 2. 百度地图开放平台-普通IP定位api
- 描述：普通IP定位是一套以HTTP/HTTPS形式提供的轻量级定位接口，用户可以通过该服务，根据IP定位来获取大致位置。
- 请求URL：
  1. http://api.map.baidu.com/location/ip //HTTP协议
  2. https://api.map.baidu.com/location/ip //HTTPS协议
- API文档：[普通IP定位API文档](http://lbs.baidu.com/index.php?title=webapi/ip-api)
- 输入：
![输入代码](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%AF%95%E4%B8%9A-%E7%99%BE%E5%BA%A6.png)
- 输出：
![输出结果](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%AF%95%E4%B8%9A-%E7%99%BE%E5%BA%A6%E7%BB%93%E6%9E%9C.png)
---
#### 3. 高德地图开放平台-IP定位api
- 描述：IP定位是一个简单的HTTP接口，根据用户输入的IP地址，能够快速的帮用户定位IP的所在位置。
- 请求URL：https://restapi.amap.com/v3/ip?parameters
- 请求方式：GET
- API文档：[IP定位API文档](https://lbs.amap.com/api/webservice/guide/api/ipconfig/)
- 输入输出：
![输入代码](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%AF%95%E4%B8%9A-%E9%AB%98%E5%BE%B7.png)

---
#### 4. 百度AI开放平台-文字识别-二维码识别api
- 描述：对图片中的二维码、条形码进行检测和识别，返回存储的文字信息。
- 请求URL：https://aip.baidubce.com/rest/2.0/ocr/v1/qrcode
- 请求方法：POST
- API文档：[二维码识别API文档](https://ai.baidu.com/tech/ocr_others/qrcode)
##### 二维码识别
- 输入：
![输入代码](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E4%BA%8C%E7%BB%B4%E7%A0%81-%E8%BE%93%E5%85%A5.png)
- 输出：
![输出结果](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E4%BA%8C%E7%BB%B4%E7%A0%81-%E8%BE%93%E5%87%BA.png)
##### 条形码识别
- 输入：
![输入代码](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%9D%A1%E5%BD%A2%E7%A0%81-%E8%BE%93%E5%85%A5.png)
- 输出：
![输出结果](https://github.com/PL728329/API_ML_AI_meseum/blob/master/images/%E6%9D%A1%E5%BD%A2%E7%A0%81-%E8%BE%93%E5%87%BA.png)
---

## （十一）API使用比较分析
- 百度开放平台-语音识别api：
  1. 判断语句所需时间较长，流畅度不够；
  2. 可调用的次数较多；
  3. 语音识别标准版：可按天/月/年购买次数及提升QPS；
  4. 语音识别极速版：按调用量计费；
  5. [价格文档](https://ai.baidu.com/ai-doc/SPEECH/ck38lxnx8)

- 百度地图开放平台-普通IP定位api：
  1. 每天有免费的配额及并发量次数。若超出用量，则需单独联系客服提升配额与并发量上限；
  2. 一般用户配额上限为0.1万次/天（1000次/天），并发量：1QPS（最高并发量为10QPS）；
  3. 可以确定大致位置，一般为城市中心点。位置信息包括经纬度、省、市等信息；
  4. 普通IP目前不支持海外场景；
  5. [价格文档](http://lbsyun.baidu.com/apiconsole/auth/privilege)


- 高德地图开放平台-IP定位api：
  1. 针对基础服务api有每日免费调用量的限制；
  2. API调用文档清晰，相对同类API来说更容易上手；
  3. 针对中小型企业使用需求推出流量包（30元/万次），可以按需购买；
  4. 针对大型企业使用需求推出流量包月（60000元/月），不限流量，使用无忧；
  5. [价格文档](https://lbs.amap.com/home/package?active=quota)

- 百度AI开放平台-文字识别-二维码识别api：
  1. 支持二维码识别/条形码识别；
  2. 一次性赠送1000次免费调用量，付费模式分为三种：购买次数包、开通按量后付费以及定制版；
  3. [价格文档](https://ai.baidu.com/ai-doc/OCR/xk3h7xvih#%E4%BA%8C%E7%BB%B4%E7%A0%81%E8%AF%86%E5%88%AB)
---
## （十二）人工智能概率性
- 语音识别可能会出现的问题：
  1. 环境杂音或嗓音可能会导致语音识别精确度下降；
  2. 语种问题，语音识别可能没有办法辨别所有语种；
- 解决办法：
  1. 加强机器自身的深度学习；
  2. [声纹识别+语音识别，解决人机交互痛点](https://blog.csdn.net/VoiceSense/article/details/102978870)


## （十三）API使用风险评估
- 语音识别错误率：
  1.  在最近公布的一项研究中，谷歌的最新说话人分类系统（speaker diarization system）将多人语音分类识别的错误率从 20% 降到了 2%，获得了十倍的性能提升。
   原文：[是谁在说话？谷歌多人语音识别新系统错误率降至2%](https://www.jiqizhixin.com/articles/2019-08-17-4)
  2. 微软语音和对话研究团队负责人黄学东宣布微软语音识别系统错误率进一步降低到5.1%，此次突破堪称是语音识别行业新的里程碑，准确率超过专业速记员。
   原文：[语音识别技术里程碑：错误率降至5.1%，超过专业速记员](https://www.msra.cn/zh-cn/news/features/new-conversational-speech-recognition-milestone-20170822)

- 错误现象处理办法：
  1.语音识别错误时，可以使用比较幽默诙谐的语气提示用户。第一次：“人家没听清楚你说什么噢！可不可以再说一遍啦~”，第二次：“人家可能还没学到这里！点击此处可以转接客服小姐姐直接帮到您噢！”
