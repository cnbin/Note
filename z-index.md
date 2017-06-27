### 7阶层叠水平:注意内联元素会覆盖浮动元素--更符合页面加载的功能和视觉呈现：通常，block水平盒子或float都是用来布局的，而内容都放置在inline盒子中，内容是页面中最重要的实体，因此层叠水平要高
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgxto055joj20zk0k0757.jpg)

![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgxtp0caulj20zk0k0wfd.jpg)

![img](http://wx3.sinaimg.cn/mw690/78f9859egy1fgxtpt31krj20zk0k03zi.jpg)

![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgxtqtuqejj20zk0k03zi.jpg)


### z-index 与层叠上下文
![img](http://wx1.sinaimg.cn/mw690/78f9859egy1fgxtrvvrq7j20zk0k0t9o.jpg)

### 当定位发生嵌套的时候 遵循祖先优先原则
![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgxup25tjaj20zk0k0myj.jpg)

### position relative  默认是 z-index：0
![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgxuqi8vtoj20zk0k00tm.jpg)

### z-index:auto /整数值/ inherit 
### z-index支持的特性:支持负值;支持css3 animation动画;在css2.1时代，需要和定位元素配合使用
### 如果不考虑CSS3,只有定位元素(position:relative/absolute/fixed/sticky)的z-index才有作用 在CSS3中有例外
![img](http://wx3.sinaimg.cn/mw690/78f9859egy1fgxurd2lfaj20zk0k0wf4.jpg)

### 层叠上下文
![img](http://wx3.sinaimg.cn/mw690/78f9859egy1fgxuu18tdij20zk0k074w.jpg)

### 层叠上下文的特性
![img](http://wx2.sinaimg.cn/mw690/78f9859egy1fgxusuqm3fj20zk0k0ta5.jpg)

### 元素z-index值不为auto的flex项（父元素display:flex|inline-flex）
![img](http://wx3.sinaimg.cn/mw690/78f9859egy1fgxuwwi8k5j20zk0k0mya.jpg)