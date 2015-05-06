# light-ch

基于主题hexo默认主题[hexo-theme-light](https://github.com/hexojs/hexo-theme-light)

> 基于hexo默认主题Light的国内版，所谓国内版就是去google服务、去facebook、去addthis等严重影响访问速度的服务，替换成百度分享、多说评论等国内服务。

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
