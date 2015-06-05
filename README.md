# light-ch（Hexo主题）

> 该主题是基于hexo默认主题[hexo-theme-light](https://github.com/hexojs/hexo-theme-light)的一个国内适用版。

改造点：

1. 去google服务、去facebook、去addthis等严重影响访问速度的服务，替换成百度分享、多说评论、百度统计等国内服务。
2. 修改code、blockquote样式（不太适合中文）。
3. 调整index布局文件。

添加的新功能：

1. Header添加头像
2. 添加新浪微博Sidebar
2. 添加归档Sidebar
3. 添加toTop（回到顶部）功能
4. 添加toc（文章目录）功能
5. 添加个人简历Layout`(待完成)`


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
  归档: /archives

widgets:
- search
- category
- tag
- tagcloud

excerpt_link: Read More

baidu_share: true

rss:

duoshuo:
  enable: true
  short_name: pengloo53

wumii: 
  enable: true
  siteprefix: http://www.linux2me.com
```

- `baidu_share` 百度分享
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

### Tweet Widget

![](http://i.minus.com/iMC8EyF9y0Y3y.PNG)

### Fancybox

![](http://i.minus.com/iHv7h7rZNqHvo.PNG)

[Hexo]: http://zespia.tw/hexo/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
