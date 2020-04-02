# ==和equals()的区别是什么？
- ==和equals都可以判断对象地址是否相等,但判断数据类型的值只能用==去判断
- 假如是String的equals方法的话,则是比较两个字符串内是不是完全一样

# 抽象类和接口的区别？
- 抽象类可以抽象方法和普通方法,接口只有抽象方法,抽象方法必须得去重写实现。
- 抽象类只能单继承,接口可以多实现
- 接口基本数据类型默认为静态常量

# 普通类和抽象类的区别
- 抽象类不能被实例化,普通类能被实例化
- 抽象类有抽象方法时,重写该抽象类,必须得去实现它的抽象方法


# Java和C++的区别
- Java只能单继承,C++可以多继承
- C++有指针概念,Java没有,但有引用
- C++执行速度比Java块,Java可通过JVM跨平台
- C++需要自己释放内存,Java无需自己操作,可通过gc机制来自动释放内存。
- C++有重载运算符,Java不可以

# hashtable和hashmap区别
- HashMap线程不安全,Hashtable则线程安全
- HashTable允许传null key和value,HashMap则不允许
- Hashtable继承自Dictionary,HashMap继承自AbstractMap

# arraylist和linkedlist区别 
- ArrayList基于数组实现,LinkedList基于链表实现
- 在空间方面,ArrayList是数组元素空间连续,LinkedList数组元素空间不连续
- 对于随机查询方面,ArrayList可以以O(1)的时间复杂度返回,而LinkedList则要O(n),ArrayList比LinkedList块
- 在插入和删除方面,LinkedList需要O(1)时间,ArrayList需要O(n),LinkedList速度比ArrayList块

# String,Stringbuffer,StringBuilder区别
- String是字符串常量,一旦创建不可更改。StringBuffer和StringBuilder则可以动态追加和删除字符。
- StringBuffer线程安全,StringBuilder线程不安全,StringBuilder速度高于StringBuffer
- String适用于字符串不更改的情况,StringBuilder适用于单线程字符串经常变更,StringBuffer适用于多线程字符串经常变更

# 深复制和浅复制的区别

# String a = new String("-");产生几个对象？

# 创建线程有几种方法？
- 通过实现Runnable
- 通过继承Thread
- 通过callable和future

# final finally fnizle区别？

# 重写和重载的区别


