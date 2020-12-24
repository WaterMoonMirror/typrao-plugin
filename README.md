# typora-img

#### 介绍
typora 图片上传存储

#### 软件架构
软件架构说明


#### 安装教程

https://blog.csdn.net/tangyb828/article/details/105998084/

#### 使用说明

目前我本地 0.9.77(beta) 版本是可以正常打开偏好设置的，如果存在这个问题，可以尝试通过下面的步奏解决：

可以把备份下来的 window.html 文件恢复回去。
然后手动编辑恢复回去的文件，搜索<script src="./app/window/frame.js" defer="defer"></script> 在其后面加上一行：<script src="./plugins/image/upload.js" defer="defer"></script> 然后再试试是否能恢复正常。
注：readme中覆盖 window.html 只是为了引入 ./plugins/image/upload.js 文件，但不同版本window.html文件可能存在一些差异，确实 有可能出现你说的这个问题。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
