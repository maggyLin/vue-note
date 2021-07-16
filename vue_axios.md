### 1.安裝 axios
*https://github.com/axios/axios

> npm install axios <br>
> npm install --save axios vue-axios

### 2.在 main.js 引入
* import axios from 'axios'
* import VueAxios from 'vue-axios'
* Vue.use(VueAxios, axios)

### 3.在 component 使用
> process.env.VUE_APP_SERVEURL -> 使用.env檔,設定api連結直接呼叫<br>
> 參數設定: VUE_APP_(自定義名稱)<br>
> 參數呼叫: process.env.VUE_APP_(自定義名稱)<br>

#### 3-1. get (參數直接接網址後面)
this.axios.get(process.env.VUE_APP_SERVEURL+"?ID=2234")
 .then((response) => {
   console.log(response.data);
})

#### 3-2. post
this.axios.post(process.env.VUE_APP_SERVEURL, 
    this.$qs.stringify({  
        act:"abc",
    })
)
.then(function (response) {
    console.log(response);
})
.catch(function (error) {
    console.log(error);
})

> 參考資料: https://github.com/axios/axios

### 4.qs (axios post) (get 不用) - post 參數傳遞不成功解決方式

1. npm install qs --save 
2. main.js引入
 * import qs from 'qs';
 * Vue.prototype.$qs = qs;

> 參考資料: https://blog.csdn.net/huangxiaoguo1/article/details/80169742
