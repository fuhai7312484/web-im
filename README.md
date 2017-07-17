## 环信 WebIM sdk

测试环信WebIM请访问：https://webim.easemob.com

更多关于环信的开发文档请见：https://docs.easemob.com


### create-react-app

https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#code-splitting

## Ant Design

- how to custom theme ?
    - how to custom theme dynamically
- how to make responsive component ? see: Sider.tsx
- ie9 pollyfill 


https://github.com/ant-design

### 自定义antd样式

参考：https://ant.design/docs/react/customize-theme-cn

1. 组件按需引入
    - 文件修改并不会触发页面刷新
    - 适合prod时使用
    - theme.js And webpack
2. 全部导入 
    - 资源多
    - 按照正常的加载less的逻辑
    - 文件修改会触发页面刷新
    - 适合开发时使用
    - theme.less

## 路由 react-router

- code splitting with webpack ?
- how to do auth ?
- how to add transition ?

https://react-guide.github.io/react-router-cn/
https://github.com/ReactTraining/react-router
https://github.com/thejameskyle/react-loadable
https://reacttraining.com/react-router/web/guides/code-splitting/code-splitting-server-rendering

## react-bits

- HOC ?

https://github.com/vasanthk/react-bits


## ant-admin


https://github.com/zuiidea/antd-admin/blob/master/src/router.js


## Tips

### media-match

- how to do media query in component ?


### 布局

position: abasolute; 浮动层，不占用内容区域大小
所以sider和footer都这种浮动层，的父级元素必须是最外层决定内容大小的元素比如body
relative的父级不能是内容的大小，因为内容区可能很小，会影响sider和footer的大小

body: min-height: 1000px


## storybook

```
npm i -g @storybook/cli
getstorybook
yarn run storybook
```

https://github.com/storybooks/storybook/tree/master/lib/cli
https://storybook.js.org/configurations