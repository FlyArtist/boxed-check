English [简体中文](README.CN.md)

# BoxedCheck for Radio & Checkbox v1.0.7
#### Making Radio & Checkbox into a box or card with Pure CSS and No Javascript!

### Download

* Document: [https://flyartist.github.io/boxed-check/index.html](https://flyartist.github.io/boxed-check/index.html)

* Release: [https://github.com/FlyArtist/boxed-check/releases](https://github.com/FlyArtist/boxed-check/releases)

### Overview
BoxedCheck has included components of Radio & Checkbox.

![overview](http://res.beanie.top/BoxedCheck/demo1.png)


### Quick Start

Looking to quickly add BoxedCheck to your project? Copy-paste the stylesheet ```<link>``` into your ```<head>``` to load the CSS.

```
<link rel="stylesheet" href="boxed-check.min.css">
```
### Starter Template
Be sure to have your pages set up with the latest design and development standards.


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

##### Or like this:

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

### Themes
You can use the ```.boxed-check-*``` classes to colorize BoxedCheck.

![overview](http://res.beanie.top/BoxedCheck/demo2.png)

	<div class="boxed-check-group boxed-check-default"> ... </div>
	<div class="boxed-check-group boxed-check-secondary"> ... </div>
	<div class="boxed-check-group boxed-check-primary"> ... </div>
	<div class="boxed-check-group boxed-check-success"> ... </div>
	<div class="boxed-check-group boxed-check-danger"> ... </div>
	<div class="boxed-check-group boxed-check-warning"> ... </div>
	<div class="boxed-check-group boxed-check-info"> ... </div>
	<div class="boxed-check-group boxed-check-dark"> ... </div>

### Themes With Outline
Replace the default modifier classes with the ```.boxed-check-outline-*``` ones to remove all background images and colors on any BoxedCheck.

![overview](http://res.beanie.top/BoxedCheck/demo3.png)

	<div class="boxed-check-group boxed-check-outline-default"> ... </div>
	<div class="boxed-check-group boxed-check-outline-secondary"> ... </div>
	<div class="boxed-check-group boxed-check-outline-primary"> ... </div>
	<div class="boxed-check-group boxed-check-outline-success"> ... </div>
	<div class="boxed-check-group boxed-check-outline-danger"> ... </div>
	<div class="boxed-check-group boxed-check-outline-warning"> ... </div>
	<div class="boxed-check-group boxed-check-outline-info"> ... </div>
	<div class="boxed-check-group boxed-check-outline-dark"> ... </div>

### Inline & Size
BoxedCheck on the same horizontal row by adding ```.boxed-check-inline``` to any ```.boxed-check```.

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

Fancy larger or smaller BoxedCheck? Add ```.boxed-check-lg``` or ```.boxed-check-sm``` for additional sizes.

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


### Using Custom Layout
Adding custom Layout into ```.boxed-check-label```.

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

### Contact
* GitHub: [Issue](https://github.com/FlyArtist/boxed-check/issues)
* Wechat: ![wechat](http://res.beanie.top/x/personal_wechat.jpg)
* Email: [450183439@qq.com](mailto:450183439@qq.com)
* QQ: 450183439

### Donate

Your donation is a great encouragement and support to the project. We will continue to develop and maintain.

![wxpay](http://res.beanie.top/x/personal_wxpay.png)
![alipay](http://res.beanie.top/x/personal_alipay.png)