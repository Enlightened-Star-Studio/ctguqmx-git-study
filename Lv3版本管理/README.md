中文   |   [English](./README-EN.md)

<h1 align="center"> 🚀合作测试 </h1>
<h4 align="center"><a href="https://#" target="_blank">大二同学一起维护下</a></h4>



---
<h1 align="center"> ☁️ 仓库食用手册</h1>
## 开发规范
**1. 常用提交参考**：commit备注信息必须参考下面示例

```
feat：新增xxx新功能

fix：修复xxx功能，如果是修复issue记得备注issue号

docs：修改文档；

refactor：代码重构，未新增任何功能和修复任何bug；

test：测试用例的修改；
```

**2. [基于插件规范提交](https://blog.csdn.net/qq_39996837/article/details/91345528)**

- 全局性安装[commitizen](https://github.com/commitizen/cz-cli) (框架): `npm install commitizen -g` 
- 项目目录内使用该插件 `commitizen init cz-conventional-changelog --save --save-exact
` 
- 使用`git cz` 替代之前的 `git commit`这时候插件会要求你按照规范提交  
