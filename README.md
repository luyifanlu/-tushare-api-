# 基于tushare数据api接口

#### 介绍
基于tushare行情数据预测，股票涨势

这是一个基于2018沪深300 的2010.6-2020.6 基础行情数据（tushare数据，完全免费），训练的深度学习模型。（模型需要下载数据，下载方法在附件中）
可以很好观测股票涨势。回测的话最好在2020.6后，否则有过拟合。api接口只做模型预测，股票池选择完全由用户决定，这样可以防止推股荐股---坐庄嫌疑。一般只做预测，结果不是太好，优化方法我在notebook介绍一种。为了保证预测速度，我把股票池大小限制在300以下---有需要更大股票池可以私聊。
模型作用
1，可以作为散户监测自己喜欢的股票池
2，可以监测某个行业，或者某个指数
3，通关一定优化，可以作为量化策略。例如再做一个基于财务
数据模型，通过两者共同筛选，排名靠前的股票。


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
