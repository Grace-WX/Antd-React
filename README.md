# react antd-design
react 后台项目模板，使用antd design UI框架

# 安装React脚手架
npm install -g create-react-app

create-react-app Your Project Name

# 目录结构
Node-modules:安装依赖包的存放目录

Public 静态资源目录，index.开头的为入口界面，manifest缓冲文件

App.js是项目的根组件

App.css是项目的样式文件

Package.json包含了项目名称，描述，依赖列表，运行项目的script，eslint配置，browsers配置

# 提示
Create-react-app脚手架创建的项目默认是不支持less语法，所以我们通过 yarn eject 暴露出 webpack 文件
在config->webpack.config.js中添加，对照sass变量的定义，写入less。配置完成之后在 yarn add less