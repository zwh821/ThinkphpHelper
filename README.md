ThinkphpHelper
==============
Thinkphp是我个人非常喜欢的一个php框架，使用它来写代码一切都那么简单有效，但是我沮丧的发现很多时候我都在做重复的事情，比如重复写最简单的CRUD方法，编写表单，写前台样式表等等。

Thinkphp对于后台操作的支持已经非常强大，再加上最近非常流行的Bootstrap框架让前台样式也变得容易遵循一个标准，于是我决定开始写一个属于自己的代码生成器。

我希望它操作足够简单，让人一看就懂，对MySql和Sqlite数据库都能够稳定生成CRUD代码就好，还如果还能顺便生成一些符合Bootstrap框架的View代码就更好啦。

经过了大概十几个小时的奋斗，ThinkphpHelper诞生啦！

它只有一个文件，你只需要配置好数据库信息后把它放到你项目文件的Action目录中，然后像这样调用它：http://[你的项目地址]/index.php/ThinkphpHelper

我把所有的样式表都写到了这个文件中，使它方便你复制粘贴到任何Thinkphp项目中，其中用到的Bootstrap和jquery的相关文件是读取网络上的CDN，所以使用它的时候最好保证你的网络畅通，如果你没有网络的话，可以自行修改相关的地址。

聪明的你一定知道它是怎么用的对吧？

项目地址：https://github.com/zhuanqianfish/ThinkphpHelper

