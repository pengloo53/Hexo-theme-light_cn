# Hexo-theme-light_cn（Hexo主题）

> 该主题基于hexo默认主题[hexo-theme-light](https://github.com/hexojs/hexo-theme-light)，最初修改为了适用`墙内`用户，后来逐渐形成自己的风格。

[Demo](http://pengloo53.coding.me)

## Release 1.4
折腾了太长时间的主题，而忘了初心，我们是为了去写、去记录、去分享，才搭建的博客。太多的东西都是多余的。
希望进一步精简主题，只保留**写作**该有的东西。

1. 精简代码，免费的永远是最贵的去除多余的服务（大部分的免费的服务已经停止，所以说天下没有免费的午餐，再投入精力找类似免费的服务非常不值得）；
2. 调整部分样式；

## Release 1.3
添加一些功能模块：

1. 集成推荐模块，百度推荐以及wumii推荐供选择
2. 添加多说近期评论
3. 添加日历云插件

![](/img/README/003-2.png)

修改手机界面Header样式：

![](/img/README/003-1.png)


## Release 1.2
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

```yml
menu:
  首页: /
#  文集: /collection
  归档: /archives
  关于我: /resume

submenu:
  订阅: /atom.xml
  留言: /customization


widgets:
- search
- category
- calendar
- recent_comments
- links
- tagcloud
# - tag
# - archive
- weibo

excerpt_link: Read More
comment_link: Comments

# header头像
avatar: /img/default/avatar.png
# header右侧图片展示
ad:

# 百度分享
baidu_share: true

# 请到baidu_tongji.ejs中替换代码
baidu_tongji: true

# enable是否开启；height小挂件高度；url替换成自己的微博挂件地址，同步修改url中height的值
weibo:
  height: 400
  url:

# 评论提供可以选择 duoshuo 或者 wumii，无需评论，此处不填就行。
comment_provider: duoshuo
# 关联推荐提供可以选择baidu_tuijian 或者 wumii, 无需关联推荐，此处不填即可。
relate_provider: baidu_tuijian

# 多说，填写多说short_name
duoshuo_short_name:

# wumii，填写网站域名，例如：http://lupeng.me
wumii_siteprefix:

# 百度推荐，填写百度推荐ID，例如：hm_t_88638
baidu_tuijian_id:

# Calendar
calendar:
  language: zh-CN
  root: calendar
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
