# spider_JinanBGworksInfo
爬取“前程无忧”网站中搜索济南的大数据相关岗位
conDB.py        该文件内为操作数据库类  注：该类内的数据库信息需该成自己的
work_spider.py  该文件作用为爬取数据并保存到json文件和插入到数据库  注：sql语句中的表名需要改为自己的
注：数据库表结构为
name    | varchar(40)
company | varchar(40)
city    | varchar(40) 
salary  | varchar(40)
date    | varchar(20) 