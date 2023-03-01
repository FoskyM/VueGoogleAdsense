# VueGoogleAdsense
Vue2谷歌广告组件

# 使用方法

1. 在 main.js 中引入并挂载

~~~js
import Adsense from './components/Adsense'
Vue.component('adsense', Adsense)
~~~

2. 在要用到的地方使用

~~~vue
<adsense
  ad-client="ca-pub-xxxxxxxxx"
  ad-slot="xxxxxx"
  ad-style="display: block"
  ad-format="auto"
  responsive="true">
</adsense>
~~~
