# uni-template-news
基于uni-app开发的新闻/资讯类App模板
## 体验方式
同步/下载项目后，拖入 HBuilderX 中即可运行体验。
## 特点
* 兼容多个平台
* 自定义组件实现顶部选项卡切换
* App 平台使用 nvue 进一步优化体验

### 平台支持
* 5+App
* H5
* 微信小程序
* 百度小程序

## 注意事项
* 使用了 scroll-view 后无法使用下拉刷新，因此除了 5+App 外其它平台均没有下拉刷新。
## 已知问题
* 支付宝 scroll-view 组件不触发滚动到底事件，因此无法上拉加载更多。
* 百度小程序 v-for 和 v-if 不能同时写在同一个组件，并且 scroll-view 的实现有差异。