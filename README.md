# Antiquity

一个有点古风的Hexo主题，来自一个不会设计不会配色的前端渣渣。
- [预览](https://yiluyanxia.site)

## 安装

### 安装

``` bash
$ git clone https://github.com/yiluyanxia/hexo-theme-antiquity.git
```

### 使用
将根目录中的config.yml文件中的theme修改为antiquity

### 更新

``` bash
cd themes/antiquity
git pull
```
## 配置
``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: 阅读全文
fancybox: true

# Sidebar
sidebar: left
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Background
# background_image: /images/bg.jpeg
background_title: 图片来自网络

# favicon
favicon: /images/default-avatar.webp

#Userinfo
author: 一路烟霞
slogan: 特别耐撕的小前端，资深的打酱油攻城狮。
# avatar: /images/code-title.png
avatar_title: 图片来自网络

# Article code panel: cloud doorframe mac
highlightPanel: cloud

#Gitment
gitment:
  owner: 
  repo: 
  client_id: 
  client_secret: 

# Miscellaneous
google_analytics:
gauges_analytics:
google_site_verification: 
baidu_site_verification: 


# 友情链接
blogroll:
  一路眼瞎: https://yiluyanxia.github.io/
```
- **menu** -导航菜单
- **rss** - RSS 链接
- **excerpt_link** - 文章尾部阅读全文链接所显示的文字.设置为‘false’则隐藏。
- **fancybox** - 启用 [Fancybox]
- **sidebar** - 侧边栏位置，可以选填 ‘left’, ’right‘ or ’false‘。
- **widgets** - 侧边栏显示的小部件
- **background_image** - 背景图，设置路径即可。
- **background_title** - 鼠标经过背景图所出现的文字。
- **highlightPanel** - 代码框样式，可选值为 cloud doorframe mac
- **gitment** - gitment的配置

- **google_analytics** - Google Analytics ID
- **favicon** - 网站图标路径
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## 特性

### Fancybox
使用Fancybox展示图片。
```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```
