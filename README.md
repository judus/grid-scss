# grid-scss
Some helper mixins for CSS grids

##### Using flex-box:
```scss
  .container {
    @include grid-flex;
  }

  .colum1 {
    @include grid-col(50%);
  }

  .column2 {
    @include grid-col(50%)
  }
```

##### Using rows and cols (bootstrap-a-like):
```scss
  .container {
    @include grid-container;
  }

  .row {
    @include grid-row;
  }

  .column1 {
    @include grid-col(50%)
  }

  .column2 {
    @include grid-col(50%)
  }
```
