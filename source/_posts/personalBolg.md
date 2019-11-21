---
title: 如何搭建自己的博客
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## 如何搭建自己的个人博客

### 系统信息

``` bash
Win 10系统
```
参考：[5分钟搭建免费个人博客](https://www.jianshu.com/p/4eaddcbe4d12)

### 准备

``` bash
GitHub账号: 账号名username，创建仓库username.github.io，注意仓库名的username和账号名的username保持一致
安装Hexo
```
[Hexo](https://hexo.io/zh-cn/docs/index.html)

### 配置


``` bash
1、创建博客：
     在本地终端（cmd）输入
	$ hexo init user.github.io
2、更改配置
    主题安装
    随便找一个喜欢的主题，然后Git到本地：
	$ cd username.github.io
	$ git clone https://github.com/miccall/hexo-theme-Mic_Theme.git themes/next
```

[更多主题](https://hexo.io/themes/)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
