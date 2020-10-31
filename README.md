# -
前端吧 
爬取网页的配置
win10系统
在这个网站上根据教程先把wget安装完成
https://blog.csdn.net/qq_31163325/article/details/84344774

然后键盘 win + r
输入

wget -m -U “Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 5.1; GTB5)” -r -k -nc -P 输入你要保存的目录 和 文件夹名称 需要下载的地址

下面是参照例子：
wget -m -U “Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 5.1; GTB5)” -r -k -nc -P D:\xxx https://www.xxx.com

下载后的文件夹，是层层包裹的，需要你一进去，里面就会出现你下载好的网页
