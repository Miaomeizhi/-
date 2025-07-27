<div align   对齐="center"   “中心”>
<h1>OpenWrt — 云编译</h1>


## 项目说明
- 固件默认管理地址：**`192.168.2.1`** 默认用户：**`root   根`** 默认密码：**`none   没有一个`**
- 源码来源：[breeze303](https://github.com/LiBwrt-op/openwrt-6.x) [VIKINGYFY](https://github.com/VIKINGYFY/immortalwrt)
- 云编译来源：[haiibo](https://github.com/haiibo/OpenWrt) [视频教程](https://www.youtube.com/watch?v=6j4ofS0GT38&t=507s)

## 定制固件
1. 首先要登录 Gihub 账号，然后 Fork 此项目到你自己的 Github 仓库
2. 修改 `configs   配置` 目录对应文件添加或删除插件，或者上传自己的 `xx.config` 配置文件，General.config为插件文件
3. 插件对应名称及功能请参考恩山网友帖子：[OpenWrt软件包全量解释](https://www.right.com.cn/FORUM/forum.php?mod=viewthread&tid=8384897)
4. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `Roc-script.sh` 文件内修改
5. 添加或修改 `xx.yml` 文件，最后点击 `Actions   行动` 运行要编译的 `workflow   工作流` 即可开始编译
6. 编译大概需要1-2小时，编译完成后在仓库主页 [Releases   释放](https://github.com/laipeng668/openwrt-ci-roc/releases) 对应 Tag 标签内下载固件
