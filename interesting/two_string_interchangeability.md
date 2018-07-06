### 两个字符换交换值 不能定义第三个变量

```javascript
function aaa(a, b) {
	a = b + a;
	b = a.slice(b.length, a.length);
	a = a.slice(0, a.length - b.length);
	console.log(a);
	console.log(b);
}
let a = 'qweq/驱蚊器二//驱蚊器翁//zczxczx';
let b = '驱蚊器';
aaa(a, b);
```
