#Flexible Font Awesome
Flexible Font Awesome (Unofficial) by [@dnomak](http://github.com/dnomak)

## Using
How to use Flexible Font Awesome

###1. Import
Sass
```
@import "flexible-fa";
```

Less
```
@import "flexible-fa.less";
```

Stylus
```
@import "flexible-fa"
```

### 2. Icon

Html Example
```
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```

Sass Example
```
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
}
ul li:last-child a:before {
  @extend fa();
  @include fa(twitter);
}
```

Less Example
```
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
}
```

Stylus Example
```
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
ul li:last-child a:before
  @extend .fa
  fa(twitter)
```

### 2. Size

Sass Example
```
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-size(2em);
}
ul li:last-child a:before {
  @extend fa();
  @include fa(twitter);
  @include fa-size(4em);
}
```

Less Example
```
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
  .fa-size(2em);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
  .fa-size(4em);
}
```

Stylus Example
```
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
  fa-size(2em)
ul li:last-child a:before
  @extend .fa
  fa(twitter)
  fa-size(4em)
```

### 3. Align

Sass Example
```
// top, middle, bottom
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-align(top);
}
ul li:last-child a:before {
  @extend fa();
  @include fa(twitter);
  @include fa-align(bottom);
}
```

Less Example
```
// top, middle, bottom
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
  .fa-align(top);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
  .fa-align(bottom);
}
```

Stylus Example
```
// top, middle, bottom
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
  fa-align(top)
ul li:last-child a:before
  @extend .fa
  fa(twitter)
  fa-align(bottom)
```

### 4. Rotated

Sass Example
```
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-rotate(90deg);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-rotate(180deg);
}
```

Less Example
```
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
  .fa-rotate(90deg);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
  .fa-rotate(180deg);
}
```

Stylus Example
```
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
  fa-rotate(90deg);
ul li:last-child a:before
  @extend .fa
  fa(twitter)
  fa-rotate(180deg);
```

### 5. Flipped

Sass Example
```
// horizontal, vertical
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-flip(horizontal);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-flip(vertical);
}
```

Less Example
```
// horizontal, vertical
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
  .fa-flip(horizontal);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
  .fa-flip(vertical);
}
```

Stylus Example
```
// horizontal, vertical
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
  fa-flip(horizontal);
ul li:last-child a:before
  @extend .fa
  fa(twitter)
  fa-flip(vertical);
```

###6. Spin
Sass Example
```
%fa {
  @include fa();
}
ul li:fist-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-spin(2s);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-spin(4s);
}
```

Less Example
```
.fa {
  fa();
}
ul li:fist-child a:before {
  &:extend(.fa);
  .fa(github);
  .fa-spin(2s);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
  .fa-spin(4s);
}
```

Stylus Example
```
.fa
  fa()
ul li:fist-child a:before
  @extend .fa
  fa(github)
  fa-spin(2s);
ul li:last-child a:before
  @extend .fa
  fa(twitter)
  fa-spin(4s);
```