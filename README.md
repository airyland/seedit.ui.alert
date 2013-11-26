# alert

---

通用操作提示样式

---

致谢:图标来自 [http://www.iconfont.cn/](iconfont)

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/alert.css">

### 默认

````html
<div class="alert">
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Warning:&nbsp;Your monthly traffic is reaching limit.
</div>

<div class="alert alert-success">
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Success:&nbsp;The <a href="#" class="link">page</a> has been added.
</div>

<div class="alert alert-info">
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Info:&nbsp;You have <a href="#" class="link">198</a> unread messages.
</div>

<div class="alert alert-error">
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Danger:&nbsp;The daily <a href="#" class="link">cronjob</a> has failed.
</div>



````

### 带图标

````html
<div class="alert">
    <i class="alert-icon">&#13683</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Warning:&nbsp;Your monthly traffic is reaching limit.
</div>

<div class="alert alert-success">
    <i class="alert-icon">&#13703</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Success:&nbsp;The <a href="#" class="link">page</a> has been added.
</div>

<div class="alert alert-info alert-shadow">
    <i class="alert-icon">&#13542</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Info:&nbsp;You have <a href="#" class="link">198</a> unread messages.
</div>

<div class="alert alert-error alert-shadow">
    <i class="alert-icon">&#13544</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Danger:&nbsp;The daily <a href="#" class="link">cronjob</a> has failed.
</div>
````


### 尺寸

````html
<div class="alert alert-info alert-shadow alert-sm">
    <i class="alert-icon">&#13542</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Info:&nbsp;You have <a href="#" class="link">198</a> unread messages.
</div>

<div class="alert alert-error alert-sx">
    <i class="alert-icon">&#13544</i>
    <a href="javascript:" class="alert-close"><i class="alert-icon">&#13540</i></a>
    Danger:&nbsp;The daily <a href="#" class="link">cronjob</a> has failed.
</div>
````