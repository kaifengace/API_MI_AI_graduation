# :rainbow: 项目名称：智能毕业纪念APP 

> PRD 价值主张设计（目标：多层次多长度版本）
> 1. 一句话版本<br>
    此款 **有你** 智能毕业纪念APP 通过调用 **百度人脸识别API** 与 **高德地图API** ，可以识别照片中的人脸，并显示出相应信息，帮助用户回忆，毕业相册的地图API可以显示周边有无校友，方便用户的社交联系。
> 2. 一分钟60s版本 (图文线上可阅读含可查连结)<br>
    此款 **有你** 智能毕业纪念APP 通过调用 **百度人脸识别API** 与 **高德地图API** ，整合实现智能毕业纪念册，其中百度人脸识别API可以识别照片中的人脸，并显示出相应信息，帮助用户回忆同学的信息，高德地图API可以显示周边有无校友，方便用户的社交联系，让毕业后的我们不再为不记得同学的姓名等信息而感到尴尬的问题，毕业相册的VR功能可以让用户重温大学时光，在身临其境中找回自己逝去的青春，让过去的校园生活不再成为过去。


## :sparkles: Product Documentation（产品说明文档）

|  Title   |   Content  |
| --- | --- |
| Target release    |  2019/11   |
|  Epic   |  有你   |
|  Document status   |  进行中   |
|  Document owner   |  胡凯锋   |
|  Designer   |  胡凯锋   |
|  Developer   |  胡凯锋   |
|  QA   |   胡凯锋  |

- 版本修订记录

|修订版本号|迭代日期|修订内容|迭代者|
|---------|-------|--------|-----|
|v1.0|2019.11.20|文档初稿撰写，建立基本产品文档框架|胡凯锋|
|v1.1|2019.11.25|撰写产品文档|胡凯锋|
|v2.0|2019.11|绘制产品流程图，结构图|胡凯锋|


- 文档输出环境

|文档名称|版本号|体验环境|撰写时间|撰写人|
|---------|-------|--------|-----|----|
|有你智能APP|v3.1|Andrio10|2019.11.28|胡凯锋|



## :rainbow: Catalogue（目录）
- [Part1 PRD价值主张设计](#价值主张设计)
    - [PRD1加值宣言](#加值宣言)
    - [PRD2核心价值](#核心价值)
    - [PRD3用户痛点](#用户痛点)
    - [PRD4人工智能概率性与用户痛点](#人工智能概率性与用户痛点)
    - [PRD5需求列表与人工智能API加值](#需求列表与人工智能API加值)
- [Part2 原型](#原型)
    - [交互及界面设计](#交互及界面设计)
    - [信息设计](#信息设计)
    - [原型文档](#原型文档)
- [Part3 API产品使用关键AI或机器学习之API的输出入展示](#API产品使用关键AI或机器学习之API的输出入展示)
    - [API使用水平](#使用水平)
    - [API使用比较分析](#使用比较分析)
    - [API使用后风险报告](#使用后风险报告)
    - [API加分项](#加分项)


### :sparkles: 产品定位
“有你”是针对大学毕业生的智能相册APP，给毕业生提供一个回忆大学生活和社交的移动端平台。

### :sparkles: 背景
大学4年是人生的一个重要阶段，这段经历是人们的宝贵财富，在这里我们遇见的人和做过的事都会给我们带来重要影响，但很多人在毕业以后就各奔东西，杳无音信，连同学的姓名和长相都忘记了，仿佛彻底告别了过去，这何尝不是一种遗憾。同时，校友是优质的潜在人脉资源，可以适当加以利用。

### :sparkles: 目标

- 回忆：通过百度人脸识别api，识别照片中的人脸，并显示出相应信息，帮助用户回忆。
- 寻回：通过高德地图api，显示同地区或相邻城市的校友，点击可显示个人信息，可申请加为好友，方便毕业后联系。
 - 再现：通过VR技术，结合其他外部VR设备，重回母校，再现毕业情景，让用户身临其境。



## :star2: 价值主张设计

### :star: 加值宣言

毕业相册可通过人脸识别api可以实现线上相册的功能，无需每人购买实体通讯录相册，可以识别照片中的人，方便用户随时回忆。
- （主要）毕业相册的地图api可以显示周边有无校友，方便用户的社交联系，开拓人脉资源。
- （辅助）毕业相册的VR功能可以让用户重温大学时光，在身临其境中找回自己逝去的青春。


### :star: 核心价值
最小可行性产品是可以通过识别图片人物返回人物信息和通过地图显示显示附近校友的毕业相册app。

## :star: 用户痛点
- 实体相册容量有限且不易保存和携带。
- 缺少同学的联系方式，不方便联系，导致毕业后逐渐失联。
- 忘记同学的名字或者其他相关信息。


### :star: 人工智能概率性与用户痛点
- 人脸识别的准确度与图片清晰度、人脸大小、是否正脸等有关。
- 人脸质量信息：返回人脸各部分的遮挡、光照、模糊、完整度、置信度等信息。
- 检测响应速度，与图片中人脸数量相关，人脸数量较多时响应时间会有些许延长。
- 质量检测

    ![质量检测](https://gitee.com/hukaif/graduation_album_app/raw/master/t1.PNG)
    
### :star: 需求列表与人工智能API加值

##### :fire: 需求列表

|  主题   |  用户案例   |  重要性   |  备注   |  api加值   |
| --- | --- | --- | --- | --- |
|  遗忘与回忆   |  用户A忘记了同学的姓名，不太记得同学的长相，想通过相册辅助回忆  |  核心功能   |  对人脸识别api的精确度要求高   |  百度人脸识别api   |
|  联系与合作   |  用户B想了解身边有没有自己的校友，可以约见面交流，同时拓宽人脉   |  次核心功能   |  信息云储存   |  高德地图api   |
|  重温大学生活   |  用户C想看看母校大学，通过VR重现大学校园   |  附加功能   |  非必要，难度大，技术不成熟   |  VR   |



### :star: 使用到的API
- 百度API人脸识别
    - [人脸检测](https://ai.baidu.com/docs#/Face-Detect-V3/top)
    - [人脸搜索](https://ai.baidu.com/docs#/Face-Search-V3/top)

- 高德地图API
    - [静态地图](https://lbs.amap.com/api/webservice/guide/api/staticmaps)

## :star2: 原型
#### :snail: 一、产品架构
![产品架构](https://github.com/kaifengace/graduation_album_app/raw/master/%E6%AF%95%E4%B8%9A%E6%9E%B6%E6%9E%84.PNG)

#### :snail: 二、产品流程
![产品流程](https://github.com/kaifengace/graduation_album_app/raw/master/%E6%AF%95%E4%B8%9A%E6%B5%81%E7%A8%8B.PNG)


