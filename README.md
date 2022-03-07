# 简介

## 什么东东
### 功能
神之手是一个能够加载xposed模块的框架,和经典xposed框架不同的是本框架不需要Root即可运行，使用比较简单
支持5.0以及以上android版本。
### 原理
通过神之手改造手机上已经安装的或者本地app,使其植入钩子框架代码，从而使其在被改造的app在启动之时自动加载钩子。程序内置动态加载功能，在启动后将加载遵循xposed api规范 的插件从而执行插件代码。





# 开始使用


如果你需要通过神之手使用 [hookui](https://hookui.lozn.top) 模块，按以下步骤操作即可：

1. 点击首页右下角的浮动按钮，然后在弹出菜单中点击 **超度已安装应用**。
2. 在选择应用界面中选择你需要进行逆向分析的APP ，比如QQ。
3. 选中之后 如果**弹出**需要允许安装未知应用,则找到神之手应用**设置允许安装**
4. 在超度应用界面 默认引擎**引擎1**,签名方式为**完美**,资源封包方式为**应用内**

*可以根据情况选择**动态加载神之手引擎**(此方法能够更好的隐藏xposed)*

5. 创建完成之后，会提示你需要**卸载QQ**，卸载即可(你的所有应用数据将会消失)。
6. 最后一步一步退出返回首页
7. 点击左上角菜单图标,切换已安装模块,确保**HOOKUI**设置已勾选激活
8. 点击左上角已被超度的应用，查看是否显示**QQ**如果一切不出意外的话，你将能看到加载内核和伪装引擎，以及原签名信息数据。
*温馨提示：hookui中也需要同时设置勾选**QQ***
9.最后**打开QQ**，这时候 Xposed 模块应该已经正常工作了,可以在右下角看到一个hookui的专属图标（无需重启系统）。
**如果不生效，可以再次强制停止你需要使用的 APP，如QQ**




# 下载升级
由于作者本人不搭建服务器,因此不会上传到本网站以及博客网站中,常见的更新地址如下：
qq群， telegram(需要翻墙)
godhand 就是神之手的意思，别进了群都不知道怎么下载哈!
*不可使用本软件进行诈骗从事违法行为等行为，仅供学习使用！触发法律后果自负！本人不承担任何责任，软件使用的时候协议上也一再强调禁止用于违法用途！切记切记*

群主非本人
[qq群 748171411](https://jq.qq.com/?_wv=1027&k=voeyhUxG)


qq 35068264的qq空间可以翻找说说，我有时会会把加群图片放在QQ空间

电报 : https://t.me/qssq666


## 联系我






qq:35068264

email:qssq521@gmail.com

电报 : https://t.me/qssq666



![qq35068264](pic/wechat.png)

![qq35068264](pic/qq.png)


# 注意事项

由于本操作会修改app,因此可能会遇到签名检测等问题。 如果框架本身的检测不足以使app运行，用户可以自行编写插件增加防检测功能,
另外使用第三方登录会遇到无法登录的问题,开发者可以自行编写xposed解决，通过同时把请求登录的app和第三方登录app使其签名变成正确的签名
# 打赏赞助

 alipay:qssq521@gmail.com
 
 qq:35068264
 

# 常见问题
## 生成失败

1. 签名失败可以查看日志来分析原因，如果是签名失败，可以找到输出目录自行使用其它软件进行v2签名。
2. 内存不足OOM?额，这个手机上需要优化下，比较大的app我需要调整一下。。
3. 其它问题可以复制错误发到群里，本人一般不会更新处理问题,我自己有自己的职业规划，我并不认为解决你的问题，对我技术上或者某些能力上有什么提升，做这个只是为了兴趣


## 安装闪退
你可以尝试一下方法
1. 切换引擎
2. 切换为动态加载
3. 更换手机
4. 更换app版本
6. 升级神之手
如果依然无法解决,抱歉，我也是不会帮你解决这种问题的。
如果你有能力你完全可以写一个xposed插件写一个暂停啥的调试啥的自行解决此等问题。
如果你不会编程，你也可以借助我的另外一个框架 [HOOKUI](https://hookui.lozn.top) 来进行幸运破解


## 插件不生效

尝试让神之手运行,给足app和神之手所需要的一些权限


