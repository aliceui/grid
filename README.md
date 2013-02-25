# grid

---

990像素定宽25栅格布局。

---

## 使用说明

### .ui-grid-row

表示一行，用于包裹`.ui-grid-{{number}}`。一行内的栅格数不要超过 25。

### .ui-grid-{{number}}

表示区域跨越了多少列。数字从 1 到 25，例如`ui-grid-18`。

```
<div class="ui-grid-row">
    <div class="ui-grid-5">ui-grid-5</div>
    <div class="ui-grid-15">ui-grid-15</div>
    <div class="ui-grid-5">ui-grid-5</div>
</div>
```

## 演示

````iframe:280
<link type="text/css" rel="stylesheet" media="screen" href="../src/grid.css">
<style>
.wrapper {
    width: 990px;
    margin: 30px auto 0;
}
.ui-grid-row div {
    background: #5DBB73;
    box-shadow: 0 1px 0 #4FAA65 inset, 0 -1px 0 #4FAA65 inset, 1px 0 0 #4FAA65 inset, -1px 0 0 #4FAA65 inset;
    transition-duration: 0.3s;
    text-align: center;
    padding: 3px 0;
}
.ui-grid-row div:hover {
    background: #72DD8D;
}
</style>

<div class="wrapper">

<div class="ui-grid-row">
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
