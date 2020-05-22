### 组件介绍
vue-slide-show
Vue轮播图组件，支持自动播放、循环播放和触屏滑动切换图片。

#### 使用说明

1.安装：
npm：`npm install illmatic-slide-show --save`

yarn：`yarn add illmatic-slide-show`

2.注册组件：
`import illmaticSlideShow from 'illmatic-slide-show';`

`Vue.use(illmaticSlideShow);`

3.使用组件：
`<illmatic-slide-show></illmatic-slide-show>`


#### 配置项

##### props:

|参数名   |类型   |可填项   |说明   |默认值
| :------------ | :------------: | :------------ | :------------ |:------------:
|imageList   |Array   |例如:[url1,url2,url2,...]   |图片列表   |[]
|loop   |Boolean   |true/false   |是否循环（头尾相接）   |true
|autoPlay   |Boolean   |true/false   |是否自动播放   |true
|interval   |Number   |例如：5   |自动播放间隔时间，单位：秒   |5
|guide   |Boolean   |true/false   |是否展示下方导航点   |true
|control   |Boolean   |true/false   |是否开启触屏滑动切换图片   |true