# h1
## h2
### h3
#### h4
##### h5
###### h6
一级标题
======================
二级标题
---------------------
> hello world!
> hello world!
> hello world!
hello world!   
> aaaaaaaaa
>> bbbbbbbbb
>>> cccccccccc
标记之外`hello world`标记之外
>>> 标记之外 ` 
< div>   
    < div></div>
    < div></div>
    < div></div>
< /div>
`标记之外

```
<div>   
    <div></div>
    <div></div>
    <div></div>
</div>
```
我是文字……

    <div>   
        <div></div>
        <div></div>
        <div></div>
    </div>
```javascript
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```

[百度1](http://www.baidu.com/" 百度一下"){:target="_blank"}

[百度2][2]{:target="_blank"}
[2]: http://www.baidu.com/   "百度二下"

<i>斜体</i>

```javascript
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```

```sequence
A->>B: 你好
Note left of A: 我在左边     // 注释方向，只有左右，没有上下
Note right of B: 我在右边
B-->A: 很高兴认识你
```

```flow                             // 流程
st=>start: 启动|past:>http://www.baidu.com[blank] // 开始
e=>end: 结束                      // 结束
op1=>operation: 方案一             // 运算1
sub2=>subroutine: 方案二|approved:>http://www.baidu.com[_parent]  // 运算2
sub3=>subroutine: 重新制定方案        // 运算2
cond1=>condition: 行不行？|request  // 判断条件1
cond2=>condition: 行不行？          // 判断条件2
io=>inputoutput: 结果满意           // 输出

// 开始->方案1->判断条件->
st->op1->cond1
// 判断条件1为no->方案2->判断条件2为no->重新制定方案->方案1
cond1(no,right)->sub2->cond2(no,right)->sub3(right)->op1
cond1(yes)->io->e       // 判断条件满足->输出->结束
cond2(yes)->io->e       // 判断条件满足->输出->结束
```