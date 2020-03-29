#疫情在家闲来无事，修改了这么一个小程序，供大家使用。
该程序修改自https://github.com/mariosemes/PornHub-downloader-python
他这个程序使用了youtube-dl，能下载各种列表，但是在我的使用过程中，只能下载playlist前36项。
然后我自己重新写了一下下载播放列表的功能。
使用方法
1.
python3 pornhubdown.py
会新建数据库，并且要求一个存储路径。
2.
python3 pornhubdown.py add https://www.pornhub.com/playlist/122392431
类似这样的网址，请确保是网址是www开头的playlist页面。
3。
python3 pornhubdown.py getlist
会对加入数据库并没有写入vkey数据的playlist进行操作，将获取的playlist写入数据库
4.
python3 pornhubdown.py start
开始下载视频，会读取数据库中所有没下载过得vkey进行下载
