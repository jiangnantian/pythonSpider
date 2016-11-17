# pythonSpider
some python spiders with BeautifulSoup & requests

##BS4

### [github](bs4/github)
- 爬取关注或粉丝列表 [followXXXList.py](bs4/github/github_followXXXList.py)
- 爬取用户个人信息 [userInfo.py](bs4/github/github_userInfo.py)

### [58同城](bs4/58tongcheng)
- 获取所有的二级菜单列表 [urlLists.py](bs4/58tongcheng/tc_urlLists.py)
- 获取每一个url下的具体信息 [itemInfo.py](bs4/58tongcheng/tc_itemInfo.py)

### [豆瓣](bs4/douban)
- 获取单个电影的短评 [comment.py](bs4/douban/douban_comment.py)
- 获取单个电影的所有大图海报 [photosR.py](bs4/douban/douban_photosR.py)

### [知乎](bs4/zhihu)
- 获取单个问题下面的回答所有图片，并存在以问题的名字命名的文件夹中 [quesImg.py](bs4/zhihu/zhihu_quesImg.py) 例子：[问题：你收藏的最美的萝莉图片是怎样的](bs4/zhihu/你收藏的最美的萝莉图片是怎样的？)
- 获取知乎用户的个人信息 [userInfo.py](bs4/zhihu/zhihu_userInfo.py)

### [股票交易数据](bs4/stock)
- 获取该支股票的指定年度指定季度的数据并写入csv [stock2csv.py](bs4/stock/stock2csv.py)
- 获取该支股票的所有交易数据并写入txt [stock2txt.py](bs4/stock/stock2txt.py)
- 获取该支股票的所有交易数据并写入以其股票代码命名的csv中 [stock2csvALL.py](bs4/stock/stock2csvALL.py)
- 获取该支股票的所有交易数据并写入以其股票代码和名字命名的csv中 [stock2csvALLWithName.py](bs4/stock/stock2csvALLWithName.py)

##scarpy

### [wiki](scarpy/wikiSpider)
