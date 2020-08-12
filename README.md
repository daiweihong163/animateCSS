# animateCSS
animate动画封装
#引入
index.html文件引入
<link rel="stylesheet" href="对应目录/animate.min.css">
<script src="对应目录/animate.js"></script>
#使用
 animateCSS('对应dom元素', '动画特效').then((message) => {
		    console.log(message)
	    }).catch(err=>{
	    	console.log(err)
        });
 #动画特效参考链接https://animate.style/
