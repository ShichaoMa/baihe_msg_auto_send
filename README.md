# 百合网自动向其它会员发送消息的程序


## INSTALL
## windows
 ```
 需要安装PIL
 # ubuntu 安装pil
 # 安装pil
 sudo pip install pillow
 # 如果报错了，则首先执行
 sudo apt-get install  libjpeg8-dev zlib1g-dev    libfreetype6-dev liblcms2-dev libwebp-dev tcl8.5-dev tk8.5-dev python-tk
 # ubuntu 安装 imagemagick
 sudo  apt-get install imagemagick

作者：夏洛之枫
链接：https://zhuanlan.zhihu.com/p/23986959
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
 ubuntu用户还需要安装image magick
 linux环境下还未测试，可能有bug
 git clone https://github.com/ShichaoMa/baihe_msg_auto_send.git
 ```

## START
 ```
 python send_msg.py
 ```
## WORKFLOW
- 输入你要发送的信息，可以输入多条，按回车继续，若要中止输入，留空即可
- 输入百合网账号
- 输入百合网密码
- 输入验证码（未多次登陆的情况下不需要输验证码）
- 若输错验证码马上会要求重输
- 开始登陆
- 若用户名密码输错，会提示重输
- 开始发送消息，程序会根据默认搜索条件（一般是你的择偶要求）查询妹纸，随机从你设置好的消息中选择一条依次发送，自动翻页，直到全网站符合条件的妹纸全都收到你的信息。
- 为了不给网站增加压力发送间隔设置为一秒钟。

作者：夏洛之枫

知乎专栏：[单身狗终极福利！！！使用爬虫模拟相亲网站客户端用来群发消息](https://zhuanlan.zhihu.com/p/23986959)

