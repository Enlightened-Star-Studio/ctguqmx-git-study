[中文](./README.md)  |   English


<h1 align="center"> 🚀ctguqmx-git-study </h1>
<h4 align="center"><a href="https://#" target="_blank">Basic GitHub Learning + Practice</a></h4>


|Introduction and specification | submission and testing | cooperative testing | code review | conflict resolution | participation in open source|
| :---------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :----------------------------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------:  |
| [☁️](./Lv1Introduction to Little White) | [💻](./Lv2Submit test) | [💾](./Lv3Introduction to Little White) | [🎨](./Lv4Introduction to Little White) | [🔧](./Lv5Introduction to Little White) | [🐍](./Lv6Introduction to Little White) | 

---
<h1 align="center"> ☁️ Warehouse Usage Guide</h1>
## Development specification
**1.Common submission reference * *: the following example must be referred to for the comment information of commit

```
feat：New XXX features

fix：Repair XXX function. If it is a repair issue, remember to note the issue number

docs：Modify document；

refactor：Code refactoring without adding any functions and fixing any bugs；

test：Modification of test cases；
```

**2. [Based on plug-in specification submission](https://blog.csdn.net/qq_39996837/article/details/91345528)**

- Global installation[commitizen](https://github.com/commitizen/cz-cli) (frame): `npm install commitizen -g` 
- Use the plug-in in the project directory `commitizen init cz-conventional-changelog --save --save-exact
` 
- Use `git cz` Replace previous `git commit`At this time, the plug-in will ask you to submit according to the specification  
