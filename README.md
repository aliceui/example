# example

---

Just for test purpose!

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/example.css">

> 如果顺利的话，你看到的按钮和提示都将是有样式的。

<input type="button" class="ui-button ui-button-morange" value="我是一个橙色按钮">

<div class="ui-tipbox ui-tipbox-message">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="提示">&#xF046;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">提示标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>

````js
seajs.use(['./dist/function-debug.js'], function() {
});
````
