1、引入js文件：
	<script type="text/javascript" src="superfloat.js"></script>
2、放置div
	 <div id="gg1">
        ***** content ******
    </div>
3、加载
	<script type="text/javascript">
		<!--
        var sf=new SuperFloat("gg1",1,1,false,0.1,0,1);
        sf.Run();
		//-->
	</script>


参数说明

new SuperFloat(
	"gg1",  //对应容器id  这里id是gg1
	1,	//起始x坐标
	1,	//起始y坐标
	false,	是否显示关闭按钮   true\false
	0.1,	移动速度
	0,	x移动方向
	1	y移动方向
);
