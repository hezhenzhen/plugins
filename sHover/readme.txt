说明：
1.sHover是纯原生javascript编写的小组件，不需要引入jQuery或其他插件就可以使用
2.有很多不同的效果可以在创建默认的效果之后进行设置，设置方法简单
3.兼容性完美，新版本的浏览器上完美运行，也包括IE5以及之前的浏览器上运行

用法：
var example1=new sHover("example1","intro1");
example1.set({
	speed:7,
	opacity:80,						
	opacityChange:true
});
