# tools
# scrollReveal.js
css样式动画库
官网: https://scrollrevealjs.org/api/reveal.html
## npm安装
```
npm install scrollreveal
```
## 引入
```
import scrollReveal from 'scrollreveal';
import retScroll  from '@/utils/scorll.js';
```
## 配置
```
// 赋值
const data = reactive({
      scrollReveal: scrollReveal()
})
      // 页面加载声明周期
onMounted(() => {
      // 启动scrollReveal的方法 需要传参
      retScroll(data)
})
```
## 使用
```
// 在需要添加动画的盒子上添加 reveal-top 类名
```
# timetrun.js
传入一个时间戳，输出为 2022-1-12 12:25:30 格式
## 引入
```
// 按需引入方法
import { parseTime } from '@/utils/tool.js'; // 引入时间格式化
```
## 使用
```
parseTime(time, '{y}-{m}-{d} {h}:{i}')
// value1：时间戳;value2：输出时间的格式
```
