    DOM1级主要定义了HTML和XML文档的底层结构。在DOM1中，DOM由两个模块组成：DOM Core（DOM核心）和DOM HTML。其中，DOM Core规定了基于XML的文档结构标准，通过这个标准简化了对文档中任意部分的访问和操作。DOM HTML则在DOM核心的基础上加以扩展，添加了针对HTML的对象和方法，如：JavaScript中的Document对象.
    DOM2级在原来DOM的基础上又扩充了鼠标、用户界面事件、范围、遍历等细分模块，而且通过对象接口增加了对CSS的支持。DOM1级中的DOM核心模块也经过扩展开始支持XML命名空间。在DOM2中引入了下列模块，在模块包含了众多新类型和新接口：
    DOM视图（DOM Views）：定义了跟踪不同文档视图的接口
    DOM事件（DOM Events）：定义了事件和事件处理的接口
    DOM样式（DOM Style）：定义了基于CSS为元素应用样式的接口
    DOM遍历和范围（DOM Traversal and Range）：定义了遍历和操作文档树的接口
    DOM3进一步扩展了DOM，在DOM3中引入了以下模块：
    
    DOM加载和保存模块（DOM Load and Save）：引入了以统一方式加载和保存文档的方法
    DOM验证模块（DOM Validation）：定义了验证文档的方法
    DOM核心的扩展（DOM Style）：支持XML 1.0规范，涉及XML Infoset、XPath和XML Base

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgye7piaycj20zk0k0t9s.jpg)


### 节点类型

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgyez1sludj20zk0k0wfn.jpg)

### 字符常量IE浏览器不兼容（Node未定义），数值常量所有浏览器都兼容

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyf53qf3nj20zk0k075g.jpg)

### domReady：
### html标签需要通过浏览器渲染引擎的解析才会变成dom节点，在刷新url地址的时候就有dom构建的过程。当所有html都转化为节点后，dom树才构建完毕，简称为dom ready。所以，一旦把script放在body前面，dom还没生成，就调用了dom(document.xxxx)明显是不行的（javascript以编写顺序解析---脚本语言）

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyfqljhvqj20zk0k074w.jpg)

### 浏览器渲染引擎的基本渲染流程： 外部资源（图片，iframe，脚本）的加载贯穿始终，即使DOM节点渲染完毕了，外部资源可能正在加载或尚未加载

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgyfvawjbxj20zk0k0wfa.jpg)

#### 扩展阅读：http://kb.cnblogs.com/page/129756/


### DomReady实现策略
![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgygb4t6ipj20zk0k0gms.jpg)

### js的window.onload和jquery的ready原理不一样，jquery的更快
![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgygjztne3j20zk0k0my8.jpg)

### 元素节点类型的判断：4个方法
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgygmxxbqzj20zk0k0gmc.jpg)


### 元素节点类型的判断
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgygnl4821j20zk0k0gmu.jpg)

### DOM节点继承层次：createElement
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgygv2da3ej20zk0k0aar.jpg)

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyguvd3ylj20zk0k0gmb.jpg)


### 一个空的div元素自有的属性
![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgygzc83mkj20zk0k0wh4.jpg)

### 块状元素与内联元素
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgyh1wz7fqj20zk0k075o.jpg)

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgyh31g4flj20zk0k0wfp.jpg)

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyh464vk5j20zk0k0ab8.jpg)

![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgyhlp119kj20zk0k03z6.jpg)

![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgyhlo7la9j20zk0k0aax.jpg)

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgyhnzpoywj20zk0k03z6.jpg)

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyhnyfyvuj20zk0k0jsh.jpg)

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyhv2q1xgj20zk0k0abx.jpg)

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyhw5vg2aj20zk0k0q4c.jpg)

### 表格系列

![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgyhxm2oqkj20zk0k0ab1.jpg)



