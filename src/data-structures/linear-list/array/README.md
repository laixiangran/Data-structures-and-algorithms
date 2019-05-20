# 什么是数组

[数组（Array）](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Array)是一种**线性表**数据结构。它用一组**连续的内存空间**，来存储一组具有相同类型的数据（JavaScript中的数组可以存储不同类型的数据，但最好遵循最佳实践）。

JavaScript 数组的长度和元素类型都是非固定的。因为数组的长度可随时改变，并且其数据在内存中也可以不连续，所以 JavaScript 数组不一定是密集型的，这取决于它的使用方式。一般来说，数组的这些特性会给使用带来方便，但如果这些特性不适用于你的特定使用场景的话，可以考虑使用类型数组 [TypedArray](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/TypedArray)。

两个关键点：

- 线性表
- 连续的内存空间和相同类型的数据

## 优点

- 随机访问

## 缺点

- 删除、插入比较复杂，需要做大量的数据搬移工作