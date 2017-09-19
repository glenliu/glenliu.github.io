# Python #
Python是一种解释型、面向对象、动态数据类型的高级程序设计语言。

Python由Guido van Rossum于1989年底发明，第一个公开发行版发行于1991年。

像Perl语言一样, Python 源代码同样遵循 GPL(GNU General Public License)协议。

 Python中默认的编码格式是 ASCII 格式，在没修改编码格式时无法正确打印汉字，所以在读取中文时会报错。

解决方法为只要在文件开头加入 # -*- coding: UTF-8 -*- 或者 #coding=utf-8 就行了 

credit: [Runoob | http://www.runoob.com/python/python-basic-syntax.html]
## Basics ##
Python 标识符

在 Python 里，标识符由字母、数字、下划线组成。

在 Python 中，所有标识符可以包括英文、数字以及下划线(_)，但不能以数字开头。

Python 中的标识符是区分大小写的。

以下划线开头的标识符是有特殊意义的。以单下划线开头 _foo 的代表不能直接访问的类属性，需通过类提供的接口进行访问，不能用 from xxx import * 而导入；

以双下划线开头的 __foo 代表类的私有成员；以双下划线开头和结尾的 __foo__ 代表 Python 里特殊方法专用的标识，如 \_\_init\_\_() 代表类的构造函数。

Python 可以同一行显示多条语句，方法是用分号 ; 分开

Python语句中一般以新行作为为语句的结束符。

但是我们可以使用斜杠（ \）将一行的语句分为多行显示

Python 可以使用引号( ' )、双引号( " )、三引号( ''' 或 """ ) 来表示字符串，引号的开始与结束必须的相同类型的。

其中三引号可以由多行组成，编写多行文本的快捷语法，常用于文档字符串，在文件的特定地点，被当做注释。

python中单行注释采用 # 开头。python 中多行注释使用三个单引号(''')或三个双引号(""")。

print 默认输出是换行的，如果要实现不换行需要在变量末尾加上逗号

缩进相同的一组语句构成一个代码块，我们称之代码组。

像if、while、def和class这样的复合语句，首行以关键字开始，以冒号( : )结束，该行之后的一行或多行代码构成代码组。

我们将首行及后面的代码组称为一个子句(clause)。

执行脚本传入参数，使用sys模块，
>    #!/usr/bin/python
>    # -*- coding: UTF-8 -*-
>    
>    import sys
>    
>    print sys.argv

**sys.argv[0]** 代表文件本身路径，所带参数从 **sys.argv[1]** 开始。

脚本语言的第一行，目的就是指出，你想要你的这个文件中的代码用什么可执行程序去运行它，就这么简单。

\#!/usr/bin/python : 是告诉操作系统执行这个脚本的时候，调用 /usr/bin 下的 python 解释器；

\#!/usr/bin/env python(推荐）: 这种用法是为了防止操作系统用户没有将 python 装在默认的 /usr/bin 路径里。当系统看到这一行的时候，首先会到 env 设置里查找 python 的安装路径，再调用对应路径下的解释器程序完成操作。

#!/usr/bin/python 相当于写死了python路径;

#!/usr/bin/env python 会去环境设置寻找 python 目录,推荐这种写法

### Variable ###

### OO ###

## List, Tuple, Dict ##
### List ###

### Slice ###

### Tuple ###

### Dictionary ###
|	What		|		How			|			Example		|
|	---			|		---			| ---					|
|				|					|						|
|				|					|						|

## IO ##

### File ###

### CSV ###

### Excel ###

## numpy ##

### ndarray ###

### broadcast ###

### vectorize ###

### statistics ###


## pandas ##

### Frame ###

### Series ###

### Performance ###



### IO ###

#### File ####

#### CSV ####

#### Excel ####


## matplotlib ##

### plot ###

