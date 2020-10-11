# problem

* demo1	是第一次导入vue.js写了一个hello，但是无法显示内容。试过改变vue.js的插入位置，更换浏览器，结果都一样。
* demo2     只是从文本上复制别人的笔记，可以正常显示，在浏览器的控制台可以调用message，改变内容。
* demo3      是自己第二次写的，结果还是无法显示date数据，浏览器的控制台提示message没有定义。





```html
vue.min.js:6 ReferenceError: message is not defined
    at ln.eval (eval at wa (vue.min.js:6), <anonymous>:3:65)
    at ln.t._render (vue.min.js:6)
    at ln.r (vue.min.js:6)
    at St.get (vue.min.js:6)
    at new St (vue.min.js:6)
    at vue.min.js:6
    at ln.$mount (vue.min.js:6)
    at ln.$mount (vue.min.js:6)
    at ln.t._init (vue.min.js:6)
    at new ln (vue.min.js:6)
Fe @ vue.min.js:6
```

