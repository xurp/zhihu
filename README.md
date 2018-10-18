# ZhiHu
SpringBoot2.0+SpringMVC+Mybatis 仿写知乎问答的网站
## 实现的功能：
登陆注册，增删改查，提问，评论，敏感词过滤，站内信，点赞，新鲜事，邮件通知，solr搜索等<br>
  1. 框架：SpringBoot + Mybatis<br>
  2. 存储：数据库使用MySQL<br>
  3. 缓存：Redis<br>
  4. 模板引擎：freemarker<br>
  5. 搜索引擎：solr<br>
## 技术：
  1. 基于redis的缓存 <br>
  2. 基于前缀树的敏感词过滤 <br>
  3. 异步框架的设计，底层使用的是Redis的异步队列，使用异步队列实现站内信，点赞，邮件等功能 <br>
  4. solr结合IKAnalyzer自定义中文分词，实现搜索引擎 <br>
  5. timeline推拉模式结合的时间轴，渲染新鲜事，实现内容的推送<br>
  ## 技术实现的详细参考
  1. [在SpringBoot实现基于Token的用户身份验证](https://blog.csdn.net/WilsonSong1024/article/details/80452072)<br>
  2. [基于前缀树图文详解敏感词过滤](https://blog.csdn.net/WilsonSong1024/article/details/80487550)<br>
  3. [ 基于Redis实现的异步消息队列](https://blog.csdn.net/WilsonSong1024/article/details/80573611)<br>
  4. [SpringBoot2.0实现邮件发送](https://blog.csdn.net/WilsonSong1024/article/details/80769460)<br>
  5. [SpringBoot中搭建全文检索引擎Solr使用详解](https://blog.csdn.net/WilsonSong1024/article/details/81164004)<br>
  6. [SpringBoot下基于Junit的单元测试](https://blog.csdn.net/WilsonSong1024/article/details/81216268)
