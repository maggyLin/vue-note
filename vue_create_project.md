# test_qsyj

## Project setup - 相關套件安裝
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```
### vue.config.js -> productionSourceMap 參數設定注意

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 版本
```
vue --version
```


//-----------------------------------------------

### vue -V 3.8.2

### vue-cli
*https://cli.vuejs.org/zh/guide/

npm install -g vue-cli

### 創建項目
*https://cli.vuejs.org/zh/guide/creating-a-project.html#vue-create

vue create hello-world

### vue-router
*https://router.vuejs.org/zh/installation.html

npm install vue-router

### vent (ui 組件)
*https://youzan.github.io/vant/#/zh-CN/quickstart

npm i vant -S
npm i babel-plugin-import -D

-> 在 babel.config.js 要引入相關plugins

### axios
*https://github.com/axios/axios

npm install axios
npm install --save axios vue-axios

### qs (axios post) (get 不用)
*https://blog.csdn.net/huangxiaoguo1/article/details/80169742

npm install qs --save 


### vuex (状态管理模式)
*https://vuex.vuejs.org/zh/

npm install vuex --save

//-----------------------------------------------------------------------------------------------

### vue.config.js --定義設定

### .env --環境變量
https://dotblogs.com.tw/twkhjl/2019/02/12/214725
https://www.itread01.com/content/1531476244.html

### 環境變量  .env檔案
变量命名格式： VUE_APP_NAME = value ( VUE_APP_是规定的命名格式(以VUE_APP_開頭)，NAME是自定义的名 )
呼叫: process.env.VUE_APP_NAME


### 空格驗證(空格缩进的规则),未關閉compile會報錯 
### eslint配置相關設定 (package.json-->eslintConfig)
https://www.jianshu.com/p/bfc7e7329cff

package.json-->"eslintConfig"-->"rules" 新增 "indent":"off" and "no-console":"off"














