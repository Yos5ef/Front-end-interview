# js数据类型隐式转换时，都做了什么？
### 讲原理之前先出一道面试题吧
```javascript
if (a == 1 && a == 2 && a == 3) {
  console.log('hello world');
}
```
### 怎样定义a变量才可以打印出 hello world呢？

观察这道题如果直接给a一个值是不可能打印出来，所以我们要想办法让a是可变的。
