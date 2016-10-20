####关于margin的，容易搞错的地方####
在一个列表中，给父容器子元素的最后一个添加margin-bottom。视觉上是看不到效果的，实际上是margin-bottom作用在父元素身上，使得父元素的高度改变。

打开控制台，查看body高度，一目了然
	
例子参见链接[Demo](http://smileyby.github.io/margin_test)
