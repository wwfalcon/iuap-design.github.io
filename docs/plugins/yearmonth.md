# yearmonth插件

只选择年与月

# 插件依赖


首先依赖于 http://design.yyuap.com/static/uui/latest/js/u.js

再引入js: http://design.yyuap.com/static/uui/latest/js/u-date.js

# 用法

定义样式为`u-yearmonth`的div父元素，包裹类`u-input`的input

```
<div class='u-yearmonth'>
    <input class="u-input" type="text">
</div>

```

js会根据`u-yearmonth`来定位dom，然后绑定事件。


# 示例



<div class="example-content ex-hide"><style>.example .u-input{
	border: 1px solid rgba(0,0,0, 0.12);
	width: 250px;
}
</style></div>
<div class="example-content"><div class="example">
	<div class='u-yearmonth'>
	    <input class="u-input" type="text">
	</div>
</div></div>
<div class="examples-code"><pre><code>.example .u-input{
	border: 1px solid rgba(0,0,0, 0.12);
	width: 250px;
}</code></pre>
</div>
<div class="examples-code"><pre><code>&lt;div class="example">
	&lt;div class='u-yearmonth'>
	    &lt;input class="u-input" type="text">
	&lt;/div>
&lt;/div></code></pre>
</div>






