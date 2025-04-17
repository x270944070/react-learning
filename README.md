1. create-react-app基于运用
   安装脚手架
   $ npm i create-react-app -g
   检查安装情况
   $ create-react-app --version
   「mac前面要设置sudo」
   基于脚手架创建React工程化的项目
   $ create-react-app 项目名称
+ 项目名称要遵循npm包命名规范：使用“数字、小写字母、_”命名
  项目目录
  I- node_modules
  I- src：所以后续编写的代码，几乎都放在SRC下「打包的时候，一般只对这个目录下的代码进行处理」，index.js作为项目入口
  |- public： 放页面模板
  |- package.json
  ｜- ...
  一个React项目中，默认会安装：
  react:React框架的核心
  react-dom:React视图渲染的核心「基于React构建WebApp（HTML页面）」
  ---> react-native：构建和渲染App的
  react-scripts：脚手架为了让项目目录看起来干净一些，把webpack打包的规则及相关的插件/LOADER等都隐藏到了node_modules目录下，react-scripts就是脚手架
  中自己对打包命令的一种封装，基于它打包，会调用node_modules中的webpack等进行处理！！