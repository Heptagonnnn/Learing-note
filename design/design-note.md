# 代码设计的新得

[toc]

## 关于外部变量传入的形式

1. 所有从函数外部获得的内容，尽量都用参数的形式传递
2. 对于很明显的对象属性，方法，可以使用this。
3. 如果无法很明显的确定函数作用域，那就方法1