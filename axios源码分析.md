- 浏览器专属：FormData, File, Blob
- Node 专属： Stream
- adapters： 主要是网络请求适配器部分的源码，包括浏览器端的xhr和nodejs端的http。
- cancel: 主要是取消请求的cancel和cancelToken相关类。
- core: axios的核心功能，重点类有以下几个: Axios, dispatchRequest和InterceptorManager
#core文件夹
| 文件 | 内容 |
| :-: | :-: | :-: |
| Axios.js | 定义Axios类 |
| dispatchRequest.js | 用来调用适配器方法发送http请求 |
| InterceptorManager.js | 拦截器构造函数 |
- helper : 帮助类
- axios: 定义axios库的接口和默认实例
- defaults: 默认配置
- utils: 工具方法