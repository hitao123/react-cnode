### learn react
1. 克隆[react-cnode](https://github.com/lzxb/react-cnode)这个项目
2. 这个项目是在react-china 这个社区讨论比较激烈，然后学习react，就克隆了这个项目
3. 这个项目的redux写的不是很好，数据太冗余，名称取得不好，`setState()`,
抽象思维很多，代码复用还可以，但是不怎么好理解
4. 我改写的基本是最原始，与我最开始接触的redux，react-router,react写法一致
5. 相比较原始的ajax，接触到的也是fetch API，准备在进行一次改造（redux-thunk）根本没有起作用（进行中）
6. 重新设计一下redux（进行中）



#### 知识点

1. ES6 module 

```export与export default
   //export class IndexList extends Component{}
   导出
   import { IndexList } from './index.js'
   //export  default class IndexList extends Component{}
   导出
   import IndexList/anyName from './index.js'

   2. import IndexList from './common'
   这种写法会自动去寻找 common 目录下 index 文件，(后缀省略是在webpack里面配置的)
   resolve: {
       extensions: ['', '.js', '.jsx'], //后缀名自动补全
   }
```

2. react的几种写法区别

```

```

3. 路由按需加载

```
```

4. webpack 1.0 配置

```
```

5. flex 布局

```
```

6. 获取下一页数据

```
```
 
