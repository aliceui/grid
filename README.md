# grid

---

Alice_990像素定宽25栅格布局_自用修改版。

---

## 使用说明

### .ui_container_25
表示990px宽度水平居中，用于外层包裹。

### .ui_grid_row
表示一行，用于包裹`.ui_grid_{{number}}`。一行内的栅格数不要超过 25。

### .ui_grid_{{number}}
表示区域跨越了多少列。数字从 1 到 25，例如`ui_grid_18`。

### .ui_alpha
修正左边距为0。

### .ui_omega
修正右边距为0。


```
<div class="ui_container_25">
	<div class="ui_grid_row">
		<div class="ui_grid_5">ui_grid_5</div>
		<div class="ui_grid_15">ui_grid_15</div>
		<div class="ui_grid_5">ui_grid_5</div>
	</div>
</div>
```


## 演示

### 基本示例


````iframe:280
<link type="text/css" rel="stylesheet" media="screen" href="src/grid.css">
<style>
.ui_grid_row div {
    background: #5DBB73;
    box-shadow: 0 1px 0 #4FAA65 inset, 0 -1px 0 #4FAA65 inset, 1px 0 0 #4FAA65 inset, -1px 0 0 #4FAA65 inset;
    transition-duration: 0.3s;
    text-align: center;
    padding: 3px 0;
}
.ui_grid_row div:hover {
    background: #72DD8D;
}
</style>

<div class="ui_container_25">

<div class="ui_grid_row">
    <div class="ui-grid-25">ui-grid-25</div>
</div>

<div class="ui-grid-row">
    <div class="ui-grid-5">ui-grid-5</div>
    <div class="ui-grid-20">ui-grid-20</div>
</div>

<div class="ui-grid-row">
    <div class="ui-grid-5">ui-grid-5</div>
    <div class="ui-grid-15">ui-grid-15</div>
    <div class="ui-grid-5">ui-grid-5</div>
</div>

<div class="ui-grid-row">
    <div class="ui-grid-21">ui-grid-21</div>
    <div class="ui-grid-4">ui-grid-4</div>
</div>

<div class="ui-grid-row">
    <div class="ui-grid-6">ui-grid-6</div>
    <div class="ui-grid-13">ui-grid-13</div>
    <div class="ui-grid-6">ui-grid-6</div>    
</div>

</div>
````


## 唠叨
原Alice.grid太支付宝项目化，而且和目前的一些grid相比还是不太成熟，也许久不曾更新...(¬_¬)
但是，亮点还是有滴，所以fork过来修改修改，自用超爽的！(´ε｀)