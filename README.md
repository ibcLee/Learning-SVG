# Learning-SVG
Start to learn SVG!!!

#### SVG形状
###### 矩形`<rect>`
###### 圆形`<circle>`
###### 椭圆`<ellipse>`
###### 线`<line>`
###### 折线`<polyline>`
###### 多边形`<polygon>`
###### 路径`<path>`
`pathLength`属性接收一个非负数作为值，并使用这个值来覆盖浏览器计算的路径长度。

* `moveto` ( `M`或`m` ): 移动到新的位置
* `lineto` ( `L`或`l` ): 从当前坐标画一条直线到一个新坐标
* `horizontal lineto` ( `H`或`h` ): 画一条水平线到新坐标
* `vertical lineto` ( `V`或`v` ): 画一条垂直线到新坐标
* `closepath` ( `Z`或`z` ): 关闭当前路径

#### SVG滤镜
* feBlend
* feColorMatrix
* feComponentTransfer
* feComposite
* feConvolveMatrix
* feDiffuseLighting
* feDisplacementMap
* feFlood
* feGaussianBlur
* feImage
* feMerge
* feMorphology
* feOffset
* feSpecularLighting
* feTile
* feTurbulence
* feDistantLight
* fePointLight
* feSpotLight

#### SVG渐变
##### 线性渐变
`<linearGradient>`定义线性渐变
`<linearGradient>`标签必须嵌套在`<defs>`标签内

###### 线性渐变可被定义为水平、垂直或角形的渐变：
* 当 y1 和 y2 相等，而 x1 和 x2 不同时，可创建水平渐变
* 当 x1 和 x2 相等，而 y1 和 y2 不同时，可创建垂直渐变
* 当 x1 和 x2 不同，且 y1 和 y2 不同时，可创建角形渐变
		
##### 放射性渐变
`<radialGradient>`用来定义放射性渐变
`<radialGradient>`标签必须嵌套在`<defs>`标签内

#### Texts(写在图像中的文本)
`<text x="10" y="10">Hello World!</text>`
text-anchor: start | middle | end | inherit，允许决定从这一点开始的文本流的方向。
#### SVG字体
	



