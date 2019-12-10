# 期末项目

趣闻APP设计

梗概：我主要设计是一款综合类的社交信息平台，现在的很多平台例如微博等他们的新闻推荐模块都是比较综合的，许多都是根据热度来推送给用户，而我这个社交平台通过针对用户在APP点击浏览的内容来进行分类，如某个用户在一天内浏览的几乎都是娱乐类的新闻 动态，那么我们的APP会通过推荐系统主要推送给用户娱乐新闻动态；这个是使用了百度AI开放平台中的“文章分类”。然后根据用户浏览文章的出现的核心关键词分析，将相似文章聚合、文本内容分析等提取文章的核心关键词，结合用户画像，精准的对用户进行个性化推荐。比如追星女孩喜欢某一位明星，他会主要是关注该明星的新闻，这时我们可以个性化推荐给用户。这使用了百度AI开放平台中的“文章标签”。同时我们的APP是用户可以自行发布信息，动态等，这时可能会存在一些违禁的词语或者比较敏感的动态，这时我们使用了百度AI开放平台中“文本审核”功能将用户发布动态前进行审核。



### 加值宣言：
目前许多的社交信息平台都是没有完全针对用户进行精准地一对一输送的，如微博，主要是推送热门事件，热门的新闻等，可能有些用户对某种事件根本就不感兴趣，那么平台的阅读量可能会随之减少，那么基于这个现状，现在设计的APP采用了百度的“文章分类”API和“文章标签”API对现状进行改善，在这个APP里，可以根据用户点击的文章进行分析，分析其核心关键词，更加精准地为用户推送动态于文章，同时用户可以在APP上发布自己的生活动态等，这也会根据用户发送的内容关键词进行分析，将其动态推送给拥有相关关键词的用户，可增加用户之间的联系与互动。


### 核心价值（最小可行性产品）：
根据用户的核心需求，精准地推送文章/新闻/动态给用户，使用户在浏览搜寻文章时更加方便快捷，减少不必要的繁琐的步骤。


### 背景
目前的社交信息类APP 推送的内容都是较为综合的，有政治的，娱乐的，经济的等等各方面的内容，而用户的所希望关注的内容可能只是里面的一小部分，如有的人喜欢追星，他们浏览文章可能多着重于娱乐方面，有的人从事财经类职业，他可能更关注经济方面的内容（其他方面可能也会关注，但着重应该是经济类）。而现在的新闻资讯通常是“推荐模块”各类综合类的资讯杂糅在一起推送，几乎没有会根据用户的核心需求进行推送。如果有一个社交的APP能根据用户的核心需求进行推送，这可能更能增加用户粘度。


### 目的
让你用最少的步骤，看你最想看的内容----趣闻APP

### 目标用户
1. 追星女孩----他们追求自己喜欢的明星，都会希望每天能看到与自己爱豆相关的动态
2. 学习类的用户--比如某用户的用户画像及常浏览的文章多为学习化妆类的，那么平台会为他主要推送关于化妆类的干货。
3. 喜欢交友的用户---我们会根据用户的发布动态的核心关键来将用户进行匹配推荐，增强用户的联系


### 用户痛点
场景一：追星女孩会想通过各种渠道来寻找自己爱豆的照片及相关的动态
场景二：希望学习/了解某种干货类的用户，但不知道从哪里能找到相关的信息。
场景三：一些比较内向，不善于在人前表达自己的用户，如果网上找到相似的兴趣爱好网友可能会促进其交流。

### 用户需求

用户希望能更方便的查看自己感兴趣的内容  ---  文章分类API和文章标签API


希望能有一个良好友善的网络环境---文本审核API




















