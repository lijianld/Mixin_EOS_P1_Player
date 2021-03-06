>**注：** 本文基于[李林](https://gist.github.com/myrual)的[开发者接入Mixin Network说明](https://gist.github.com/myrual/64769acd3d09e9fd3ac37636d899f844) ，特此感谢！！！

# 1. 开发者自己创建一个mixin 账户

[https://mixin.one](https://mixin.one)

如果要更详细的指导请看 **官印** 的这篇文章：[MIXIN下载指南](https://www.jianshu.com/p/65b12a44ad53)

# 2.开发者使用注册的mixin账户创建App

## 2.1 访问 https://developers.mixin.one/dashboard ， 使用Mixin App的摄像头扫描二维码登陆。

![mixin_interface](http://static.zybuluo.com/hitchhacker/294v071s3nz8enj371zcotyg/mixin_interface.jpeg)

## 2.2 填写注册App需要的信息。

- **（1）app的名字，2-64个字符：**

![app_name](http://static.zybuluo.com/hitchhacker/rqmjrzgesvaq7dpmfbd7kvfs/app_name.png)

- **（2）app小程序的地址：**

![app_home_uri](http://static.zybuluo.com/hitchhacker/u68q9v1qbaqgcge97rl3mlcm/app_home_uri.png)

home_uri在机器人中的入口是在这里：

![app_home_uri_interface1](http://static.zybuluo.com/hitchhacker/egucec7ij8mir9rjw0m2ilcq/home_uri_interface.jpeg)

弹出来的这个地址就是home_uri页面中的内容：

![home_uri_interface2](http://static.zybuluo.com/hitchhacker/fso25zcp7xgu1meeyx40bxht/home_uri_interface2.jpeg)


- **（3）授权后跳转的地址：**

![oauth_path](http://static.zybuluo.com/hitchhacker/tfhp4roq7ah5su44fyw97lzm/oath_path.png)

引导用户扫描你app的二维码后，跳转到的地址就是这个。可以设置为你的服务器「ip:端口」，例如你设置oauth path为「http://11.11.11.11:3355」 ，则客户在扫码后即会跳转到 http://11.11.11.11:3355/?code=[返回的code] 这个地址。

- **（4）然后输入一个简短的app介绍**

- **（5）再搞个图标**

- **（6）点击Submit，Okay！你的第一个MiXin App就注册好了！**
