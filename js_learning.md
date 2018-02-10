## [JavaScript入门篇](https://www.imooc.com/learn/36)

- 1-1 如何插入js
同文件， 引用JS外部文件

- 1-4 JS再页面中的位置
一般在<head> <body> 中

- 1-6 Java script 注释
 
与C一一致：
    1 单行注释 `//`
    2 多行注释 `/**/`

- 1-7 定义变量 关键字 var 
```c
var mynum = 6;
```
- 1-8 判断语句（if...else）
- 1-9 函数

一般语法
```c
function func_name()
{
   //code
}
```
- 2-1 输出
```
document.write("");// 可以使用"+" 串联
```
- 2-2 警告 

按顺序弹出警告对话框
```
alert(字符串常量)
```

- 2-3 确认

confirm 消息对话框通常用于允许用户做选择的动作
```
confirm(str);
```
- 2-4 提问

prompt弹出消息对话框,通常用于询问一些需要与用户交互的信息。弹出消息对话框（包含一个确定按钮、取消按钮与一个文本输入框）
```
prompt(str1, str2);
```
- 2-5 打开新窗口
```
window.open()
```

- 2-6 关闭窗口
```
window.close
```
- 3-1 DOM
文档对象模型DOM（Document Object Model）定义访问和处理HTML文档的标准方法。DOM 将HTML文档呈现为带有元素、属性和文本的树结构（节点树）。
元素节点
文本节点
属性节点

- 3-2通过ID获取元素
```
document.getElementById(“id”) 
```

- 3-3
innerHTML 属性用于获取或替换 HTML 元素的内容。
```
Object.innerHTML
```
Object是获取的元素对象，如通过document.getElementById("id")获取的元素。
- 3-4 改变HTML样式
```
Object.style.property=new style;
```
- 3-5 显示和隐藏
```
Object.style.display = value
```
- 3-6 控制类名
```
object.className = classname
```
    1.获取元素的class 属性
    2. 为网页内的某个元素指定一个css样式来更改该元素的外观




