1.简单数据类型与复杂数据类型的存贮？
简单数据类型储存在栈中；
复杂数据类型存储在堆中；
目前基本数据类型有：Boolean、Null、Undefined、Number、String、Symbol，引用数据类型有：Object、Array、Function、RegExp、Date 等；

2.深浅拷贝？
对于仅仅是复制了引用（地址），换句话说，复制了之后，原来的变量和新的变量指向同一个东西，彼此之间的操作会互相影响，为 浅拷贝。

而如果是在堆中重新分配内存，拥有不同的地址，但是值是一样的，复制后的对象与原来的对象是完全隔离，互不影响，为 深拷贝。

而如果是在堆中重新分配内存，拥有不同的地址，但是值是一样的，复制后的对象与原来的对象是完全隔离，互不影响，为 深拷贝。

2.闭包的好处和坏处:
优点：重复使用变量，并且不会造成变量污染

缺点：更占内存，内存泄漏

3.js 的垃圾回收机制：
在 js 中能实现这样的垃圾回收的功能的一共有两种方式：标记清除 和引用计数

4.set 与 map 区别：
set 与 map 主要应用于数据重组，数据存储

Set 允许你可以存任何类型的唯一值

<!-- add(value)：新增，相当于 array里的push。
delete(value)：存在即删除集合中value。
has(value)：判断集合中是否存在 value。
clear()：清空集合。 -->

WeakSet 与 Set 的区别：
ES6 新增的一种新的数据结构，类似于数组，成员唯一（内部元素没有重复的值）。且使用键对数据排序即顺序存储
WeakSet 只能储存对象引用，不能存放值，而 Set 对象都可以。
WeakSet 对象是无法被遍历的（ES6 规定 WeakSet 不可遍历），也没有办法拿到它包含的所有元素。
字典（Map）：
map 对象是一个简单的键/值映射。任何值（包括对象和原始值）都可以用作一个键或一个值。
函数、对象、值、都可以作为键名
weakmap 的弱引用类型
置为 null 不存在

1.nginx

2.过滤

3.
