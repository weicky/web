```html
<html>
<head>
<style type="text/css">
#outer {
	display:table;
	height:400px;
	*position:relative; /* “*”作用于IE6、7 */
	overflow:hidden;
}
#middle {
	display:table-cell;
	vertical-align:middle;
	*position:absolute;
	*top:50%;
}
#inner {
	margin:0px auto;
	*position:relative;
	*top:-50%;
}
</style>
</head>
<body>
<div id="outer">
	<div id="middle">
		<div id="inner">这里是要居中的内容</div>
	</div>
</div>
</body>
</html>
```