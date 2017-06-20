

## 【兰州料理的菜单管理】
>应用原生JavaScript来实现
## 基本功能描述
1. 用户可以录入菜单信息；
2. 实时地显示菜单列表；
3. 用户可以删除菜单项

## 用到知识
1. 原生提示框 [window.prompt](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt)，用来和用户进行交互。
2. H5的本地存储 [window.localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)。
3. 待续







<script src='https://code.jquery.com/jquery-1.12.4.min.js'/>
<script type="text/javascript">
	$(document).ready(function() {
	    //为超链接加上target='_blank'属性
		$('a[href^="http"]').each(function() {
			$(this).attr('target', '_blank');
		});
	});
</script>