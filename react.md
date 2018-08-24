# react


## 安装，启动等命令

1. 安装脚手架create-react-app
>npm install -g create-react-app
2. 创建项目
> create-react-app myproject
3. 启动
> cd myproject
> npm start

4. 显示配置
> npm run eject
4. 打包
> npm run build


## 腾讯软件 
[腾讯软件](https://pc.qq.com/);

## react dom渲染

> ReactDOM.render(dom,containDOM);

1. dom 一旦被渲染，就无法改变，只能通过变通方法，将重新指向render()方法，
    重新设置dom，来现修改dom
2. dom默认使用ES6模版引擎的方式，不是字符串    

## react jsx 和模版引擎｛｝表示

1. 解析值，运算都可以

## 组件

1. 首字母大写的类函数，返回 dom 就可以将函数名写成标签的形式

2. 组件内部有个state状态，通过调用setState()，设置状态来实现更新dom

3. 父子组件通信，父组件将回调函数传入子组件的属性中，子组件触发原生事件后调用父回调

4. 同级组件通信，通过找父组件来做中转站


## 高级应用
1. jsx 是React.createElement 的语法糖

2. 属性检查器，使用 prop-types库来完成 import PropTypes from 'prop-types';

3. ref 属性可以接受一个函数
``` 
<input type="text" ref={(input) => { textInput = input; }} />
```

4. 表单数据，如果是DOM处理就是非受控组件，如果是react处理就是受控组件

5. 开放版本和生产版本使用，减少提示，提升性能

6. context 

7. fragment 代码片段，就是空的jsx <></>,包装dom，实际显示时，不渲染，他是React.Fragment对象的
    语法糖，如果使用key 则使用 <React.Fragment key={index}></React.Fragment>


## react 生命周期 
[react 生命周期](https://www.cnblogs.com/qiaojie/p/6135180.html)
