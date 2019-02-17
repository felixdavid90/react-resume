# 动态简历 #

## 介绍 ##
最近看到别人用vue做了一个动态简历，感觉很有意思，所以我就用react和redux自己也做了一份。

至于为什么用redux，大概是因为前端总是喜欢把简单的事情搞复杂吧哈哈哈哈。

原作者链接：http://strml.net/
## 预览 ##
请戳这里：https://yinguangyao.github.io/react-resume/build/index.html

## 运行 ##

运行前请确认自己安装了node.js和npm的环境。
```
git clone https://github.com/yinguangyao/react-resume.git
npm install
npm run build
```
然后在浏览器里面输入localhost:4000就可以运行了。

当然你也可以直接打开build下面的index.html，因为这已经是编译过的了，你也可以在src/assets/data.js里面修改数据，然后重新编译生成自己的动态简历。

## 说明 ##
使用async和await时遇到babel编译的坑，最后用babel-runtime和babel-plugin-transform-runtime两个模块搞定了。

可以借助redux-devTools的chrome插件来查看redux里面的所有状态。

关于webpack和react环境的搭建，请看我这篇博客：https://segmentfault.com/a/1190000008574361

## 更新 ##
这个简历是2017年使用react-redux和webpack1.0搭建而成，最近使用mobx、TypeScript和parcel进行了重构，在v2.0分支可以看到。