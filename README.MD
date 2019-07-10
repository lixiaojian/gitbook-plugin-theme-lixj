### GITBOOK主题插件 gitbook-plugin-theme-lixj

### 配置参数
```javascript
const params = {
    "pluginsConfig": {
        "theme-lixj":{
          //是否显示logo 默认不显示
          "logo":false , 
          //页头的导航 没有的话，不传就行
          "nav":[
              //导航的className
              "className":"header-nav",
              //导航的另一个className 用于给nav定义多个样式 比如添加选中的状态
              "className2":"active",
              //导航的链接地址
              "href":"http://www.lixj.vip" ,
              //链接的target属性值
              "target":"_blank",
              //链接的显示内容
              "text":"我的主页"
          ] ,
          "search-placeholder":"输入关键字搜索"
        }
      }
}
```