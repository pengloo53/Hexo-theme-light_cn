# Hexo-theme-light_cn（Hexo主题）

> 该主题是基于hexo默认主题[hexo-theme-light](https://github.com/hexojs/hexo-theme-light)的一个china适用版。

[Demo](http://lupeng.me)

##Release 1.2
主要做了下列修改：

1. 整体风格更加简洁，修改多处页面细节，符合响应式设计；
2. 修改文章显示宽度，main-col宽度改成760px（文章一行不宜过长）；
3. 添加了[不蒜子计数器](http://service.ibruce.info/)；
4. 设计个人简历页面，[Demo](http://lupeng.me/resume/)；

![](http://7sbsl6.com1.z0.glb.clouddn.com/Hexo_theme_release_v1.2_1.png)

## Release 1.1
改变了light主题的header样式以及整体着色。开始有别于原light主题的风格。

![](https://cloud.githubusercontent.com/assets/5508125/8259131/d420ff76-16ec-11e5-9f09-d640a49ee2a3.png)

## Release 1.0
![](source/img/README/001.png)

> 主要改造点：

1. 去google服务、去facebook、去addthis等严重影响访问速度的服务，替换成百度分享、多说评论、百度统计等国内服务。
2. 修改code、blockquote样式（不太适合中文）。
3. 调整index布局文件。

> 添加的新功能：

1. Header添加头像，并添加增大动画效果
2. 添加新浪微博widgets
2. 添加归档widgets
3. 添加toTop（回到顶部）功能
4. 添加toc（文章目录）功能
5. 添加个人简历Layout（便于设计自己的页面）
6. 实现多级分类
7. 添加gallery Layout


## 安装

执行下面命令，然后修改`_config.yml`配置文件中`theme`为 `light-ch`.

```
git clone https://github.com/pengloo53/light-ch themes/light-ch
```

## 更新主题

```
cd themes/light-ch
git pull
```

## 配置

默认:

``` yaml
menu:
  首页: /
#  文集: /collection
#  图集: /gallery
  归档: /archives
  分类: /index.html#categories
  关于我: /resume

submenu:
  订阅: /atom.xml
  留言: /customization

widgets:
#- search
- category
- archive
# - tag
- tagcloud
- weibo

excerpt_link: Read More
comment_link: Comments

# header头像
avatar: /assets/img/avatar/avatar.jpg
# header右侧图片展示
ad: /assets/img/avatar/hello.jpg

baidu_share: true

# 请到baidu_tongji.ejs中替换代码
baidu_tongji: true

# enable是否开启；height小挂件高度；url替换成自己的微博挂件地址，同步修改url中height的值
weibo:
  enable: true
  height: 800
  url: Your weibo url

# 评论提供可以选择 duoshuo 或者 wumii，无需评论，此处不填就行。
comment_provider: duoshuo

duoshuo:
  short_name: Your duoshuo

wumii: 
  relateditems: true
  siteprefix: Your site url

```

- `avatar` 头像URL
- `baidu_share` 百度分享
- `weibo` 新浪微博
- `duoshuo` 多说评论
- `wumii` 无觅关联

## Features

### Gallery Post

![](http://i.minus.com/ibp6Hbytwgof9y.jpg)

```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post

![](http://i.minus.com/i7hBbGqh14EWo.png)

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```
