## Grid_990像素定宽25栅格布局_自用版

## 使用说明

### . container_25
> 表示990px宽度水平居中，用于外层包裹。

### . grid_row
> 表示一行，用于包裹`. grid_{{number}}`。一行内的栅格数不要超过 25。

### . grid_{{number}}
> 表示区域跨越了多少列。数字从 1 到 25，例如` grid_18`。

### . alpha
> 修正左边距为0。

### . omega
> 修正右边距为0。

## 演示

```html
<div class=" container_25">
	<div class=" grid_row">
		<div class=" grid_5"> grid_5</div>
		<div class=" grid_15"> grid_15</div>
		<div class=" grid_5"> grid_5</div>
	</div>
</div>
```

```html
<link type="text/css" rel="stylesheet" media="screen" href="src/grid.css">
<style>
. grid_row div {
    background: #5DBB73;
    box-shadow: 0 1px 0 #4FAA65 inset, 0 -1px 0 #4FAA65 inset, 1px 0 0 #4FAA65 inset, -1px 0 0 #4FAA65 inset;
    transition-duration: 0.3s;
    text-align: center;
    padding: 3px 0;
}
. grid_row div:hover {
    background: #72DD8D;
}
</style>

<div class=" container_25">

<div class=" grid_row">
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
```


## 唠叨
原Alice.grid太支付宝项目化，而且和目前的一些grid相比还是不太成熟，也许久不曾更新...(¬_¬)。但是，亮点还是有滴，所以fork过来修改修改，自用超爽的！(´ε｀)