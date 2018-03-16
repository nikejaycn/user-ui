# Angular BBS开发指南
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fnikejaycn%2Fuser-ui.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fnikejaycn%2Fuser-ui?ref=badge_shield)


## 技术栈

Angular 2

## 环境准备

请先安装NodeJS 5+。

## 启动

进入本目录，运行`npm install`命令。

运行`npm start`命令，启动完成后会在<http://localhost:4200>启动一个开发服务器。

## 工具

运行`npm run g c name-action`可以创建`src/app/name/action.*`文件，内含`NameActionComponent`组件，并自动加入NgModule中。

## 重要！！！投稿指南！

Angular中文社区热烈欢迎各位投稿。延续程序员的光荣传统，我们使用Github接收稿件！

首先，你要会发Pull Request，如果不会用可以参见<http://blog.jobbole.com/76854/>。

然后，请找到`src/app/_shared/api/articles`目录，仿照我已经写的这些文章，把你的文章放进去（用Markdown、Jade、HTML都可以，可以引用图片等），并在index.ts中引用它。

然后，请找到`src/app/_shared/api/authors`目录，把你的个人简介（含靓照）放进去，你就是正式的作者了，用户看到你的名字可以点进去查看详情。

最后，如果你想创建自己的专栏，请找到`src/app/_shared/api/columns`目录，编辑`index.ts`，添加你的专栏简介。当然，专栏是一种荣誉，专栏的文章有质量和数量的要求，如果你创建了专栏，我以后可能会追着你催稿哦，不过这都是小意思，对吧！


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fnikejaycn%2Fuser-ui.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fnikejaycn%2Fuser-ui?ref=badge_large)