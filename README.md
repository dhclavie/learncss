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


----------
>CSS盒子模型

1.
一个孤立的盒子的内部结构
2.
多个盒子之间的相互关系

盒子模型 ＝
connent内容 +
border边框 +
padding内边距 +
margin外边距

计算元素的宽和高时，要讲border纳入。


----------
>CSS属性float和posititon

浮动float：默认为none，如果设置为非none，则盒子脱离标准流。

Postition，默认值为static，按照盒子标准流

1.
relative（相对定位），仍在标准流中，相对于原来所在标准流中的位置，进行一定偏移。
2.
absolute（绝对定位），不在标准流中，以最近的已经定位的祖先元素进行定位。
3.
fixed（固定定位），不在标准流中，以浏览器窗口进行定位。

----------
>z-index空间位置

当被设置了position属性时这个属性才有意义。

----------
>display属性

修改盒子的类型为块block，行inline或者把盒子隐藏none

----------
>CSS布局技术的3个基本概念：定位，浮动和外边距操纵


