# 我的个人博客

访问地址：[5t0ne](httpps://dszqbsm.github.io)

## 站点搭建记录

### 4.18

搭建参考：[GitHub Pages + Hexo搭建个人博客网站，史上最全教程](https://blog.csdn.net/yaorongke/article/details/119089190)、[Hexo Fluid 用户手册](https://hexo.fluid-dev.com/docs/)

1. 初步搭建，阅读数、评论区还没设置（LeanCloud注册收不到验证码）

2. 站点风格有待优化

3. 考虑购买域名映射站点

### 4.24

1. 注册了LeanCloud，设置了单篇文章阅读量计数

2. 页面底部展示网站的 PV、UV 统计数

3. 添加评论功能

## 站点使用笔记

1. 在hexo-blog目录下执行`hexo new post 文章名`即可创建一篇新文章，在`source/_posts`目录下修改`.md`文章具体内容，图片保存在`source/img`目录下

2. 根目录下的`_config.yml`文件是站点配置文件，`_config.fluid.yml`文件是主题配置文件

3. 本仓库保存的是`hexo-log/public`目录下的所有文件，即修改站点配置、主题配置、新建文章等修改操作后，执行`hexo g -d`命令会自动将修改同步到`hexo-log/public`目录，并推送到GitHub仓库中