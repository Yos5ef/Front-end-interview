### 请问下方打印的this的长度是多少？

function len(a,b,c){
    console.log(this.length);                 
}

let arr = [len, 1, 2, 3, 4, 5];

arr[0]();
