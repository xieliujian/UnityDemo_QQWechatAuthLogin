# UnityDemo_QQWechatAuthLogin

****

### Author : Xieliujian
### E-mail : 377624289@qq.com

****

<h2 id="Demo6">QQWechatAuthLogin的Demo展示使用ShareSDK进行QQ和Wechat登录</h2>

* a, 效果图如下:
![效果图](https://github.com/xieliujian/UnityDemo_QQWechatAuthLogin/tree/master/Snapshot/QQWechatAuthLogin/QQ20171021-153400%402x.png)

* b, QQ Wechat在Android集成注意

主要的实现代码里已经提供，注意的如下图所示

![效果图](https://github.com/xieliujian/UnityDemo_QQWechatAuthLogin/tree/master/Snapshot/QQWechatAuthLogin/QQ20171021-201447%402x.png)

需要提供一个和包名一样的jar包，不然微信登录不能成功, 这个jar包可以参考Demo.jar包自己写，或者联系shareSdk客服

* c, QQ WeChat在iOS集成注意

![效果图](https://github.com/xieliujian/UnityDemo_QQWechatAuthLogin/tree/master/Snapshot/QQWechatAuthLogin/QQ20171021-201531%402x.png)

如图所示，QQ需要填写3个 qq, qzone qqseries(关键是这个，ios上可能就读这个)

wechat需要填写2个 wechat wechatseries(关键是这个, ios上可能就读这个)

![效果图](https://github.com/xieliujian/UnityDemo_QQWechatAuthLogin/tree/master/Snapshot/QQWechatAuthLogin/QQ20171021-201912%402x.png)

导出包的后处理时候，需要写入plist字段，需要填写正确的 url schemes