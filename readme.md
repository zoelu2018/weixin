app.json 全局配置，包括了小程序的所有页面路径、窗口外观、界面表现、底部tar等
{
  "pages":[
    "pages/index/index",
    "pages/logs/logs"
  ],
  "window":{
    "backgroundTextStyle":"light",
    "navigationBarBackgroundColor": "#fff",
    "navigationBarTitleText": "Weixin",
    "navigationBarTextStyle":"black"
  },
  "style": "v2",
  "sitemapLocation": "sitemap.json"
}
- pages:用记录当前小程序所有页面的路径
- window：全局定义小程序所有页面的背景色、文字颜色等
- style: 全局定义小程序组件所使用的样式版本
- sitemapLocation: 用来指明sitemap.json
# WXML模板
  - view text image navigator(导航跳转)
  - 提供了Vue中的模板语法
# 宿主环境
# 组件
  text 相当于html的span
  view 相当于html的div 嵌套完成页面上的布局
  image 相当于image
  icon 
  navigator 跳转
# 常用的视图容器类组件
- view 
    - 普通视图区域
    - 类似div
    - 常用来实现页面的布局效果
- srcoll-view
    - 可滚动的视图区域
    - 常用来是实现滚动列表效果
- swiper 和 swiper-item
    -轮播图容器组件和轮播图item组件
- <text selectable>130387832982</text>
- <rich-text nodes="<h1 style='color : red'>标题</h1>"/>
- 其他常用的组件
  - button
    - 按钮组件
    - 通过open-type属性可以第哦啊用微信提供的各种功能
  - image
    - 图片组件
    - image组件默认宽高为300.240
  - navigator 
    - 页面导航组件
    - 类似a链接