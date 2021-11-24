简体中文 [English](README.md)

# BoxedCheck for Radio & Checkbox v1.0.7
#### 纯净的CSS，没有任何JavaScript代码，盒式/卡片式的 Radio 和 Checkbox 美化!

### 下载

* 查看文档: [https://flyartist.github.io/boxed-check/index.html](https://flyartist.github.io/boxed-check/index.html)

* 发行版本: [https://github.com/FlyArtist/boxed-check/releases](https://github.com/FlyArtist/boxed-check/releases)

### 预览
BoxedCheck 已经包含了 Radio 和 Checkbox 组件.

![overview](http://res.beanie.top/BoxedCheck/demo1.png)


### 快速开始

想快速添加 BoxedCheck 到您的项目中? 复制粘贴以下 ```<link>``` 到您的 ```<head>``` 中来加载 CSS.

```
<link rel="stylesheet" href="boxed-check.min.css">
```
### 启动模板
确保您的页面遵从了最新的设计规范和开发标准.


	<div class="boxed-check-group">
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-demo">
	        <div class="boxed-check-label">Radio 1</div>
	    </label>
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-demo">
	        <div class="boxed-check-label">Radio 2</div>
	    </label>
	
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="checkbox" name="checkbox-demo">
	        <div class="boxed-check-label">Checkbox 1</div>
	    </label>
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="checkbox" name="checkbox-demo">
	        <div class="boxed-check-label">Checkbox 2</div>
	    </label>
	</div>

##### 或者这样:

	<div class="boxed-check-group">
	    <div class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-demo" id="radio-demo-1">
	        <label class="boxed-check-label" for="radio-demo-1" >Radio 1</label>
	    </div>
	    <div class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-demo" id="radio-demo-2">
	        <label class="boxed-check-label" for="radio-demo-2" >Radio 2</label>
	    </div>
	
	    <div class="boxed-check">
	        <input class="boxed-check-input" type="checkbox" name="checkbox-demo" id="checkbox-demo-1">
	        <label class="boxed-check-label" for="checkbox-demo-1" >Checkbox 1</label>
	    </div>
	    <div class="boxed-check">
	        <input class="boxed-check-input" type="checkbox" name="checkbox-demo" id="checkbox-demo-1">
	        <label class="boxed-check-label" for="checkbox-demo-2" >Checkbox 2</label>
	    </div>
	</div>

### 主题
您可以使用 ```.boxed-check-*``` 类为 BoxedCheck 装饰颜色.

![overview](http://res.beanie.top/BoxedCheck/demo2.png)

	<div class="boxed-check-group boxed-check-default"> ... </div>
	<div class="boxed-check-group boxed-check-secondary"> ... </div>
	<div class="boxed-check-group boxed-check-primary"> ... </div>
	<div class="boxed-check-group boxed-check-success"> ... </div>
	<div class="boxed-check-group boxed-check-danger"> ... </div>
	<div class="boxed-check-group boxed-check-warning"> ... </div>
	<div class="boxed-check-group boxed-check-info"> ... </div>
	<div class="boxed-check-group boxed-check-dark"> ... </div>

### 无底色的主题
将默认的主题类替换为 ```.boxed-check-outline-*``` 类将移除所有的底色和背景，并且只留下边框.

![overview](http://res.beanie.top/BoxedCheck/demo3.png)

	<div class="boxed-check-group boxed-check-outline-default"> ... </div>
	<div class="boxed-check-group boxed-check-outline-secondary"> ... </div>
	<div class="boxed-check-group boxed-check-outline-primary"> ... </div>
	<div class="boxed-check-group boxed-check-outline-success"> ... </div>
	<div class="boxed-check-group boxed-check-outline-danger"> ... </div>
	<div class="boxed-check-group boxed-check-outline-warning"> ... </div>
	<div class="boxed-check-group boxed-check-outline-info"> ... </div>
	<div class="boxed-check-group boxed-check-outline-dark"> ... </div>

### 内联元素 & 元素尺寸
 给任意 ```.boxed-check``` 类添加 ```.boxed-check-inline``` 类使 BoxedCheck 作为内联元素保持在一条水平线上.

![overview](http://res.beanie.top/BoxedCheck/demo5.png)

	<div class="boxed-check-group boxed-check-default">
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-inline" checked>
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-inline">
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-inline">
	        <div class="boxed-check-label">Default</div>
	    </label>
	</div>

需要更大或更小的 BoxedCheck 吗 ? 添加 ```.boxed-check-lg``` 或者 ```.boxed-check-sm``` 类可以设置按钮的不同尺寸.

![overview](http://res.beanie.top/BoxedCheck/demo6.png)
 
	<div class="boxed-check-group boxed-check-default boxed-check-lg">
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-lg" checked>
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-lg">
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-lg">
	        <div class="boxed-check-label">Default</div>
	    </label>
	</div>
	<div class="boxed-check-group boxed-check-default boxed-check-sm">
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-sm" checked>
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-sm">
	        <div class="boxed-check-label">Default</div>
	    </label>
	    <label class="boxed-check boxed-check-inline">
	        <input class="boxed-check-input" type="radio" name="radio-size-sm">
	        <div class="boxed-check-label">Default</div>
	    </label>
	</div>

### 自定义布局
往 ```.boxed-check-label``` 类标签中添加代码.

![overview](http://res.beanie.top/BoxedCheck/demo4.png)

	<div class="boxed-check-group boxed-check-success">
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-overview-custom">
	        <div class="boxed-check-label" style="text-align:center;">
	            <h2>Breakfast</h2>
	            <span>Good Morning</span>
	        </div>
	    </label>
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-overview-custom">
	        <div class="boxed-check-label" style="text-align:center;">
	            <h2>Lunch</h2>
	            <span>Good Afternoon</span>
	        </div>
	    </label>
	    <label class="boxed-check">
	        <input class="boxed-check-input" type="radio" name="radio-overview-custom">
	        <div class="boxed-check-label" style="text-align:center;">
	            <h2>Supper</h2>
	            <span>Good Evening</span>
	        </div>
	    </label>
	</div>

### 联系方式
* GitHub: [Issue](https://github.com/FlyArtist/boxed-check/issues)
* 微信: ![wechat](http://res.beanie.top/x/personal_wechat.jpg)
* 邮箱: [450183439@qq.com](mailto:450183439@qq.com)
* QQ: 450183439

### 捐赠打赏

您的捐赠非常激励我们对该项目进行开发和维护，而且我们会更好地开发和维护该项目.

![wxpay](http://res.beanie.top/x/personal_wxpay.png)
![alipay](http://res.beanie.top/x/personal_alipay.png)