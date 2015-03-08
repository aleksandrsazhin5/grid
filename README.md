#grid
Генератор модульной сетки на Less

##less
```less
@import "grid.less";

@class: s;
@grid-columns: 12;
@grid-gutter-width: 30px;

.row{
  .make-grid(@class, @grid-columns, @grid-gutter-width);
}
```

##html
```html
<div class="row">
    <div class="col s2"></div>
    <div class="col s2 offset-s2"></div>
    <div class="col s2"></div>
</div>
```