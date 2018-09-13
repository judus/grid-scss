# grid-scss
Some helper mixins for CSS grids

#### Using flex-box:

4 columns of equal size with children elements 
```scss
  .container {
    @include grid-cols(4);
  }
```

3 columns with specific sizes
```scss
  .container {
    @include grid-flex;
  }

  .column-left {
    @include grid-col(25%);
  }

  .column-center {
    @include grid-col(50%);
  }
  
  .column-right {
    @include grid-col(25%);
  }
```

#### Using rows and cols, no flex:

6 columns of equal size
```scss
  .container {
    @include grid-container;
  }

  .row {
    @include grid-row;
  }

  .column {
    @include grid-col(16.6666);
  }
```