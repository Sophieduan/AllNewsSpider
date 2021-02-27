# intro

新浪新闻，腾讯新闻，搜狐新闻，澎湃新闻。

短期目前旨在爬取所有新闻门户网站的新闻，每个门户网站爬虫开箱即用，并自动保存到同目录下的 csv/excel 文件中，禁止将所得数据商用。

长期目标是打造一个信息流聚合平台，或者进行更高层面的比如社会舆情、新闻地理可视化等的处理。

**项目长期维护，欢迎 star，项目更多信息欢迎关注个人微信公众号 【月小水长】**



# how to use

每个文件夹下的代码就是对应平台的新闻爬虫

py 文件直接运行

pyd 文件需要，假设为 pengpai_news_spider.pyd

1. 将 pyd 文件下载到本地，新建项目，把 pyd 文件放进去

2. 项目根目录下新建 runner.py，写入以下代码即可运行并抓取

   ```python
   import pengpai_news_spider
   pengpai_news_spider.main()
   ```

   

# todo

1、百度新闻爬虫，已完成，已发布

2、澎拜新闻爬虫，已完成，已发布

3、腾讯新闻爬虫，已完成，已发布

4、新浪新闻爬虫，已完成，未发布

5、头条新闻爬虫，未完成，未发布