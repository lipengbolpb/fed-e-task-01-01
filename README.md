1. 
   输出：10
   原因：i 是全局作用中的 当循环过后 i 结果都是一样的

2.
  输出：123
  原因：

3. Math.min(...arr)

4. 
  var 定义的变量可以修改，如果不初始化会输出undefined，不会报错。作用域可提升。
  let  是块级作用域，函数内部使用let定义后，对函数外部无影响。
  const 是块级作用域 定义的变量不可以修改，而且必须初始化。

5.
  输出：20

6.
 用途：为对象添加独一无二的属性 对象的私有属性

7.
 浅拷贝：objdet.assgin()合并对象生成一个新对象，如果对象的属性是普通类型改变之后新对象不会改变，如果是引用类型改变后新对象会改变
 深拷贝：利用JSON.stringify(obj)将对象先转为json字符串，再JSON.parse(）转回为json对象可以实现深拷贝

8.
  JS是一门单线程的语言，代码只会一行一行的执行，为了解决阻塞进程,就出现了异步编程
  微任务和宏任务属于一个队列，主要区别在于它们的执行顺序（宏任务执行完如果有可执行的微任务则执行完微任务才会继续执行下一个宏任务）
  宏任务：包括整体代码script，，setInterval，setImmediate。
  微任务：原生Promise(有些实现的promise将then方法放到了宏任务中)、process.nextTick、MutationObserver
  
10.
  TypeScript 是 JavaScript 的一个超集
  TypeScript 可以使用 JavaScript 中的所有代码和编码概念，TypeScript 是为了使 JavaScript 的开发变得更加容易而创建的
  TypeScript 从核心语言方面和类概念的模塑方面对 JavaScript 对象模型进行扩展
  TypeScript 中的数据要求带有明确的类型，JavaScript不要求。
  TypeScript 为函数提供了缺省参数值
11.
  TypeScript优点：
	增强了代码的可读性和可维护性 
	可以在编译阶段就发现大部分错误，这总比在运行时候出错好
	.js 文件可以直接重命名为 .ts 即可
  TypeScript缺点：
	有一定的学习成本
	短期 小型项目不太适合，维护成本较高