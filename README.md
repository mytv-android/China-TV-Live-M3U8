# 2025-03-08 09:22:36 已更新
> 湖南、重庆官网和APP均无直播入口，故无法获取；

> 天津、辽宁官网无直播入口，待分析APP端（有时间再说）；

> 广东暂时未能解决，貌似绑定IP；

> 江苏测试每次请求都要鉴权，就没加；

> 四川需要登录，所以就没必要弄了。

部分直播源须携带`Referer`请求头：

> 安徽（待研究APP）：`https://www.ahtv.cn/`

> 湖北（官网和APP都一样，暂时无解了）：`https://news.hbtv.com.cn/`

> 山东（待研究APP）：`https://v.iqilu.com/`

WebView源和m3u中的webview://直播源地址仅部分软件支持，如：天光云影3.3.7修改版。