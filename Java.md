# ==和equals()的区别是什么
- 对于==，当作用于比较基本数据类型的值时，则判断两个值是否相等，当作用于两个对象引用时，则判断是否指向同一个对象
- equals方法只能作用于判断两个对象是否一样，不能判断两个基本数据类型的值，当被重写的情况则不一样，比如说String,用于判断每个字符是否完全一样

# 抽象类和接口的区别？
- 抽象类可以抽象方法和普通方法,接口只有抽象方法,抽象方法必须得去重写实现。
- 抽象类只能单继承,接口可以多实现
- 接口基本数据类型默认为静态常量

# 普通类和抽象类的区别
- 抽象类不能被实例化,普通类能被实例化
- 抽象类有抽象方法时,重写该抽象类,必须得去实现它的抽象方法

# hashCode和equals的区别与联系
- equals用于比较两个对象是否引用于同一个对象,hashCode用于获取对象的哈希值
- equals相等的情况,hashCode一定相等
- hashCode相等,equals比较未必相等
- hashCode效率比equals高

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

# sleep()与wait()的区别
- wait方法只能在同步的情况下调用,sleep不必在同步情况下调用
- wait方法是Object里的方法,sleep是线程里的方法
- wait方法会释放锁,sleep不释放锁
- wait唤醒的条件是其他线程调用对象的notify()方法,sleep唤醒条件是超时或者调用interupt()

# Java gc有哪几种回收算法
- 标记清除法
- 复制法
- 标记整理法
- 分代收集法

# String a = new String("-");产生几个对象？
- 两个,new String产生在堆里,"-"产生在方法区

# 创建线程有几种方法？
- 通过实现Runnable
- 通过继承Thread
- 通过callable和future

# final finally fnizle区别？
- final适用于修饰不可变的常量
- finally适用于 try catch
- finizle使用于对象被销毁时的操作

# 重写和重载的区别
- 重写发生于父类之中,重载发生同一个类之中
- 重写必须方法名 参数列表 一样,重载要求方法名一样,参数列表必须不一样


# Java 栈和堆的区别
- 堆存储的是数组和对象,一般指的是new出来那些变量
- 栈存储的是引用和数据类型变量

