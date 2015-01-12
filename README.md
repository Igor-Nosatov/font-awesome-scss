#Flexible Font Awesome
Flexible Font Awesome Unofficial by @dnomak - http://github.com/dnomak

## Using

**Html**
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```

###1. Import
**Sass**
```scss
@import "flexible-fa";
```

**Less**
```less
@import "flexible-fa.less";
```

**Stylus**
```
@import "flexible-fa"
```

### 2. Icon

**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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

**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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

**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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

**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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

**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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
**Sass**
```scss
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

**Less**
```less
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

**Stylus**
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
