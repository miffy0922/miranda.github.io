# 魔鬼先锋
### 《大牛程序员》项目技术文档总结

1. img跟background-image的区别(丁铭)
	大图片主要图片 都使用img ， background-image一般用来加载雪碧图，
	background 会慢一点，因为先调用css 再调用图片，  一般都是雪碧图。
2. 按钮 点击(丁铭)
3. （丁铭）
	点击按钮的 border实现 一个before after伪类分别作为圈 
		点击时候就小手移动， 移动的时候，会溢出按钮， 使用父div overflow 因为截的是方块，按钮是圆形 截不了  就可以通过移动小手 自己“送过去”被截掉
4. 文字渐变  其实是背景是渐变的，但是只对div中的文字进行（刘雨）
5. 字体不能过小， 在不同浏览器下可以接受的最小字体不一样。safari 支持12以下  chrome最小是12px（刘雨）
6. 遮罩 实现 伪类 boxshadow（冯富铭）
7. 字体问题~~  看连接 （王孟菲）
https://segmentfault.com/a/1190000007787731
8. 表单的轮播  实现 demo （王星宇）
9. 动画的砖 左右来回动 就是 0% 的时候在左边  50%的时候在右边 （刘雨）
10. 选择器的时候 用逗号的话，小心变成全局变量	（刘雨）
11. &nbsp容易出bug 不推荐  &#8195 是一个占位符 （丁铭）
12. 鼠标移到某个元素上 变为小手链接的是 cursor:pointer属性 （高劲飞）
13. 地图相关（胡风）