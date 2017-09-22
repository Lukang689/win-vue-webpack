
# 开发环境搭建：
## 1. 安装 node.js 。
## 2. 安装 cnpm （比 npm 更快）：
```
npm install -g cnpm --registry=https:registry.npm.taobao.org
```
## 3. 安装全局的 vue-cli 脚手架：
- 用于搭建所需的 Vue 开发模板框架

```
cnpm install -g vue-cli
//输入 vue-V，然后回车，出现 vue 的客户端版本信息，则说明安装成功了。
```
## 4.安装 Webpack：
- 类似于 Browserify 的模块打包器。

```
cnpm install -g webpack -g
//输入 webpack -h 查看是否安装成功
```

## 5.初始化项目：
- cd 到一个目录下，然后

```
vue init webpack Project-Name
```
- 此时在目录下会多了一个名为 <Project-Name>的文件夹，这个就是 vue 的模板项目。

## 6. 启动调试：
```
//安装依赖
cd Project-Name
cnpm install
npm run dev //这个是 debug 部署命令
```
- 端口启动，端口号可以在项目文件夹下的 config/index.js 中修改。
- 启动成功后会打开一个页面。


---
# 开发环境搭建完成
---

# 编译部署：
## 1. 在项目文件夹下：
```
npm run build
```
- dist 文件夹里面就是编译好的文件了。

