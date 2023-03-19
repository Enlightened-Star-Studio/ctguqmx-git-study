中文   |   [English](./README-EN.md)

<h1 align="center"> 🚀启明星Git学习 </h1>
<h4 align="center"><a href="https://#" target="_blank">基础github学习学习+实践</a></h4>
  
<div align="center">

|入门及规范|提交测试|版本管理|Code Review| 冲突解决 |参与开源 |
| :---------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------:  |
| [☁️](./Lv1小白入门) | [💻](./Lv2提交测试) | [💾](./Lv3版本管理) | [🎨](./Lv4代码审查) | [🔧](./Lv5冲突解决) | [🐍](./Lv6参与开源) | 

</div>

---
<h1 align="center"> ☁️ 仓库食用手册</h1>



## 如何使用
- 对于**每个同学**，都可以按照顺序依次去板块内完成对应的任务，如何进入下一个板块，每个板块不仅仅是学习基础知识还需要进行实战。
- 对于**高年级**的同学建议是都参与进来，尽量多贡献代码，给低年级同学提供规范，锻炼自己
- 每个模块尽量都加一些**模拟实战**的小项目，来进行实战
- 虽然是本项目是试验场，但**不欢迎不兜底的进行提交**，对自己代码负责对仓库负责
- 但**同时出问题了更好**，本项目后面阶段会故意人为制造问题，需要每位同学都参与并且能利用git版本进行修复

## 开发规范
**1. 提交须知**：`禁止提交1MB以上的大文件！！！` 
**2. 常用提交参考**：commit备注信息必须参考下面示例

```
feat：新增xxx新功能

fix：修复xxx功能，如果是修复issue记得备注issue号

docs：修改文档；

refactor：代码重构，未新增任何功能和修复任何bug；

test：测试用例的修改；
```

**3. [基于插件规范提交](https://blog.csdn.net/qq_39996837/article/details/91345528)**

- 全局性安装[commitizen](https://github.com/commitizen/cz-cli) (框架): `npm install commitizen -g` 
- 项目目录内使用该插件 `commitizen init cz-conventional-changelog --save --save-exact
` （第一次执行即可）
- 使用`git cz` 替代之前的 `git commit`这时候插件会要求你按照规范提交  
- 同时记得不要动`.gitignore` ,他会自动忽略该插件本地目录`node_modules`以及`package.json`提交，


## 项目提交忽略目录清单
```
node_modules //git提交规范插件依赖
package.json 
package-lock.json
```

## 贡献者

<!-- readme: collaborators,contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/404name">
            <img src="https://avatars.githubusercontent.com/u/56631419?v=4" width="100;" alt="404name"/>
            <br />
            <sub><b>绝伦N</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/wangxiangwen135">
            <img src="https://avatars.githubusercontent.com/u/74345877?v=4" width="100;" alt="wangxiangwen135"/>
            <br />
            <sub><b>Sxwxw</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/420xincheng">
            <img src="https://avatars.githubusercontent.com/u/74346123?v=4" width="100;" alt="420xincheng"/>
            <br />
            <sub><b>新橙</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/yxr2333">
            <img src="https://avatars.githubusercontent.com/u/75789516?v=4" width="100;" alt="yxr2333"/>
            <br />
            <sub><b>Icecream</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/errrrdz">
            <img src="https://avatars.githubusercontent.com/u/75832045?v=4" width="100;" alt="errrrdz"/>
            <br />
            <sub><b>Peiheng Zhang</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/lovekang3344">
            <img src="https://avatars.githubusercontent.com/u/101037867?v=4" width="100;" alt="lovekang3344"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/WTY2002">
            <img src="https://avatars.githubusercontent.com/u/81131511?v=4" width="100;" alt="WTY2002"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/chengxuyuanbai">
            <img src="https://avatars.githubusercontent.com/u/101038217?v=4" width="100;" alt="chengxuyuanbai"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/MI19632">
            <img src="https://avatars.githubusercontent.com/u/105859021?v=4" width="100;" alt="MI19632"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/spcodhu">
            <img src="https://avatars.githubusercontent.com/u/102903955?v=4" width="100;" alt="spcodhu"/>
            <br />
            <sub><b>全宇宙超级无敌帅的胡磊涛</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/zsh-8163">
            <img src="https://avatars.githubusercontent.com/u/92667025?v=4" width="100;" alt="zsh-8163"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Doubledog2">
            <img src="https://avatars.githubusercontent.com/u/94832822?v=4" width="100;" alt="Doubledog2"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/kvzjj">
            <img src="https://avatars.githubusercontent.com/u/102362550?v=4" width="100;" alt="kvzjj"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/lulu123TT">
            <img src="https://avatars.githubusercontent.com/u/81348359?v=4" width="100;" alt="lulu123TT"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/hqing2002">
            <img src="https://avatars.githubusercontent.com/u/81168638?v=4" width="100;" alt="hqing2002"/>
            <br />
            <sub><b>绘清</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/wuwuwu223">
            <img src="https://avatars.githubusercontent.com/u/81224214?v=4" width="100;" alt="wuwuwu223"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: collaborators,contributors -end -->
