

>引入CSS的形式

1. 行内式，直接在标记的style属性里面设置css样式
2. 嵌入式，在head标签内写css代码
3. 链接式

<link href="xxxx" rel="stylesheet" type="text/css" />
4. 导入式

<style type="text/css">
@import "mystlcs.css"
</style>

----------
>基本CSS选择器

所有HTML的标记样式都通过不同的CSS选择器进行控制。

1. 标记选择器：试用html标签来设置样式

h1{color:red;}

2. 类别选择器

.red{xxxxx}
3. ID选择器

#id{xxxxxxx}

----------
>复合选择器


复合选择器就是两个或者以上的基本选择器通过不同的方式组合在一起。

1.
交集选择器：由两个选择器直接连接构成，其结果是选中二者各自元素范围的交集。

h3.calss{xxxx}
2.
并集选择器：选中多个选择器所选择的范围的组合，通过逗号连接。

h2,h3{xxxxxxx}
3.
后代选择器：对内层元素进行设置样式，外层标记写在前面，内层标记写在后面，使用空格分隔。

p h1{ddddddd}


----------
>CSS的层叠特性

优先级：行内样式 >
ID选择器 > 类别选择器 >
标记选择器  
