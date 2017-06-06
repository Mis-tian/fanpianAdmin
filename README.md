# RecordAdmin
## Todo

- ~~访客、用户统计图表~~
- ~~用户管理列表~~
- ~~文章管理列表~~
- ~~模块管理~~
- 文本编辑器

## 界面
### 文章列表
![](https://github.com/douglasvegas/fanpianAdmin/blob/master/screenshots/%E6%96%87%E7%AB%A0%E5%88%97%E8%A1%A8.png)


### ISSUES
- 建议使用可控表单
 > 符合React的数据流，单向数据流，从state流向render输出的结果。
 数据存贮在state中，便于使用。便于对数据进行处理
- webpack publicPath影响打包结果的问题
- componentDidMount和componentWillUpdate使用可能出现死循环，慎重。
- 手动删除token、返回登录无法进入界面、流程控制问题。用登录成功的回调函数修改state？