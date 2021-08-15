# Vue.js+Node.js 开发实战

#

## redis store the json data type into the key

```
SET book:nav_menu '[{"name": "主页","src": "http://loaclhost"},{"name": "文章","src": "/article/list"}]'
```

SET book:footer '{"footer":[{"name": "版权所有: ","src": "http://loaclhost","text": "Stiller"}, {"name": "发送邮件","src": "mailto:uneedzf@gmail.com","text": "Gmail"}]}'

SET book:links '[{"name" : "baidu","src": "http://baidu.com"}]'

SET book:indexPic '[{"title": "baidu", "src": "http://baidu.com", "img": "http://xxxxx.com/xxx. jpg"}]'

## redis 命令行查看中文不乱码

```
redis-cli  --raw
```

[redis 命令行查看中文不乱码](https://blog.csdn.net/chwshuang/article/details/55258004)

## redis 如何查看所有的 key

```
redis> keys *
```

[redis 如何查看所有的 key](https://blog.csdn.net/lanyang123456/article/details/80717250)

## TypeError: Router.use() requires middleware function but got a Object

```
module.exports = router ;
```

[TypeError: Router.use() requires middleware function but got a Object](https://stackoverflow.com/questions/27465850/typeerror-router-use-requires-middleware-function-but-got-a-object/50007721)

## Redis DEL 命令

```
redis 127.0.0.1:6379> DEL KEY_NAME
```

[Redis DEL 命令](https://www.runoob.com/redis/keys-del.html)

## Reference:

[Vue.js+Node.js 开发实战：从入门到项目上线前言](https://weread.qq.com/web/reader/c7432440721c7eb2c74881fkecc32f3013eccbc87e4b62e)

## How to disable ESLint in vue-cli?

```
npm remove @vue/cli-plugin-eslint
```

[How to disable ESLint in vue-cli?](https://stackoverflow.com/questions/38757069/how-to-disable-eslint-in-vue-cli)

## TinyMCE

[TinyMCE](https://www.npmjs.com/package/tinymce)  
[TinyMCE support for Vue 3](https://www.tiny.cloud/blog/tinymce-vue-3-support/)

## babel.config.js

[Vue Cli 3 已经开始使用 babel.config.js，而不是.babelrc #211](https://github.com/vueComponent/ant-design-vue/issues/211)  
[babel-plugin-import](https://www.npmjs.com/package/babel-plugin-import)  
[babel 到底该如何配置？](https://segmentfault.com/a/1190000011665642)

## Footer Centerning

[How TO - Center Elements Vertically](https://www.w3schools.com/howto/howto_css_center-vertical.asp)  
[CENTERING THINGS](https://www.w3.org/Style/Examples/007/center.en.html)

## Deployment

[Previewing Locally](https://cli.vuejs.org/guide/deployment.html#general-guidelines)

## Nginx run vue project

You can simply remove all the html file in the nginx folder, then place the dist content inside of it

```
brew services start nginx
open /usr/local/Cellar/nginx

```

[【YaconIT】Vue 项目部署到 Nginx 服务器](https://www.bilibili.com/video/BV1R741117ds/)  
[nginx 上部署前端项目](https://www.cnblogs.com/songmengyao/p/12298754.html)  
[手把手教 Nginx 部署 Vue 项目](https://juejin.cn/post/6844904096973979662)
[Mac Nginx 部署 vue 项目](https://www.jianshu.com/p/093bba6ec8ef)  
[[vue]：vue 前端和 node 后端、通过 nginx 的服务器配置](https://mp.weixin.qq.com/s/Uuv6RLopAmps7y6dg_9v9g)

## Nginx

[Installing Nginx in Mac OS X Maverick With Homebrew](https://medium.com/@ThomasTan/installing-nginx-in-mac-os-x-maverick-with-homebrew-d8867b7e8a5a)  
[Installing NGINX on MAC](https://dev.to/arjavdave/installing-nginx-on-mac-46ac)
