# font-awesome-scss
Font Awesome Scss Plus

## Install

```scss
@import "font-awesome";
```

## Using

### Html
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```

### Icon
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
}
```

### Size
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-size(2em);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-size(2em);
}
```

### Left
```scss
ul li:first-child a:after {
  @include fa;
  @include fa(github);
  @include fa-left(10px);
}
ul li:last-child a:after {
  @include fa;
  @include fa(twitter);
  @include fa-left(20px);
}
```

### Right
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-right(10px);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-right(20px);
}
```

### Align
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-size(2em);
  @include fa-align(top);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-size(2em);
  @include fa-align(bottom);
}
```

### Rotated
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-rotate(90deg);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-rotate(180deg);
}
```

### Flipped
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-flip(horizontal);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-flip(vertical);
}
```

### Spin
```scss
@include fa-spin;
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-spin(1s);
}
ul li:last-child a:before{
  @include fa;
  @include fa(twitter);
  @include fa-spin(5s);
}
```
