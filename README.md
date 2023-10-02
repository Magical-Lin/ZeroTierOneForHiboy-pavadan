ZeroTier - mipsel



项目地址https://github.com/zerotier/ZeroTierOne

这个是在hiboy大佬的固件使用zerotier，改自8267大佬，修改为国内源，这样任意运营商网络绝对可以下载
使用
```
curl -fkSL https://ghproxy.com/https://github.com/Magical-Lin/ZeroTierOneForHiboy-pavadan/releases/download/1.12.2/installzero.sh | sh
nvram set zerotier_id=这里填你的网络id
/etc/storage/zerotier.sh start
```
源帖子https://www.right.com.cn/forum/thread-8274848-1-1.html



后面是测试readme的格式
文本
------
### 普通文本
这是一段普通的文本
### 单行文本
    Hello,大家好，我是果冻虾仁。
在一行开头加入1个Tab或者4个空格。
### 文本块
#### 语法1
在连续几行的文本开头加入1个Tab或者4个空格。

    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

#### 语法2
使用一对各三个的反引号：
```
欢迎到访
我是C++码农
你可以在知乎、CSDN、简书搜索【果冻虾仁】找到我
```
该语法也可以实现代码高亮，见[代码高亮](#代码高亮)
### 文字高亮
文字高亮功能能使行内部分文字高亮，使用一对反引号。
语法：
```
`linux` `网络编程` `socket` `epoll` 
```
效果：`linux` `网络编程` `socket` `epoll`

也适合做一篇文章的tag
