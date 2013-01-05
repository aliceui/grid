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
