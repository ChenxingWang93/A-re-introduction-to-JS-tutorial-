# A-re-introduction-to-JS-tutorial-

与大多数的编程语言不同，JS没有输入输出的概念。它是一个在宿主环境(host environment)运行的脚本语言，任何与外界沟通的机制都是由宿主环境提供的。web browsers是最常见的宿主环境，但在非常多的其他程序中也包含
JavaScript解释器，如Adobe Acrobat、Adobe Photoshop、SVG 图像、Yahoo！的 Widget 引擎，[Node.js](https://nodejs.org/en/)之类的服务器端环境，NoSQL数据库，开源的[Apache CouchDB](https://couchdb.apache.org/)
嵌入式计算机，以及包括[GNOME](https://www.gnome.org/) (GNU/Linux上最流行的GUI之一)在内的桌面环境等等。

### 概览
js是一种多范式动态语言，包含类型、运算符、标准内置（built-in）对象方法，源于Java和C，所以这两种语言的许多语法特性同样适用JavaScript，JS通过原型链而不是class类来支持面向对象
(有关ES6类的内容参考[Classes](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Classes);有关对象原型参考[继承与原型链](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Inheritance_and_the_prototype_chain))
JS支持函数式编程--对象、函数可以被保留在变量中，像其他对象一样传递。

先从任何语言都不可获取的“类型”开始，JS程序可以修改值(value),这些值都有各自的类型。其中包括：

- [Number](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Number)(数字🔢)
- [String](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/String)(字符串)
- [Boolean](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Boolean)(布尔运算)
- [Function](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Function)(函数)
- [Object](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object)(对象)
- [Symbol](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Symbol)(ES2015 新增)
  - [Array](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Array)(数组🔢)
  - [Date](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Date)(日期📅)
  - [RegExp](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/RegExp)(正则表达式)
- [null](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/null)(空🈳️)
- [undefined](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/undefined)(未定义)

还有...看上去有些奇怪的[undefined](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/undefined)(未定义)类型和[null](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/null)
(空)类型。此外还有[Array](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Array)(数组)类型，及分别用于表示日期📅的[Date](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Date)
[RegExp](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/RegExp)(正则表达式)
这三种类型都是特殊的对象。

JS有一种内置的[Error](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Error)(错误)类型

一个个讨论👆的类型
