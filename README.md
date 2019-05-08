1、在Visual Studio Code 软件的终端输入,安装ionic插件
npm install -g ionic


2、安装完成后 ,使用 ionic --version 检查是否安装成功


3、新建项目，项目名称为app，项目内容为tabs切换

ionic start app tabs

这里加了--type=angular才会生成angular的项目

ionic start myApp tabs --type=angular


4、终端输入 ionic serve 预览项目



cd myApp 进入项目


Visual Studio Code 进入插件安装：Ctrl + Shift + X


cd到我们的项目目录,创建对应的页面文件夹：

ionic g page booklist

安装淘宝cnpm

npm install -g cnpm --registry=https://registry.npm.taobao.org


F:\ionic\jdshop05>cnpm config get registry

https://registry.npm.taobao.org/

F:\ionic\jdshop05>npm config get registry

https://registry.npmjs.org/
