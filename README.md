# TencentComicBook
## 腾讯漫画批量抓取


#### 安装依赖

`pip install -r requirements.txt`


#### 使用帮助
```
onepiece.py --help
Usage: onepiece.py [OPTIONS] [MODE]...

  根据腾讯漫画id下载图片

  添加 all/a 关键字即可下载所有章节

  例如 python3 onepiece.py -id 50430 all

Options:
  -id, --id INTEGER      请输入你想要下载的漫画的id,默认下载海贼王
                         如海贼王http://ac.qq.com/Comic/ComicInfo/id/505430
                         python3 onepiece.py -id 50430
  -i, --interval TEXT    下载多个章节,输入章节区间,如 -i 1-10,25,30-40
  -c, --chapter INTEGER  输入要下载的章节chapter，默认下载最新章节
                         如倒数第二 -c -2
  -t, --thread INTEGER   线程池数,默认开启8个线程池,下载多个章节时效果才明显
  --help                 Show this message and exit.
'''