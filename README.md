#flexible-fa
Flexible Font Awesome by @dnomak · http://dnomak.com

## Using Sass
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```
####1. Import
```scss
@import "flexible-fa";
```
####2. Icon
```scss
%fa {
  @include fa();
}
ul li:first-child a:before {
  @extend fa();
  @include fa(github);
}
ul li:last-child a:before {
  @extend fa();
  @include fa(twitter);
}
```
#### 3. Size
```scss
%fa {
  @include fa();
}
ul li:first-child a:before {
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
####4. Align
```scss
// top, middle, bottom
%fa {
  @include fa();
}
ul li:first-child a:before {
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
#### 5. Rotated
```scss
%fa {
  @include fa();
}
ul li:first-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-rotate(90deg);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-rotate(180deg);
}
```
####6. Flipped
```scss
// horizontal, vertical
%fa {
  @include fa();
}
ul li:first-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-flip(horizontal);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-flip(vertical);
}
```
####7. Spin
```scss
%fa {
  @include fa();
}
ul li:first-child a:before {
  @extend fa();
  @include fa(github);
  @include fa-spin(2s);
}
ul li:last-child a:before {
  @extend fa();
  @include fa-spin(4s);
}
```

## Using Less
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```
####1. Import
```less
@import "flexible-fa.less";
```
####2. Icon
```less
.fa {
  .fa();
}
ul li:first-child a:before {
  &:extend(.fa);
  .fa(github);
}
ul li:last-child a:before {
  &:extend(.fa);
  .fa(twitter);
}
```
#### 3. Size
```less
.fa {
  .fa();
}
ul li:first-child a:before {
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
####4. Align
```less
// top, middle, bottom
.fa {
  .fa();
}
ul li:first-child a:before {
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
#### 5. Rotated
```less
.fa {
  .fa();
}
ul li:first-child a:before {
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
####6. Flipped
```less
// horizontal, vertical
.fa {
  .fa();
}
ul li:first-child a:before {
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
####7. Spin
```less
.fa {
  .fa();
}
ul li:first-child a:before {
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

## Using Stylus
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```
####1. Import
```
@import "flexible-fa"
```
####2. Icon
```
.fa
  fa()
ul li:first-child a:before
  @extend .fa
  fa(github)
ul li:last-child a:before
  @extend .fa
  fa(twitter)
```
#### 3. Size
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
####4. Align
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
#### 5. Rotated
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
####6. Flipped
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
####7. Spin
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
