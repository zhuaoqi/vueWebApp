# 基于vue1.0开发的移动端H5积分商城项目
``` bash
基于vue@1.0开发的移动端H5积分商城项目
vue
vue-ruoter
vue-resource
webpack
```

## 示例

<p><img src="gif/demo.gif" width="375" height="667"></p>

## 运行

``` bash
#github仓库url
git clone https://github.com/vincentSea/vueWebapp.git
 or
git clone git@github.com:vincentSea/vueWebapp.git
```


``` bash
npm install
cnpm install (http://npm.taobao.org/)
```

``` bash
npm run dev   ----- localhost:8080  
npm run build ----- 打包项目
```

## mock.js
使用[Mock.js](http://mockjs.com/)模拟数据
```bash
# 安装
npm install mockjs --save
```


## 目录结构
<pre>

│  .gitattributes
│  .gitignore               # 忽略无需git控制的文件  比如 node_modules
│  favicon.ico
│  index.html               # 首页
│  index.tpl                # 首页模板
│  package.json             # 项目配置
│  README.md                # 项目说明
│  webpack.config.js        # webpack 配置文件
│
├─output                    #上线文件
│  
├─src                       
│  │  app.js                # 启动配置，配置路由，过滤器
│  │  App.vue               # 主vue
│  │  routers.js            # 路由
│  │  
│  ├─assets                 # 静态文件
│  │  ├─css
│  │  ├─images
│  │  └─lib
│  │          
│  ├─components             # 组件
│  ├─view                   # 样式
│  └─views                  # 页面
│           

</pre>


