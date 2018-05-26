# vue-demo
some small vue case

通过vue框架,程序员只对数据进行操作,而不需要关心Dom操作渲染问题,以下案例均无DOM操作


1.horse-race-lamp(跑马灯)    //通过 v-model双向绑定数据msg字符串,通过@click方法对msg字符串进行分割,拼接形成新的msg.

2.table-list(学生列表)      //通过v-model双向绑定查询关键字key, search(key)过滤list数组并返回一个新数组newList, v-for渲染newList, 同样v-model双向绑定  id , name 拼接成新对象  ,add()将这个对象push进list,   del(index)删除该行.

3.filter(过滤器,正则表达式)   //padStart() es6字符串新特性，自动补全，如时间 12点6分3秒 12:6:3
使用padString（2,0） 就会变成12:06:03