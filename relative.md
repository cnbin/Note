### 1.position与absolute：relative是大哥，absolute功能比较强，relative限制absolute 1、限制定位 2.限制层级 3、限制overflow

### 2.absolute是不受overflow影响的，但是如果大哥元素是relative则就会有影响了

![img](http://wx3.sinaimg.cn/mw690/78f9859egy1fgxph02mqkj20no0d5gpq.jpg)

### 3.当relative设置了具体的z-index(不包括auto)，absolute的z-indext不起任何作用了，此时的z-index的层级高低是由relative决定的

### 4.relative限制absolute的方向定位
![img](http://wx4.sinaimg.cn/mw690/78f9859egy1fgxtgmj1umj20o50e9ju7.jpg)